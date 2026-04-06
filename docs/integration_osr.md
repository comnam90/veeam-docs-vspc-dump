---
title: "Integration with Object Storage Repositories"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_osr.html"
last_updated: "8/19/2025"
product_version: "9.1.0.30636"
---

# Integration with Object Storage Repositories


Integration with object storage allows you to configure backup agent policies in Veeam Service Provider Console so that object storage repositories are used as cloud repositories. To do that:

1. Connect object storage repository to your Veeam Cloud Connect server as described in the [Backup to Object Repository](https://helpcenter.veeam.com/docs/backup/cloud/cc_object_storage.html) section of the Veeam Cloud Connect Guide.

Consider the following:

* For Amazon S3: the user account must be able to configure the s3\* and iam\* permissions.
* For Microsoft Azure Storage and Google Cloud Storage: helper appliance configuration required. For details on configuring helper appliances for Microsoft Azure, see section [Step 5. Specify Mount Server Settings](https://helpcenter.veeam.com/docs/vbr/userguide/azure_storage_mount_server.html?ver=13#configuring-helper-appliance) of the Veeam Backup & Replication User Guide. For details on configuring helper appliances for Google Cloud, see [Step 5. Specify Mount Server Settings](https://helpcenter.veeam.com/docs/vbr/userguide/google_cloud_storage_mount_server.html?ver=13#configuring-helper-appliance) of the Veeam Backup & Replication User Guide.
* For S3 Compatible, IBM Cloud Object Storage and Wasabi Cloud Storage: access permissions configuration required. For details, see section [Access Permissions](https://helpcenter.veeam.com/docs/backup/cloud/cc_object_storage_permissions.html) of the Veeam Cloud Connect Guide.

1. Set the object storage repository as default for specific company as described in the [Allocating Cloud Backup Resources](allocate_cloud_backup_resources.md) section.
2. Create a new backup policy for specific computers as described in the [Configuring Backup Policies](configure_backup_policies.md) section.

The backup policy will target to the selected default repository automatically.

After you have configured the integration, you can view and export object storage job details in Veeam Service Provider Console web portal, charge for protected workloads and generate backup reports to track the efficiency of object storage protection.


