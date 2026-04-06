---
title: "Creating vSphere Backup Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/create_vsphere_job.html"
last_updated: "9/20/2024"
product_version: "9.1.0.30636"
---

# Creating vSphere Backup Jobs


You can create backup jobs that will suit VM protection requirements for managed companies.

Before you create a backup job, check prerequisites described in the [Considerations and Limitations](https://helpcenter.veeam.com/docs/vbr/userguide/backup_job_limitations.html) section of the Veeam Backup & Replication User Guide.

Note that you cannot schedule backup jobs configured on Veeam Backup & Replication servers that were assigned to you by your service provider if your service provider has disabled scheduling jobs on these servers for your company. To configure schedule for these backup jobs, contact your service provider.

To create a backup job, complete the following steps:

1. [Launch the New vSphere Backup Job wizard](vbr_job_launch_wizard.md).
2. [Specify the backup job name and description](vbr_job_name_description.md).
3. [Select objects to back up](vbr_job_scope.md).
4. [Specify backup repository settings](vbr_job_repository.md).
5. [Specify guest OS processing options](vbr_job_guest_os.md).
6. [Configure backup job schedule](vbr_job_schedule.md).
7. [Review backup job settings](vbr_job_review.md).


