---
title: "Updating Veeam Cloud Connect License"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/update_cc_licenses.html"
last_updated: "11/10/2025"
product_version: "9.1.0.30636"
---

# Updating Veeam Cloud Connect License


In Veeam Service Provider Console, you can update license on Veeam Cloud Connect servers.

To update a license on Veeam Cloud Connect servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam Cloud Connect tab, select Veeam Cloud Connect servers on which you want to update license.

To narrow down the list of Veeam Cloud Connect servers, you can apply the following filters:

* Hostname — search the list of Veeam Cloud Connect servers by the name of the server.
* License status — limit the list of Veeam Cloud Connect servers by status of the installed license (Valid, Warning, Error).

1. At the top of the list, click Update.

Alternatively, you can right-click the necessary server and choose Update.

Veeam Service Provider Console will instruct the selected Veeam Cloud Connect servers to connect to the Veeam License Update Server on the Internet, download a new product license from it (if available), install it, and display the result in the License Update Status column.

Enabling Automatic License Update

You can enable automatic license update on managed Veeam Cloud Connect servers.

To enable automatic license update:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam Cloud Connect tab, select Veeam Cloud Connect servers on which you want to enable automatic license update.

To narrow down the list of Veeam Cloud Connect servers, you can apply the following filters:

* Hostname — search the list of Veeam Cloud Connect servers by the name of the server.
* License Status — limit the list of Veeam Cloud Connect servers by status of the installed license (Valid, Warning, Error).

1. At the top of the list, switch the License Auto Update toggle to On.

Veeam Service Provider Console will enable automatic license update and activate automatic usage reporting on the selected Veeam Cloud Connect servers.

Updating License in Veeam Backup & Replication Console

You can update a license file directly in Veeam Backup & Replication. For details on updating Veeam Cloud Connect license, see section [Updating License](https://helpcenter.veeam.com/docs/backup/cloud/sp_update_license.html) of the Veeam Cloud Connect Guide.


