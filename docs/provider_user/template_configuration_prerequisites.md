---
title: "Before You Begin"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/template_configuration_prerequisites.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Before You Begin


Before you configure a backup policy, check the following prerequisites:

* The target location where you plan to store backup files must have enough free space.
* Available backup job options depend on the Veeam backup agent operation mode. For details, see section [Product Editions](https://helpcenter.veeam.com/docs/agentforwindows/userguide/license_editions.html) of the Veeam Agent for Microsoft Windows User Guide.
* The number of jobs that you can assign to a Veeam backup agent depends on the product edition. For details on the limitation of the number of jobs, see section [Backup Job](https://helpcenter.veeam.com/docs/agentforwindows/userguide/scheduled_backup_job.html) of the Veeam Agent for Microsoft Windows User Guide.
* [For Veeam Backup & Replication repository targets] If you plan to use a Veeam Backup & Replication repository as a target for backups, you must pre-configure user access permissions on this backup repository. For details, see section [Setting Up User Permissions on Backup Repositories](https://helpcenter.veeam.com/docs/agentforwindows/userguide/integrate_permissions.html) of the Veeam Agent for Microsoft Windows User Guide.

Backup has the following limitations:

* You cannot save a backup of the entire computer on the local computer disk. Use one of the following options as a target location:

* External hard drive or USB drive

* Network shared folder
* Veeam backup repository
* Veeam Cloud Connect repository

* Veeam Agent for Microsoft Windows does not back up data to which symbolic links are targeted. It only backs up the path information that the symbolic links contain. After restore, identical symbolic links are created in the restore destination.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator.


