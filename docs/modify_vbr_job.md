---
title: "Modifying Backup Job Settings"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_vbr_job.html"
last_updated: "1/27/2026"
product_version: "9.2.0.33215"
---

# Modifying Backup Job Settings


To modify Veeam Backup & Replication job settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. Choose the necessary job in the list.
4. At the top of the list, click Edit.

Alternatively, you can right-click the necessary job and select Edit.

Note that you cannot modify job settings for companies with removed VMware vSphere tag, VMware Cloud Director organizations mapping or hosted Veeam Backup & Replication resources.

For servers running Veeam Backup & Replication version 13.0.1 or later: Veeam Service Provider Console will open the Veeam Backup & Replication Edit Backup Job or Edit Backup Copy Job wizard. For details on how to edit a backup job or backup copy job in the Veeam Backup & Replication Web UI, see sections [Editing Job Settings](https://helpcenter.veeam.com/docs/vbr/userguide/editing_jobs_web.html) and [Editing Backup Copy Job Settings](https://helpcenter.veeam.com/docs/vbr/userguide/backup_copy_edit.html) in the Veeam Backup & Replication User Guide.

1. For servers running Veeam Backup & Replication version 13 or earlier: In the Edit Job wizard, modify Veeam Backup & Replication job settings.

For details on backup job settings, see [Creating Backup Jobs](create_backup_jobs.md).

1. Save changes.


