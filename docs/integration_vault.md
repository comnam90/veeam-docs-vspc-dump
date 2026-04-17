---
title: "Integration with Veeam Data Cloud Vault"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_vault.html"
last_updated: "4/17/2026"
product_version: "9.2.0.33215"
---

# Integration with Veeam Data Cloud Vault


Veeam Service Provider Console offers integration with Veeam Data Cloud Vault. Integration allows you to create and manage storage vaults without accessing Veeam Data Cloud portal.

Integration offers the following capabilities:

* Bulk creation of Veeam Data Cloud Vault tenants. You can create Veeam Data Cloud Vault tenants and storage vaults for multiple Veeam Service Provider Console companies simultaneously.
* Veeam Data Cloud vaults management. You can configure additional storage vaults and assign the managed vaults to Veeam Backup & Replication servers.
* Backup repositories creation. You can create new repositories on managed Veeam Backup & Replication servers using the assigned storage vaults.

This solution is intended for service providers who:

* Use Veeam Service Provider Console to manage and monitor license usage data.
* Manage client companies who want to store their data in the cloud.
* Use Veeam Data Cloud Vault to store and protect data.

Before You Begin

To provide Veeam Data Cloud Vault services to client companies, you must create a customer and request a subscription for your Service Provider company in Veeam Data Cloud. For details, see sections [Creating Customers](https://helpcenter.veeam.com/docs/vdc/provider/sp_customers_create.html) and [Requesting Subscriptions](https://helpcenter.veeam.com/docs/vdc/provider/sp_subscriptions_request.html) in the Veeam Data Cloud Guide for Service Providers.

This section assumes that you have a good understanding of Veeam Data Cloud Vault.

|  |
| --- |
| Note: |
| Veeam Data Cloud Vault integration is available for Veeam Backup & Replication version 13 (build #13.0.1.2067) or later. |

In This Section

* [Enabling Veeam Data Cloud Vault Integration](vault_enable_integration.md)
* [Managing Veeam Data Cloud Vault Tenants](vault_tenants.md)
* [Managing Storage Vaults](manage_storage_vaults.md)
* [Managing Backup Repositories](vault_backup_repositories.md)


