---
title: "Disabling and Enabling Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/disable_enable_jobs.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Jobs


You can disable and enable scheduled VM, computer and file jobs without accessing the Veeam Backup & Replication console on managed backup servers. For example, to prevent a backup job from writing data to a cloud repository, you can temporarily disable this job.

Disabling Jobs

A disabled job will not start by the schedule. If you disable a job that has a child job (such as a SQL database log backup,Oracle database log backup or PostgreSQL database log backup), both the parent and the child jobs will be disabled.

To disable one or more scheduled jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Virtual Infrastructure — select this tab to disable VM protection jobs (Backup, Replication, SureBackup, Backup copy, Backup to tape, VM copy, Storage snapshot, CDP policy)
* Data Backup > Virtual Infrastructure — select this tab to disable file protection jobs (File share backup, File share backup copy, File copy, File to tape)
* Data Backup > Object Storage — select this tab to disable object storage jobs (Object storage data backup, Object storage data backup copy)
* Computers > Managed by Backup Server — select this tab to disable jobs for Veeam backup agents managed by client Veeam Backup & Replication servers (Backup, Backup copy, SureBackup)

1. Select the necessary jobs in the list.
2. At the top of the list, click Scheduling > Disable.

Alternatively, you can right-click the necessary job and select Scheduling > Disable.

Enabling Jobs

To enable one or more previously disabled jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Virtual Infrastructure — select this tab to enable VM protection jobs (Backup, Replication, SureBackup, Backup copy, Backup to tape, VM copy, Storage snapshot, CDP policy)
* Data Backup > Virtual Infrastructure — select this tab to enable file protection jobs (File share backup, File share backup copy, File copy, File to tape)
* Data Backup > Object Storage — select this tab to enable object storage jobs (Object storage data backup, Object storage data backup copy)
* Computers > Managed by Backup Server — select this tab to enable jobs for Veeam backup agents managed by client Veeam Backup & Replication servers (Backup, Backup copy, SureBackup)

1. Select the necessary jobs in the list.
2. At the top of the list, click Scheduling > Enable.

Alternatively, you can right-click the necessary job and select Scheduling > Enable.


