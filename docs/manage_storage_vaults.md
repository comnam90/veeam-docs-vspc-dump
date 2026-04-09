---
title: "Managing Storage Vaults"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_storage_vaults.html"
last_updated: "3/18/2026"
product_version: "9.2.0.33215"
---

# Managing Storage Vaults


In Veeam Service Provider Console plugin, you can create additional storage vaults for managed Vault tenants, modify existing storage vaults, and assign vaults to Veeam Backup & Replication servers.

Note that when you create a new Vault tenant for a Veeam Service Provider Console company, a storage vault for this tenant will be created automatically.

|  |
| --- |
| Note: |
| * In Veeam Service Provider Console plugin, you can create and manage storage vaults only for tenants with Microsoft Azure edition subscriptions. * If you plan to allocate resources of a hosted Veeam Backup & Replication server to multiple client companies, you must create a separate storage vault or a separate repository for each company. Otherwise, Veeam Service Provider Console will not be able to display the repository storage usage for individual companies. |

Prerequisites

Before working with storage vaults:

* Make sure you have created a customer and requested a subscription for your Service Provider company in Veeam Data Cloud. For details, see sections [Creating Customers](https://helpcenter.veeam.com/docs/vdc/provider/sp_customers_create.html) and [Requesting Subscriptions](https://helpcenter.veeam.com/docs/vdc/provider/sp_subscriptions_request.html) in the Veeam Data Cloud Guide for Service Providers.
* Configure Veeam Data Cloud Vault Plugin connection. For details, see [Enabling Veeam Data Cloud Vault Integration](vault_enable_integration.md).

In This Section

* [Creating Storage Vaults](vault_create_storage.md)
* [Assigning Storage Vaults](vault_assign_storage.md)
* [Modifying Storage Vaults](vault_edit_storage.md)
* [Locking Storage Vaults](vault_storage_read_only.md)
* [Removing Storage Vaults](vault_remove_storage.md)


