---
title: "Updating Veeam ONE License"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/update_one_licenses.html"
last_updated: "8/31/2025"
product_version: "9.1.0.30636"
---

# Updating Veeam ONE License


You can update a license on managed Veeam ONE servers.

To update a license:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam ONE tab, select Veeam ONE servers on which you want to update license.

To narrow down the list of Veeam ONE servers, you can apply the following filters:

* Reseller — search the list of Veeam ONE servers by name of a reseller who manages the server.
* Company — search the list of Veeam ONE servers by name of a company who owns the server.
* Hostname — search the list of Veeam ONE servers by the name of the server.
* License status — limit the list of Veeam ONE servers by status of the installed license (Valid, Warning, Error).
* Type — limit the list of Veeam ONE servers by type of license installed on the server (Community, Rental, Subscription, Perpetual).

1. At the top of the list, click Update.

Alternatively, you can right-click the necessary server and choose Update.

Veeam Service Provider Console will instruct the selected Veeam ONE servers to connect to the Veeam License Update Server on the Internet, download a new product license from it (if available), install it, and display the result in the License Update Status column.

Enabling Automatic License Update

You can enable automatic license update on managed Veeam ONE servers.

To enable automatic license update:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam ONE tab, select Veeam ONE servers on which you want to enable automatic license update.

To narrow down the list of Veeam ONE servers, you can apply the following filters:

* Reseller — search the list of Veeam ONE servers by name of a reseller who manages the server.
* Company — search the list of Veeam ONE servers by name of a company who owns the server.
* Hostname — search the list of Veeam ONE servers by the name of the server.
* License Status — limit the list of Veeam ONE servers by status of the installed license (Valid, Warning, Error).
* Type — limit the list of Veeam ONE servers by type of license installed on the server (Community, Rental, Subscription, Perpetual).

1. At the top of the list, switch the License Auto Update toggle to On.

Veeam Service Provider Console will enable automatic license update and activate automatic usage reporting on the selected Veeam ONE servers.

Updating License in Veeam ONE Client

You can update a license file directly in Veeam ONE. For details on updating a license using the Veeam ONE Client, see section [Updating Licenses](https://helpcenter.veeam.com/docs/one/userguide/update_license.html?ver=13) of the Veeam ONE User Guide.


