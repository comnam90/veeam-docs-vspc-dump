---
title: "Managing Veeam Backup & Replication Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/manage_backup_jobs.html"
last_updated: "11/7/2023"
product_version: "9.1.0.30636"
---

# Managing Veeam Backup & Replication Jobs


You can manage Veeam Backup & Replication jobs configured on your backup servers, and jobs assigned to your company by your service provider. Veeam Service Provider Console supports the following jobs:

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

To access Veeam Backup & Replication job management, you must have at least one Veeam Backup & Replication server with configured jobs in your infrastructure or at least one Veeam Backup & Replication job assigned to you by your service provider.

You can start, stop and retry jobs, remove jobs, enable and disable jobs, view and export job details, download job logs and session reports.

You can also create or edit VM backup jobs for your company on the Veeam Backup & Replication servers of your service provider.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

In This Section

* [Creating Backup Jobs](create_backup_jobs.md)
* [Modifying Backup Job Settings](modify_vbr_job.md)
* [Starting, Stopping and Retrying Jobs](start_stop_restart_jobs.md)
* [Disabling and Enabling Jobs](disable_enable_jobs.md)
* [Downloading Job Logs and Session Report](download_job_logs.md)


