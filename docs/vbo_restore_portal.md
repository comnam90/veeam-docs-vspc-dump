---
title: "Accessing Veeam Backup for Microsoft 365 Restore Portal"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_restore_portal.html"
last_updated: "8/21/2025"
product_version: "9.1.0.30636"
---

# Accessing Veeam Backup for Microsoft 365 Restore Portal


To restore data of backed up Microsoft 365 organizations, you can use Veeam Backup for Microsoft 365 Restore Portal. For details on working with restore portal, see section [Data Restore Using Restore Portal](https://helpcenter.veeam.com/docs/vbo365/guide/ssp_restore.html) of the Veeam Backup for Microsoft 365 User Guide.

To access Veeam Backup for Microsoft 365 restore portal from Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Protected Data.
2. Open the Microsoft 365 Objects tab.
3. Select the necessary object.

To narrow down the list of objects, you can apply the following filters:

* Object — search objects by name.
* Type — limit the list of objects by type (User, Group, Teams, Site).

* Site/Reseller/Company/Location — limit the list of objects by Veeam Cloud Connect site, reseller, company and location to which jobs belong. To limit the list of jobs by site, reseller, company and location, use filters at the top left corner of the Veeam Service Provider Console window.

The Site filter is available only if you have connected more than one Veeam Cloud Connect server to Veeam Service Provider Console.

1. At the top of the list, click Restore Portal.

Alternatively, you can right-click the necessary object and choose Restore Portal.

Veeam Service Provider Console will open Veeam Backup for Microsoft 365 restore portal in a new window.


