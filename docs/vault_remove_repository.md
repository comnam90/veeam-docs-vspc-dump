---
title: "Removing Backup Repositories"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_remove_repository.html"
last_updated: "3/2/2026"
product_version: "9.2.0.33215"
---

# Removing Backup Repositories


If you no longer use a backup repository, you can remove this repository. Note that you cannot remove a repository that is used as a target repository for configured backup jobs.

To remove a backup repository:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Backup Servers.
5. Select the necessary server in the list and click a link in the Vault Repositories column.

To display only backup servers with assigned repositories, click Filter, in the Vault repositories section click Repositories assigned, and click Apply.

1. In the Repositories window, select the necessary repository and click Remove.
2. In the confirmation window, click Yes.


