---
title: "Setting Cloud Tenant to Management Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/set_cloud_tenant.html"
last_updated: "6/10/2025"
product_version: "9.1.0.30636"
---

# Setting Cloud Tenant to Management Agents


In Veeam Service Provider Console, you can set cloud tenants for discovered computers with installed management agents that belong to a client company with allocated cloud resources. When you set a cloud tenant to a discovered computer, the management agent on this computer reconnects to Veeam Service Provider Console with the selected cloud tenant settings.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Setting Cloud Tenant to Management Agents

To set a cloud tenant to Veeam Service Provider Console management agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary management agents in the list.
4. At the top of the list, click Management Agent and choose Set Tenant.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Set Tenant.

1. In the Set Tenant window, select the cloud tenant which you want to set for the management agent and click Apply.


