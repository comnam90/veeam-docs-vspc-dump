---
title: "Uninstalling Management Agents"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/delete_management_agents.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Uninstalling Management Agents


You can uninstall Veeam Service Provider Console management agents from managed computers. After you uninstall management agents from managed computers, you will no longer be able to manage Veeam products on these computers:

* Veeam Backup & Replication and Veeam Backup Enterprise Manager on Veeam backup servers.
* Veeam Backup for Microsoft 365 and Veeam ONE servers.
* Veeam backup agents on managed computers.

When you uninstall a management agent from a computer protected with Veeam backup agent, the Veeam backup agent will be switched to the Unmanaged mode. The number of used and total licenses in the Veeam Service Provider Console license pool will be updated.

|  |
| --- |
| Note: |
| You cannot uninstall management agents in the following cases:   * The management agent has the Rejected status. * * The management agent is installed on a computer on which a node of the High Availability cluster is deployed. To uninstall this management agent, you must delete the cluster. For details, see [Managing Backup High Availability Clusters](vbr_ha_clusters.md#remove). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Uninstalling Management Agents from Discovered Computers

To uninstall Veeam Service Provider Console management agents from one or more managed computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. Select the necessary computers in the list.
4. At the top of the list, click Management Agent and choose Delete.

Alternatively, you can right-click the necessary computer, choose Management Agent and select Delete.

1. In the displayed window, click Yes to confirm management agent removal.

Uninstalling Management Agents from Discovered Veeam Backup & Replication Servers

To uninstall Veeam Service Provider Console management agents from one or more Veeam Backup & Replication servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Servers tab.
3. Select the necessary servers in the list.
4. At the top of the list, click Delete Agent.

Alternatively, you can right-click the necessary backup server and choose Delete Agent.

1. In the displayed window, click Yes to confirm management agent removal.

Uninstalling Management Agents from Discovered Veeam ONE Servers

To uninstall Veeam Service Provider Console management agents from one or more Veeam ONE servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the ONE Servers tab.
3. Select the necessary servers in the list.
4. At the top of the list, click Delete Agent.

Alternatively, you can right-click the necessary Veeam ONE server and choose Delete Agent.

1. In the displayed window, click Yes to confirm management agent removal.

Uninstalling Management Agents from Discovered Veeam Backup for Microsoft 365 Servers

To uninstall Veeam Service Provider Console management agents from one or more Veeam Backup for Microsoft 365 servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Microsoft 365 Backup Servers tab.
3. Select the necessary servers in the list.
4. At the top of the list, click Delete Agent.

Alternatively, you can right-click the necessary Veeam Backup for Microsoft 365 server and choose Delete Agent.

1. In the displayed window, click Yes to confirm management agent removal.


