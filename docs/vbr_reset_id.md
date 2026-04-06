---
title: "Resetting Veeam Backup & Replication Installation ID"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbr_reset_id.html"
last_updated: "9/1/2025"
product_version: "9.1.0.30636"
---

# Resetting Veeam Backup & Replication Installation ID


In Veeam Service Provider Console, you can reset installation IDs for managed Veeam Backup & Replication servers. Resetting installation IDs may be required if you cloned several Veeam Backup & Replication servers from one deployment. Cloned backup servers have the same installation IDs, which affects license usage statistics and reporting.

|  |
| --- |
| Note: |
| You can reset installation ID in Veeam Service Provider Console only for Windows Veeam Backup & Replication servers. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator.

Resetting Veeam Backup & Replication Installation ID

To reset installation ID of managed Veeam Backup & Replication servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Servers tab.
3. Select the necessary Veeam Backup & Replication servers in the list.
4. At the top of the list, click Server Actions > Regenerate Installation ID.

Alternatively, you can right-click the necessary server, choose Server Actions and select Regenerate Installation ID.

1. In the Regenerate Installation ID window, click Yes.

Veeam Service Provider Console will generate a unique installation IDs and restart the Veeam Backup Service for the selected Veeam Backup & Replication servers.


