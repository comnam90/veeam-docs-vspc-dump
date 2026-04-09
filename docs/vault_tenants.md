---
title: "Managing Vault Tenants"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_tenants.html"
last_updated: "3/17/2026"
product_version: "9.2.0.33215"
---

# Managing Vault Tenants


In Veeam Data Cloud, Vault tenants are used as a method to organize storage vaults, associate vaults with subscriptions, and manage access to storage vaults.

Vault tenants can manage storage vaults under the assigned subscription. One tenant can be linked to only one subscription, but a single subscription can be assigned to multiple tenants.

|  |
| --- |
| Note: |
| In Veeam Service Provider Console plugin, you can create and manage only tenants with Microsoft Azure edition subscriptions. |

Prerequisites

Before configuring integration of managed companies:

* Make sure you have created a customer and requested a subscription for your Service Provider company in Veeam Data Cloud. For details, see sections [Creating Customers](https://helpcenter.veeam.com/docs/vdc/provider/sp_customers_create.html) and [Requesting Subscriptions](https://helpcenter.veeam.com/docs/vdc/provider/sp_subscriptions_request.html) in the Veeam Data Cloud Guide for Service Providers.
* Configure Veeam Data Cloud Vault Plugin connection. For details, see [Enabling Veeam Data Cloud Vault Integration](vault_enable_integration.md).

Configuring Tenants Integration

To configure integration between companies in Veeam Service Provider Console and Vault tenants in Veeam Data Cloud, you can do either of the following:

* [Create new Veeam Data Cloud Vault tenants](vault_create_tenants.md).

Use this method if you want to create Veeam Data Cloud Vault tenants and storage vaults for company accounts that you already manage in Veeam Service Provider Console.

* [Configure mapping between Veeam Data Cloud Vault tenants and Veeam Service Provider Console companies](vault_tenant_mapping.md).

Use this method if you want to map existing Veeam Data Cloud Vault tenants to company accounts registered in Veeam Service Provider Console.


