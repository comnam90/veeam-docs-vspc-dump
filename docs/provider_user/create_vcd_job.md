---
title: "Creating Cloud Director Backup Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/create_vcd_job.html"
last_updated: "3/12/2024"
product_version: "9.1.0.30636"
---

# Creating Cloud Director Backup Jobs


You can create backup jobs that will suit data protection requirements for managed VMware Cloud Director organizations.

Before you create a backup job, check prerequisites described in the [Creating Backup Jobs for Cloud Director VMs](https://helpcenter.veeam.com/docs/vbr/userguide/vcloud_director_perform_backup.html#considerations-and-limitations) section of the Veeam Backup & Replication User Guide.

Note that you cannot schedule backup jobs configured on Veeam Backup & Replication servers that were assigned to you by your service provider if your service provider has disabled scheduling jobs on these servers for your company. To configure schedule for these backup jobs, contact your service provider.

To create a backup job, complete the following steps:

1. [Launch the New Cloud Director Backup Job wizard](vcd_job_launch_wizard.md).
2. [Specify the backup job name and description](vcd_job_name_description.md).
3. [Select objects to back up](vcd_job_scope.md).
4. [Specify backup repository settings](vcd_job_repository.md).
5. [Specify guest OS processing options](vcd_job_guest_os.md).
6. [Configure backup job schedule](vcd_job_schedule.md).
7. [Review backup job settings](vcd_job_review.md).


