---
title: "Activating Veeam Backup for Microsoft 365 Servers in Veeam Service Provider Console"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/activate_vbo_servers.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Activating Veeam Backup for Microsoft 365 Servers in Veeam Service Provider Console


If a connected Veeam Backup for Microsoft 365 server does not have Veeam Backup for Microsoft 365 REST API or PowerShell installed and activated, you will not be able to manage the connected server. Veeam Service Provider Console allows you to install the required components and activate Veeam Backup for Microsoft 365 REST API and PowerShell without having to access the Veeam Backup for Microsoft 365 console. For details on how to install Veeam Service Provider Console management agents on  Veeam Backup for Microsoft 365 servers, see [Managing Veeam Service Provider Console Agents](manage_vac_agents.md#agents).

Activating Veeam Backup for Microsoft 365 Servers

To activate Veeam Backup for Microsoft 365 servers in Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Microsoft 365 Backup Servers tab.

Veeam Service Provider Console will display a list of all managed Veeam Backup for Microsoft 365 servers.

1. Select the necessary server in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Application status — limit the list of servers by application status (Running, Not running).
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error).
* Management agent version — limit the list of servers by management agent version (Up-to-date, Out-of-date, Patch available, N/A).

* Location — limit the list of servers by location to which servers belong. To limit the list of servers by  location, use filter at the top left corner of the Veeam Service Provider Console window.

1. At the top of the list, click Activate.

Alternatively, you can right-click the necessary server and choose Activate.

1. In the confirmation window, click Yes.


