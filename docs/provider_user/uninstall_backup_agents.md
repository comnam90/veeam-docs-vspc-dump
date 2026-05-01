---
title: "Uninstalling Veeam Backup Agents"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/uninstall_backup_agents.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Uninstalling Veeam Backup Agents


You can uninstall Veeam backup agents on managed computers. During the uninstall procedure, both Veeam backup agents and Veeam Service Provider Console management agents are removed from remote machines. After you uninstall Veeam backup agents, the number of used and total licenses in the Veeam Service Provider Console license pool will be updated.

|  |
| --- |
| Note: |
| If a managed computer runs another Veeam product together with Veeam backup agent, a Veeam Service Provider Console management agent is not removed as part of the uninstall procedure. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Uninstalling Veeam Backup Agents

To uninstall Veeam backup agents from one or more managed computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Select the necessary Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and choose Delete.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Delete.

1. In the displayed window, click Yes to confirm removal.


