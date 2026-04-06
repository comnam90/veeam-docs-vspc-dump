---
title: "Managing Veeam Backup & Replication Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_backup_jobs.html"
last_updated: "11/26/2025"
product_version: "9.1.0.30636"
---

# Managing Veeam Backup & Replication Jobs


You can manage Veeam Backup & Replication jobs configured on client and hosted  backup servers, and assign jobs created on hosted servers to client companies. Veeam Service Provider Console supports the following jobs:

* VM protection jobs:

* Backup jobs
* Replication jobs
* SureBackup jobs
* Backup copy jobs
* Backup to tape jobs
* VM copy jobs
* SQL database log backup jobs
* Oracle database log backup jobs
* PostgreSQL database log backup jobs
* Storage snapshot jobs
* CDP policies

* File protection jobs:

* File share backup jobs
* File share backup copy jobs
* File copy jobs
* File to tape jobs

* Object storage jobs:

* Object storage backup jobs
* Object storage backup copy jobs

* Computer protection jobs:

* Agent backup jobs
* Agent backup copy jobs
* SureBackup jobs

Other job types are not supported in Veeam Service Provider Console.

To access Veeam Backup & Replication job management, you must have at least one Veeam Backup & Replication server with configured jobs in the hosted or client infrastructure.

You can start, stop and retry jobs, remove jobs, enable and disable jobs, view and export job details, download job logs and session reports.

You can also create or edit VM backup jobs for client companies on hosted Veeam Backup & Replication servers.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Only Portal Administrator can create and edit Hyper-V backup jobs, backup copy jobs, and jobs on client Veeam Backup & Replication servers.

Only Portal Administrator and Portal Operator can assign jobs to client companies.

In This Section

* [Creating Backup Jobs](create_backup_jobs.md)
* [Modifying Backup Job Settings](modify_vbr_job.md)
* [Assigning Jobs to Companies](assign_vbr_jobs.md)
* [Starting, Stopping and Retrying Jobs](start_stop_restart_jobs.md)
* [Disabling and Enabling Jobs](disable_enable_jobs.md)
* [Restoring Veeam Backup & Replication Workloads](restore_vbr.md)
* [Downloading Job Logs and Session Report](download_job_logs.md)


