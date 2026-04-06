---
title: "Enabling Veeam Backup for Microsoft 365 Integration"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_enable_integration.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Enabling Veeam Backup for Microsoft 365 Integration


To allow Veeam Service Provider Console to synchronize data between companies and Veeam Backup for Microsoft 365 organizations, you must enable the integration feature.

To enable integration features:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the Integration Features section, set the Company Mapping toggle to On.

For details on integration features, see [Integration Features](integration_vbo.md#features).

Disabling Veeam Backup for Microsoft 365 Integration

If you want to hide the Companies tab from the menu on the left, you can disable the Company Mapping integration feature. Note that already collected license usage data will not be removed from license usage reports and configured company mapping will not be affected. If you no longer want to include Veeam Backup for Microsoft 365 organizations license usage in Veeam Service Provider Console companies license usage, you must remove company mapping. For details, see [Removing Mapping](vbo_remove_mapping.md).

To disable integration features:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the Integration Features section, set the Company Mapping toggle to Off.


