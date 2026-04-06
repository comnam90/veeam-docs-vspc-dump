---
title: "Managing Veeam Backup for Public Clouds"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vb_cloud_jobs.html"
last_updated: "10/22/2024"
product_version: "9.1.0.30636"
---

# Managing Veeam Backup for Public Clouds


You can manage Veeam Backup for Public Clouds policies configured on Veeam Backup for Public Clouds appliances managed by Veeam Service Provider Console. Veeam Service Provider Console supports the following policies:

* Backup policies
* Snapshots
* Replication snapshots
* Archive backup policies

To access policy management, you must have at least one Veeam Backup for Public Clouds appliance in the hosted or client infrastructure.

You can create policies, modify policies settings, start and stop policies and remove policies.

Before You Begin

Before you start managing Veeam Backup for Public Clouds policies, make sure that you have configured cloud appliance account credentials and guest OS account credentials for managed appliances and verified the appliance certificate. You can configure accounts credentials as a part of appliance deployment process or by modifying connected appliance settings.

For details on connecting cloud appliances in Veeam Service Provider Console, see [Adding Veeam Backup for Amazon Web Services Appliances](clouds_add_aws.md), [Adding Veeam Backup for Microsoft Azure Appliances](clouds_add_azure.md) and [Adding Veeam Backup for Google Cloud Appliances](clouds_add_google.md). For details on modifying appliance settings, see [Modifying Appliances](clouds_edit_appliances.md).

For details on verifying cloud appliance certificates, see [Verifying Appliances](clouds_verify_certificate.md).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

In This Section

* [Creating Veeam Backup for Public Clouds Policies](create_cloud_jobs.md)
* [Modifying Veeam Backup for Public Clouds Policies](edit_cloud_jobs.md)
* [Removing Veeam Backup for Public Clouds Policies](remove_cloud_jobs.md)
* [Starting and Stopping Veeam Backup for Public Clouds Policies](start_stop_cloud_jobs.md)
* [Disabling and Enabling Veeam Backup for Public Clouds Policies](disable_enable_cloud_jobs.md)
* [Restoring Veeam Backup for Public Clouds Workloads](restore_clouds.md)
* [Accessing Veeam Backup for Public Clouds Portal](access_vb_cloud_portal.md)
* [Viewing and Exporting Job Details](export_cloud_job_details.md)
* [Viewing and Exporting Protected Workload Details](export_cloud_workload_details.md)
* [Viewing and Exporting Cloud Backup Appliance Details](export_cloud_appliance_details.md)


