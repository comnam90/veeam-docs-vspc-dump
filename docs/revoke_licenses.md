---
title: "Revoking Veeam Backup Agent Licenses"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/revoke_licenses.html"
last_updated: "6/19/2025"
product_version: "9.1.0.30636"
---

# Revoking Veeam Backup Agent Licenses


Each Veeam backup agent that is managed in Veeam Service Provider Console consumes a number of instances from the Veeam Service Provider Console license pool. The license status of a managed Veeam backup agent is set to Licensed.

When Veeam backup agent becomes unmanaged, instances are revoked from this Veeam backup agent, and returned to the Veeam Service Provider Console license pool. For example, this happens when you switch Veeam backup agent to the Unmanaged mode (Free mode). For details, see [Switching Veeam Backup Agents to Unmanaged Mode](activate_backup_agents.md#unman).

You can also manually revoke instances from one or more Veeam backup agents. When instances are revoked, a Veeam Service Provider Console management agent is removed from a managed computer, and Veeam backup agent is switched to the Unmanaged mode (Free mode).

|  |
| --- |
| Note: |
| If a managed computer runs Veeam Backup & Replication or Veeam Backup Enterprise Manager together with Veeam backup agent, Veeam Service Provider Console management agent is not removed. |

To revoke Veeam backup agent instances:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. Open the Veeam Agents tab.
4. Select the necessary Veeam backup agents in the list.

To narrow down the list of Veeam backup agents, you can use the following filters:

* Reseller — search the list of Veeam backup agents servers by name of a reseller who manages the company.
* Company — search Veeam backup agents by company name.
* Hostname — search Veeam backup agents by host name.
* Guest OS — limit the list of Veeam backup agents by OS type (Windows, Linux, macOS).
* License status — limit the list of Veeam backup agents by license status (Licensed, New, License exceeded).
* Operation mode — limit the list of Veeam backup agents by operation mode (Server, Workstation).
* Platform — limit the list of Veeam backup agents by platform type (Physical, Virtual, Cloud).
* Connection status — limit the list of Veeam backup agents by connection status (Online, Offline).

1. At the top of the list, click Revoke License Key.

Alternatively, you can right-click the necessary agent and choose Revoke License Key.

1. In the displayed window, click Yes to confirm the operation.


