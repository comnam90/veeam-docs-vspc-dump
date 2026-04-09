---
title: "Creating Hyper-V Backup Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_hyperv_job.html"
last_updated: "2/3/2026"
product_version: "9.2.0.33215"
---

# Creating Hyper-V Backup Jobs


You can create backup jobs that will suit VM protection requirements for managed Microsoft Hyper-V VMs.

Before you configure a backup job, check prerequisites specified in the [Considerations and Limitations](https://helpcenter.veeam.com/docs/vbr/userguide/backup_job_limitations_hv.html) section of the Veeam Backup & Replication User Guide.

|  |
| --- |
| Note: |
| This functionality is available for Veeam Backup & Replication version 13.0.1 or later. |

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Creating Hyper-V Backup Jobs

To create a backup job:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. At the top of the jobs list, click New > Hyper-V Backup Job.

Alternatively, you can right-click on the jobs list and select New > Hyper-V Backup Job.

Veeam Service Provider Console will open the Create Job window.

1. Select the server on which you want to create the job and click Create.

Veeam Service Provider Console will open the New Backup Job wizard from the Veeam Backup & Replication Web UI. Follow the procedure as described in the Veeam Backup & Replication User Guide, starting from [Step 2. Specify Job Name and Description](https://helpcenter.veeam.com/docs/vbr/userguide/backup_job_name_hv_web.html).


