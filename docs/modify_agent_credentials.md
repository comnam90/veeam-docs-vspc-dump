---
title: "Modifying Management Agent Credentials"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_agent_credentials.html"
last_updated: "9/1/2025"
product_version: "9.1.0.30636"
---

# Modifying Management Agent Credentials


If you plan to deploy Veeam Backup & Replication on a discovered computer, you need to specify service account credentials. You can set the account credentials beforehand and use them during Veeam Backup & Replication installation and upgrade.

|  |
| --- |
| Note: |
| You can modify management agent credentials only for Windows Veeam Backup & Replication servers. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Modifying Management Agent Credentials

To set new account credentials for a management agent:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary management agent in the list.
4. At the top of the list, click Management Agent and choose Set Credentials.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Set Credentials.

1. In the Set Credentials window, specify a user name and password for a new connection account.

If the agent already has configured credentials, click Change Credentials and specify new credentials.

The account must have local administrator privileges on the remote computer.

1. Click Save.

Deleting Management Agent Credentials

To delete credentials from management agent settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary management agent in the list.
4. At the top of the list, click Management Agent and choose Set Credentials.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Set Credentials.

1. In the Set Credentials window, click Delete Credentials.
2. In the confirmation window, click Yes.


