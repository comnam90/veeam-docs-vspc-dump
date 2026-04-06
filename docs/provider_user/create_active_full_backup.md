---
title: "Creating Active Full Backups"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/create_active_full_backup.html"
last_updated: "6/6/2025"
product_version: "9.1.0.30636"
---

# Creating Active Full Backups


You can create an active full backup, and add it to the backup chain on the target storage. The active full backup resets the backup chain. All subsequent incremental backups use the active full backup as a starting point. The previously used full backup will remain on the target storage until it is removed from the backup chain according to the retention policy. For details on active full backups, see section [Active Full Backup](https://helpcenter.veeam.com/docs/agentforwindows/userguide/active_full_backup.html) of the Veeam Agent for Microsoft Windows User Guide.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Creating Active Full Backups

To perform active full backup:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Find the necessary Veeam backup agent in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
4. In the Agent Backup Job window, select one or more backup jobs.
5. At the top of the list, click Actions > Active Full.

Alternatively, you can right-click the necessary backup job and choose Actions > Active Full.


