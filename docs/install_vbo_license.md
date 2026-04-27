---
title: "Installing Veeam Backup for Microsoft 365 License"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/install_vbo_license.html"
last_updated: "4/23/2026"
product_version: "9.2.0.33215"
---

# Installing Veeam Backup for Microsoft 365 License


You can install a license on a managed Veeam Backup for Microsoft 365 server.

To install a license:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the menu on the left, click License Information.
3. On the Veeam Backup for Microsoft 365 tab, select Veeam Backup for Microsoft 365 servers on which you want to install license.

To narrow down the list of Veeam Backup for Microsoft 365 servers, you can apply the following filters:

* Reseller — search the list of Veeam Backup for Microsoft 365 servers by name of a reseller who manages the server.
* Company — search the list of Veeam Backup for Microsoft 365 servers by name of a company who owns the server.
* Hostname — search the list of Veeam Backup for Microsoft 365 servers by the name of the server.
* License status — limit the list of Veeam Backup for Microsoft 365 servers by status of the installed license (Valid, Warning, Error).
* Type — limit the list of Veeam Backup for Microsoft 365 servers by type of license installed on the server (Community, Rental, Subscription).

1. Do one of the following:

* If you have configured integration with VCSP Pulse, at the top of the list, click Install and select the necessary option:

* To upload license file from your computer, select From local folder and browse to the license file.
* To install license key configured in VCSP Pulse, select From VCSP Pulse. In the Install License window, select the necessary license key and click Install.

For details on Veeam Service Provider Console integration with VCSP Pulse, see [Integration with VCSP Pulse](integration_pulse.md).

* If you have not configured integration with VCSP Pulse, click Install and browse to the license file.

Alternatively, you can right-click the necessary server and choose one of the available options.

After you choose the license file, Veeam Service Provider Console will display the result of the license installation in the License Update Status column.

|  |
| --- |
| Note: |
| It is not recommended to install one VCSP Pulse license in multiple products. If you have selected a license key that is already installed in another product, Veeam Service Provider Console will ask you to copy the license key. If you do not want to copy the license key, you can download the license file and install it manually. Note that in license usage report Veeam Service Provider Console will add up points usage for all servers with the same license ID. Only Veeam Data Platform licenses can be installed in multiple products.  If you have one license key installed on multiple servers, Veeam Service Provider Console will add up points usage for all servers with the same license key. If you want to report points usage for all servers separately, you must install different license keys on these servers. |

Installing License in Veeam Backup for Microsoft 365 Console

You can install a license file directly in Veeam Backup for Microsoft 365. For details on installing a license using the Veeam Backup for Microsoft 365 console, see section [Installing and Updating License](https://helpcenter.veeam.com/docs/vbo365/guide/vbo_installing_license.html) of the Veeam Backup for Microsoft 365 User Guide.


