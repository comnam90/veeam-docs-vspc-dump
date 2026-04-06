---
title: "Creating Backup Copy Job"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_copy_job.html"
last_updated: "10/27/2025"
product_version: "9.1.0.30636"
---

# Creating Backup Copy Job


You can configure backup copy jobs to create several instances of the same backup in different locations. Backup copies have the same format as those created by backup jobs.

Before you configure a backup copy job, check prerequisites specified in the [Before You Begin](https://helpcenter.veeam.com/docs/vbr/userguide/backup_copy_before_you_begin_web.html) section of the Veeam Backup & Replication User Guide.

|  |
| --- |
| Note: |
| This functionality is available for Veeam Backup & Replication version 13.0.1 or later. |

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Creating Backup Copy Jobs

To create a backup copy job:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. At the top of the jobs list, click Configuration and select New > Backup Copy Job.

Veeam Service Provider Console will open the Create Job window.

1. Select the server on which you want to create the job and click Create.

Veeam Service Provider Console will open the New Backup Copy Job wizard from the Veeam Backup & Replication Web UI. Follow the the procedure as described in the Veeam Backup & Replication User Guide, starting from [Step 2. Specify Job Name and Copy Mode](https://helpcenter.veeam.com/docs/vbr/userguide/backup_copy_name_web.html).


