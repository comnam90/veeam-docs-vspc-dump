---
title: "Configuring Tenant Management Mode"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/cloud_tenant_management.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Configuring Tenant Management Mode


By default, when you add a Veeam Cloud Connect server, Veeam Service Provider Console restricts performing management operations from the Veeam Backup & Replication console on this server. These operations include managing tenant and subtenant accounts and configuring cloud repositories and replication resources. You can change this setting later in Veeam Service Provider Console web UI.

To change tenant management mode:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. From the Veeam Cloud Connect servers list, select the server on which you want to configure tenant management mode.
6. At the top of the list, click Tenant Management in Cloud Connect and select one of the following options:

* Enable — select this option if you want to allow tenant and cloud resource management in Veeam Service Provider Console and Veeam Backup & Replication console.

* Disable (Recommended) — select this option if you want to disable tenant and cloud resource management in Veeam Backup & Replication console.

1. In the Tenant Management window, click Yes.


