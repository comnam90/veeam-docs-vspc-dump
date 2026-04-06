---
title: "Updating Veeam Backup for Microsoft 365 License"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/update_vbo_licenses.html"
last_updated: "6/19/2025"
product_version: "9.1.0.30636"
---

# Updating Veeam Backup for Microsoft 365 License


You can update a license on managed Veeam Backup for Microsoft 365 servers.

To update a license:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam Backup for Microsoft 365 tab, select Veeam Backup for Microsoft 365 servers on which you want to update license.

To narrow down the list of Veeam Backup for Microsoft 365 servers, you can apply the following filters:

* Reseller — search the list of Veeam Backup for Microsoft 365 servers by name of a reseller who manages the server.
* Company — search the list of Veeam Backup for Microsoft 365 servers by name of a company who owns the server.
* Hostname — search the list of Veeam Backup for Microsoft 365 servers by the name of the server.
* License status — limit the list of Veeam Backup for Microsoft 365 servers by status of the installed license (Valid, Warning, Error).
* Type — limit the list of Veeam Backup for Microsoft 365 servers by type of license installed on the server (Community, Rental, Subscription, Perpetual).

1. At the top of the list, click Update.

Alternatively, you can right-click the necessary server and choose Update.

Veeam Service Provider Console will instruct the selected Veeam Backup for Microsoft 365 servers to connect to the Veeam License Update Server on the Internet, download a new product license from it (if available), install it, and display the result in the License Update Status column.

Enabling Automatic License Update

You can enable automatic license update on managed Veeam Backup for Microsoft 365 servers.

To enable automatic license update:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam Backup for Microsoft 365 tab, select Veeam Backup for Microsoft 365 servers on which you want to enable automatic license update.

To narrow down the list of Veeam Backup for Microsoft 365 servers, you can apply the following filters:

* Reseller — search the list of Veeam Backup for Microsoft 365 servers by name of a reseller who manages the server.
* Company — search the list of Veeam Backup for Microsoft 365 servers by name of a company who owns the server.
* Hostname — search the list of Veeam Backup for Microsoft 365 servers by the name of the server.
* License Status — limit the list of Veeam Backup for Microsoft 365 servers by status of the installed license (Valid, Warning, Error).
* Type — limit the list of Veeam Backup for Microsoft 365 servers by type of license installed on the server (Community, Rental, Subscription, Perpetual).

1. At the top of the list, switch the License Auto Update toggle to On.

Veeam Service Provider Console will enable automatic license update and activate automatic usage reporting on the selected Veeam Backup for Microsoft 365 servers.

Updating License in Veeam Backup for Microsoft 365 Console

You can update a license file directly in Veeam Backup for Microsoft 365. For details on updating a license using the Veeam Backup for Microsoft 365 console, see section [Installing and Updating License](https://helpcenter.veeam.com/docs/vbo365/guide/vbo_installing_license.html) of the Veeam Backup for Microsoft 365 User Guide.


