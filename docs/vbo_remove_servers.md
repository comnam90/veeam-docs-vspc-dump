---
title: "Removing Veeam Backup for Microsoft 365 Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_remove_servers.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Veeam Backup for Microsoft 365 Servers


You can uninstall Veeam Service Provider Console management agents from hosted Veeam Backup for Microsoft 365 servers.

|  |
| --- |
| Note: |
| You cannot uninstall management agents in the following cases:   * The management agent has the Rejected status. For details on management agent connection status, see [Accepting and Rejecting Management Agent Connections](accept_reject_connections.md). * The management agent is installed on a computer on which Veeam Cloud Connect is deployed. |

Removing Veeam Backup for Microsoft 365 Servers

To remove Veeam Service Provider Console management agent from hosted Veeam Backup for Microsoft 365 server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary servers in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error, Info).

1. At the top of list, click Remove.
2. In the confirmation window, click Yes.

To remove management agents from client Veeam Backup for Microsoft 365 servers, go to the Discovery > Microsoft 365 Backup Servers tab. For details, see [Uninstalling Management Agents](delete_management_agents.md#vbo).


