---
title: "Disabling and Enabling API Keys"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_api_key.html"
last_updated: "2/27/2026"
product_version: "9.2.0.33215"
---

# Disabling and Enabling API Keys


You can enable and disable created API keys and API keys created by managed companies and resellers.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Disabling API Keys

To temporarily prevent connection to third party solutions, you can disable an API key. After you disable an API key, you (or reseller that created the API key) cannot use this key to configure new integrations and Veeam Service Provider Console breaks all connections made with the disabled key.

To disable an API key:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Access Management and navigate to the REST API Keys tab.
3. Select the necessary API key and click Disable at the top of the list.

Alternatively, you can right-click the necessary API key and choose Disable.

1. In the Disable Key window, click Yes.

Enabling API Keys

To enable an API key:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Access Management and navigate to the REST API Keys tab.
3. Select the necessary API key and click Enable at the top of the list.

Alternatively, you can right-click the necessary API key and choose Enable.

|  |
| --- |
| Note: |
| Resellers cannot disable or enable API keys using Veeam Service Provider Console Reseller Portal. If a reseller needs to enable an API key, you will have to enable the key for the reseller. |


