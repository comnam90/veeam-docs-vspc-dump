---
title: "Integration with Custom Plugins"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_custom.html"
last_updated: "10/27/2025"
product_version: "9.1.0.30636"
---

# Integration with Custom Plugins


Integration with custom plugins allows you to use Veeam Service Provider Console plugins developed to tailor Veeam Service Provider Console portal according to your business needs.

Uploading Custom Plugins

To upload a custom plugin to Veeam Service Provider Console:

1. Develop a custom plugin as described in Veeam Service Provider Console Plugin Template Guide.

For Veeam Service Provider Console Plugin Template package and documentation, see [this Veeam KB article](https://www.veeam.com/kb4311).

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. At the top of the plugin list, click Upload Custom Plugin.
4. In the Upload Custom Plugin window, click Browse and select a NUPKG file with your custom plugin.
5. To enable the plugin for all managed companies and resellers, select the Enable the plugin to all managed organizations, including newly added check box.
6. Click Upload.

After the file upload is complete, you will see your custom plugin tile in the plugin library. If you have configured internal UI for the plugin, you can access the created pages in Veeam Service Provider Console portal.

Disabling, Enabling and Removing Custom Plugins

To change settings for a custom plugin:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. At the top right corner of the custom plugin tile, click the gear icon.

Veeam Service Provider Console will open the plugin settings window.

1. On the Plugin Settings tab, click Disable to disable the plugin, Enable to enable a disabled plugin, or Remove to delete the plugin.

Modifying Custom Plugin REST API Key

To change REST API key for a custom plugin:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. At the top right corner of the custom plugin tile, click the gear icon.

Veeam Service Provider Console will open the plugin settings window.

1. On the Plugin Settings tab, click Change REST API Key.
2. In the Change REST API Key window, specify a new REST API key and click Apply.

Changing Custom Plugin Scope

To change assignment scope for a custom plugin:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. At the top right corner of the custom plugin tile, click the gear icon.

Veeam Service Provider Console will open the plugin settings window.

1. On the Companies tab, select the necessary company in the list and click Enable to enable the plugin for the company, or Disable to disable the plugin for the company.

To enable the plugin for all companies and resellers, switch the toggle at the top of the company list to Blacklist and disable the plugin for specific companies manually.

To disable the plugin for all companies and resellers, switch the toggle at the top of the company list to Whitelist and enable the plugin for specific companies manually.

1. Click Close.


