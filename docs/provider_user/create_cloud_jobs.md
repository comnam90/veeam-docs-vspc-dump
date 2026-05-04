---
title: "Creating Veeam Backup for Public Clouds Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/create_cloud_jobs.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Creating Veeam Backup for Public Clouds Policies


To create new Veeam Backup for Public Clouds policies, you can access Veeam Backup for Public Clouds portal directly from Veeam Service Provider Console.

To access Veeam Backup for Public Clouds portal:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to view cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to view cloud file protection policies (Snapshot, Replica snapshot)
* Cloud Databases — select this tab to view cloud database protection policies (Backup, Snapshot, Replica snapshot, Archive)

1. At the top of the list, click Create Policy.

[For Cloud Database and Data Backup policies] From the drop-down list, select type of workload for which you want to create a policy.

1. In the Create Policy window, select Veeam Cloud Connect site on which Veeam Backup for Public Clouds appliance is deployed.
2. Select the necessary appliance in the list.
3. Click Create.

Veeam Service Provider Console will open a Veeam Backup for Public Clouds policy creation wizard.

For details on Veeam Backup for Veeam Backup for Public Clouds policies settings, see the following sections of the Veeam Backup for Veeam Backup for Public Clouds User Guides:

* [Performing Backup](https://helpcenter.veeam.com/docs/vbaws/guide/backup.html) of the Veeam Backup for AWS User Guide
* [Performing Backup](https://helpcenter.veeam.com/docs/vbazure/guide/performing_backup.html) of the Veeam Backup for Microsoft Azure User Guide
* [Performing Backup](https://helpcenter.veeam.com/docs/vbgc/guide/performing_backup.html) of the Veeam Backup for Google Cloud User Guide


