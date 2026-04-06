---
title: "Removing Veeam Backup & Replication Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbr_remove_servers.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Veeam Backup & Replication Servers


To remove a Veeam Backup & Replication server, you need to uninstall Veeam Service Provider Console management agents from hosted Veeam Backup & Replication or Veeam Backup Enterprise Manager servers.

|  |
| --- |
| Note: |
| You cannot uninstall management agents in the following cases:   * The management agent is in the Rejected status. For details on management agent connection status, see [Accepting and Rejecting Management Agent Connections](accept_reject_connections.md). * The management agent is installed on a computer on which Veeam Cloud Connect is deployed. |

Removing Veeam Backup & Replication Servers

To remove Veeam Service Provider Console management agent from hosted Veeam Backup & Replication or Veeam Backup Enterprise Manager server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup & Replication plugin tile.
4. In the menu on the left, click Infrastructure.
5. Select the necessary servers in the list.
6. At the top of list, click Remove.
7. In the confirmation window, click Yes.

To remove management agents from client Veeam Backup & Replication or Veeam Backup Enterprise Manager servers, go to the Discovery > Backup Servers tab. For details, see [Uninstalling Management Agents](delete_management_agents.md#one).


