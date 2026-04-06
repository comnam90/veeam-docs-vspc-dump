---
title: "Accepting and Rejecting Management Agent Connections"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/accept_reject_connections.html"
last_updated: "8/7/2025"
product_version: "9.1.0.30636"
---

# Accepting and Rejecting Management Agent Connections


In Veeam Service Provider Console, you can accept and reject connections from Veeam Service Provider Console management agents.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Accepting Management Agent Connections

You normally need to accept connections manually if auto deployment settings are configured not to accept connections from new Veeam Service Provider Console management agents. In this case, although on a client or hosted computer you have configured a management agent to connect to Veeam Service Provider Console, in the Administrator Portal this agent will be displayed as Rejected. To work with a discovered computer in Veeam Service Provider Console, you will need to manually accept a connection from the management agent.

For details on auto deployment settings, see [Configuring Auto Deployment Settings](automate_discovery_installation.md#auto).

To manually accept connections from Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Click Filter. In the Connection status section, select the Rejected check box only. Click Apply.

The list of discovered computers will display management agents that are not yet registered with Veeam Service Provider Console as active agents.

1. Select the necessary management agents in the list.
2. At the top of the list, click Management Agent and choose Accept Connection.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Accept Connection.

Rejecting Management Agent Connections

You can reject connections from Veeam Service Provider Console management agents. Veeam Service Provider Console does not collect data from rejected management agents, and you will not be able to perform most management operations on rejected agents. All SLA statistics for rejected management agents will be permanently deleted from Veeam Service Provider Console.

To manually reject connections from Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Click Filter. In the Connection status section, select the Online and Inaccessible check boxes only. Click Apply.

The list of discovered computers will display management agents that have been registered with Veeam Service Provider Console as active agents.

1. Select the necessary management agents in the list.

1. At the top of the list, click Management Agent and choose Reject Connection.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Reject Connection.

The status of the management agent will be changed to Rejected.

Accepting Management Agent Connections on Veeam Cloud Connect Servers

To manually accept connections from Veeam Service Provider Console management agents deployed on Veeam Cloud Connect servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary Veeam Cloud Connect server from the list.
6. At the top of the list, click Server Management and select Accept Connection.

Alternatively, you can right-click the necessary server, choose Server Management and select Accept Connection.


