---
title: "Accessing Veeam Backup for Public Clouds Portals"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_access_ui.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Accessing Veeam Backup for Public Clouds Portals


You can access Veeam Backup for Amazon Web Services, Veeam Backup for Microsoft Azure and Veeam Backup for Google Cloud web portals from Veeam Service Provider Console plugin.

Prerequisites

Before you start working with repositories, make sure that:

* You have approved security certificate for the appliance whose web portal you want to access. For details, see [Verifying Appliances](clouds_verify_certificate.md).
* You have configured guest OS credentials for the appliance whose web portal you want to access. You can configure guest OS accounts credentials as a part of appliance deployment process or by modifying connected appliance settings. For details on creating new guest OS accounts, see [Adding Guest OS Accounts](clouds_guest_accounts.md). For details on modifying appliance settings, see [Modifying Appliances](clouds_edit_appliances.md).

Accessing Veeam Backup for Public Clouds Portal

To access Veeam Backup for Amazon Web Services or Veeam Backup for Microsoft Azure web portal:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.
5. Select the necessary appliance in the list.
6. At the top of the list, click Open Appliance UI.

Veeam Service Provider Console will open the appliance web portal.

Alternatively, you can access Veeam Backup for Public Clouds portals from the Discovery > Cloud Appliances tab. For details, see [Accessing Veeam Backup for Public Clouds Portal](access_vb_cloud_portal.md).

For details on working with Veeam Backup for Veeam Backup for Public Clouds portals, see Veeam Backup for Veeam Backup for Public Clouds User Guides:

* [Veeam Backup for AWS User Guide](https://helpcenter.veeam.com/docs/vbaws/guide/welcome.html)
* [Veeam Backup for Microsoft Azure User Guide](https://helpcenter.veeam.com/docs/vbazure/guide/overview.html)
* [Veeam Backup for Google Cloud User Guide](https://helpcenter.veeam.com/docs/vbgc/guide/welcome.html)


