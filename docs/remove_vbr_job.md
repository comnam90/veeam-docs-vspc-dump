---
title: "Removing Veeam Backup & Replication Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_vbr_job.html"
last_updated: "1/27/2026"
product_version: "9.2.0.33215"
---

# Removing Veeam Backup & Replication Jobs


If you no longer want to protect data, you can remove a backup job configuration.

To remove a job configuration from Veeam Backup & Replication:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. Choose the necessary jobs.
4. At the top of the list, click Remove.

Alternatively, you can right-click the necessary job and select Remove.

1. In the Remove Job window, click Yes to confirm removal.

After you remove a backup job configuration, all backups created by this job will become orphaned. Orphaned backups are retained according to the background retention process. For details, see section [Background Retention](https://helpcenter.veeam.com/docs/vbr/userguide/background_retention_job.html?ver=13) of the Veeam Backup & Replication User Guide.

|  |
| --- |
| Note: |
| This functionality is available for Veeam Backup & Replication version 12.1 or later. |


