---
title: "Managing Backup Repositories"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_backup_repositories.html"
last_updated: "3/18/2026"
product_version: "9.2.0.33215"
---

# Managing Backup Repositories


In Veeam Service Provider Console plugin, you can create backup repositories using the assigned storage vaults.

|  |
| --- |
| Note: |
| If you plan to allocate resources of a hosted Veeam Backup & Replication server to multiple client companies, you must create a separate storage vault or a separate repository for each company. Otherwise, Veeam Service Provider Console will not be able to display the repository storage usage for individual companies. |

Prerequisites

Before working with backup repositories:

* Make sure you have created a customer and requested a subscription for your Service Provider company in Veeam Data Cloud. For details, see sections [Creating Customers](https://helpcenter.veeam.com/docs/vdc/provider/sp_customers_create.html) and [Requesting Subscriptions](https://helpcenter.veeam.com/docs/vdc/provider/sp_subscriptions_request.html) in the Veeam Data Cloud Guide for Service Providers.
* Configure Veeam Data Cloud Vault Plugin connection. For details, see [Enabling Veeam Data Cloud Vault Integration](vault_enable_integration.md).
* Assign a storage vault to a Veeam Backup & Replication server. For details, see [Configuring Vaults Assignment](vault_assign_storage.md).

In This Section

* [Creating Backup Repositories](vault_create_repository.md)
* [Modifying Backup Repositories](vault_edit_repository.md)
* [Removing Backup Repositories](vault_remove_repository.md)


