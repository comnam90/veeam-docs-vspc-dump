---
title: "Modifying Storage Vaults"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_edit_storage.html"
last_updated: "3/17/2026"
product_version: "9.2.0.33215"
---

# Modifying Storage Vaults


To modify storage vault settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Veeam Data Cloud.
5. Navigate to the Storage Vaults tab.
6. From the list of storage vaults, select the necessary vault.

To narrow down the list of vaults, you can search vaults by name, Veeam Service Provider Console company and country or apply the following filters:

* Subscription — search vaults by subscription name.
* Status — limit the list of vaults by status (Healthy, Warning, Error, Information, All).
* Subscription type — limit the list of vaults by subscription type.
* Quota enforcement — limit the list of vaults by hard quota enforcement (Enabled, Disabled).
* Mode — limit the list of vaults by access mode (Read-Write, Read-Only).

1. At the top of the list, click Edit.

Veeam Service Provider Console will open the Edit Storage Vault wizard.

1. Modify quota settings for the storage vault as described in [Creating Storage Vaults](vault_create_storage.md#quota).
2. Save changes.


