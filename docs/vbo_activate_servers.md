---
title: "Activating Veeam Backup for Microsoft 365 Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_activate_servers.html"
last_updated: "4/23/2026"
product_version: "9.2.0.33215"
---

# Activating Veeam Backup for Microsoft 365 Servers


If connected Veeam Backup for Microsoft 365 server does not have Veeam Backup for Microsoft 365 REST API installed and activated, you will not be able to manage the connected server. Veeam Service Provider Console plugin allows you to install the required components and activate Veeam Backup for Microsoft 365 REST API without having to access Veeam Backup for Microsoft 365 console. For details on how to activate client Veeam Backup for Microsoft 365 servers, see [Activating Veeam Backup for Microsoft 365 Servers in Veeam Service Provider Console](activate_vbo_servers.md).

Activating Hosted Veeam Backup for Microsoft 365 Servers

To activate hosted Veeam Backup for Microsoft 365 servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary server in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error, Info).

1. At the top of list, click Activate.
2. In the confirmation window, click Yes.


