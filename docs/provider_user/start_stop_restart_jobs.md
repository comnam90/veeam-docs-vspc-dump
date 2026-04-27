---
title: "Starting, Stopping and Retrying Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/start_stop_restart_jobs.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Starting, Stopping and Retrying Jobs


You can start, stop and retry VM, computer, database and file jobs without accessing the managed backup servers. For example, if a backup job failed, you can manually retry or start this job in Veeam Service Provider Console to avoid data loss.

Starting Jobs

To start one or more Veeam Backup & Replication jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Virtual Infrastructure — select this tab to start VM protection jobs (Backup, Replication, SureBackup, Backup copy, Backup to tape, VM copy, Storage snapshot)
* Data Backup > Virtual Infrastructure — select this tab to start file protection jobs (File share backup, File share backup copy, File copy, File to tape)
* Data Backup > Object Storage — select this tab to start object storage jobs (Object storage data backup, Object storage data backup copy)
* Computers > Managed by Backup Server — select this tab to start jobs for Veeam backup agents managed by client Veeam Backup & Replication servers (Backup, Backup copy, SureBackup)

1. Select the necessary jobs in the list.
2. At the top of the list, click Actions > Start.

Alternatively, you can right-click the necessary job and select Actions > Start.

Stopping Jobs

To stop one or more running Veeam Backup & Replication jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Virtual Infrastructure — select this tab to stop VM protection jobs (Backup, Replication, SureBackup, Backup copy, Backup to tape, VM copy, Storage snapshot)
* Data Backup > Virtual Infrastructure — select this tab to stop file protection jobs (File share backup, File share backup copy, File copy, File to tape)
* Data Backup > Object Storage — select this tab to stop object storage jobs (Object storage data backup, Object storage data backup copy)
* Computers > Managed by Backup Server — select this tab to stop jobs for Veeam backup agents managed by client Veeam Backup & Replication servers (Backup, Backup copy, SureBackup)

1. Select the necessary jobs in the list.
2. At the top of the list, click Actions > Stop.

Alternatively, you can right-click the necessary job and select Actions > Stop.

1. In the Stop Job window, select how you want to stop the job:

* Click Gracefully, if you want Veeam Backup & Replication to produce a new restore point only for those workloads that have already been processed and for workloads that are being processed at the moment.
* Click Immediately, if you want Veeam Backup & Replication to produce a new restore point only for those workloads that have already been processed by the time you stop the job.

Retrying Jobs

To restart one or more failed Veeam Backup & Replication jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Virtual Infrastructure — select this tab to retry VM protection jobs (Backup, Replication)
* Data Backup > Virtual Infrastructure — select this tab to retry file share backup jobs (File share backup, File share backup copy, File copy, File to tape)
* Data Backup > Object Storage — select this tab to retry object storage jobs (Object storage data backup, Object storage data backup copy)

1. Select the necessary jobs in the list.
2. At the top of the list, click Actions > Retry.

Alternatively, you can right-click the necessary job and select Actions > Retry.


