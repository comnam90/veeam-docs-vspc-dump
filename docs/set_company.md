---
title: "Setting Company to Management Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/set_company.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Setting Company to Management Agents


In Veeam Service Provider Console, you can set companies and cloud tenants for discovered computers with installed management agents that have the Unverified status. When you set a company and a cloud tenant to a discovered computer, the management agent on this computer reconnects to Veeam Service Provider Console with the selected company and tenant settings.

Note that if you delete an unverified agent connection, the agent will be removed from Veeam Service Provider Console. To connect this agent, you will have to reinstall it manually.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Setting Company to Management Agents

To set a company and a cloud tenant to Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary management agents in the list.
4. At the top of the list, click Management Agent and choose Set Company.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Set Company.

1. In the Set Company window, select the client company and cloud tenant that you want to set for the management agent and click Apply.


