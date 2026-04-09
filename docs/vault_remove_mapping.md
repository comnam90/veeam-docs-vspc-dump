---
title: "Removing Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_remove_mapping.html"
last_updated: "3/17/2026"
product_version: "9.2.0.33215"
---

# Removing Mapping


If you do not want to assign Veeam Data Cloud Vaults to a managed company, you can remove mapping. If you remove mapping, vaults that were previously assigned to Veeam Backup & Replication servers of this company will not be affected.

To remove mapping:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Veeam Data Cloud.
5. Navigate to the Tenants tab.
6. From the list of tenants, select one or more mapped tenants.

To narrow down the list of tenants, you can search tenants by name, Veeam Service Provider Console company and subscription or apply the following filters:

* Status — limit the list of tenants by tenant status (Healthy, Warning, Error, Information, All).
* Subscription type — limit the list of tenants by subscription type.
* Mapping status — limit the list of tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Remove Mapping.
2. In the Remove Mapping window, click Yes.


