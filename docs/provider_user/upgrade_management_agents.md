---
title: "Upgrading Management Agents"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/upgrade_management_agents.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Upgrading Management Agents


Veeam Service Provider Console and its management agents must run the same software version. Otherwise, they cannot properly communicate with each other. When you upgrade or migrate to a new version of Veeam Service Provider Console, all management agents will upgrade automatically after you log in to Veeam Service Provider Console web portal. If necessary, you can upgrade the management agents manually.

Note that when you install an update (a patch or private fix), all management agents will update automatically.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Upgrading Management Agents

To upgrade Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. Click Filter. In the Management agent version section, select the Out-of-date check box only. Click Apply.

The list of discovered computers will display management agents whose software version does not coincide with the Veeam Service Provider Console version.

1. Select the necessary management agents from the list.
2. At the top of the list, click Management Agent and choose Upgrade.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Upgrade.

1. In the displayed window, check the result of the upgrade and click OK.


