---
title: "Managing Read-Only Access Mode"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_storage_read_only.html"
last_updated: "4/21/2026"
product_version: "9.2.0.33215"
---

# Managing Read-Only Access Mode


If a company exceeds the hard quota configured for a storage vault, this vault becomes read-only. In this case, all jobs targeted to this vault will fail automatically. After you increase the storage quota, you must disable the read-only access mode manually.

Disabling Read-Only Access Mode

To disable read-only access mode for a storage vault:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Veeam Data Cloud.
5. Navigate to the Storage Vaults tab.
6. From the list of storage vaults, select the necessary vault.

To display only vaults with enabled read-only mode, click Filter, in the Mode section, select Read-Only and click Apply.

1. At the top of the list, click Set Read-Write.
2. In the confirmation window, click Yes.

Enabling Read-Only Access Mode

To enable read-only access mode manually:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Veeam Data Cloud.
5. Navigate to the Storage Vaults tab.
6. From the list of storage vaults, select the necessary vault.

To display only vaults with disabled read-only mode, click Filter, in the Mode section, select Read-Write and click Apply.

1. At the top of the list, click Set Read-Only.
2. In the confirmation window, click Yes.


