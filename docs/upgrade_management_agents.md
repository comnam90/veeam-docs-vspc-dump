---
title: "Upgrading Management Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/upgrade_management_agents.html"
last_updated: "2/16/2026"
product_version: "9.1.0.30636"
---

# Upgrading Management Agents


Veeam Service Provider Console and its management agents must run the same software version. Otherwise, they cannot properly communicate with each other. When you upgrade or migrate to a new version of Veeam Service Provider Console, all management agents will upgrade automatically after you log in to Veeam Service Provider Console web portal. If necessary, you can upgrade the management agents manually.

Note that when you install an update (a patch or private fix), all management agents will update automatically.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Upgrading Management Agents

To upgrade Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Click Filter. In the Management agent version section, select the Out-of-date check box only. Click Apply.

The list of discovered computers will display management agents whose software version does not coincide with the Veeam Service Provider Console version.

1. Select the necessary management agents from the list.
2. At the top of the list, click Management Agent and choose Upgrade.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Upgrade.

1. In the displayed window, check the result of the upgrade and click OK.

Upgrading Management Agents on Veeam Cloud Connect Servers

To upgrade Veeam Service Provider Console management agents installed on Veeam Cloud Connect servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary Veeam Cloud Connect server from the list.

Servers with management agents whose software version does not coincide with the Veeam Service Provider Console version will have Out-of-date value in the Agent Version column.

1. At the top of the list, click Server Management and select Upgrade Management Agent.

Alternatively, you can right-click the necessary server, choose Server Management and select Upgrade Management Agent.

1. In the displayed window, check the result of the upgrade and click OK.


