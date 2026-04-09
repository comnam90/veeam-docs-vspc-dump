---
title: "Configuring Vaults Assignment"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vault_assign_storage.html"
last_updated: "3/17/2026"
product_version: "9.2.0.33215"
---

# Configuring Vaults Assignment


To add a Veeam Data Cloud storage vault to your backup infrastructure, you must assign the vault to a Veeam Backup & Replication server. When you assign a vault, the backup server will be automatically registered in Veeam Data Cloud.

Assigning Storage Vaults

To assign a storage vault to a Veeam Backup & Replication server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Backup Servers.
5. Select the necessary server in the list.

To narrow down the list of servers, you can apply the following filters:

* Company — search servers by the name of Veeam Service Provider Console company.
* Backup Server — search servers by name.
* Connection status — limit the list of servers by status of Veeam Data Cloud registration (Not registered, Registered, Warning, Error).
* Vaults — limit the list of servers by vaults assignment (No vaults, Vaults assigned).
* Vault repositories — limit the list of servers by repository assignment (No repositories, Repositories assigned).
* Application status — limit the list of servers by status of the application running on a computer (Healthy, Inaccessible).
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error).
* Vault compatibility — limit the list of servers by compatibility with Veeam Data Cloud Vault (Compatible, Not compatible).
* Guest OS — limit the list of servers by guest OS (Windows, Linux).

1. At the top of the list, click Vault Management.
2. In the Vault Management window, click Assign Vault.

Plugin will display a list of all storage vaults available for the company to which the Veeam Backup & Replication server belongs.

1. From the list of storage vaults, select the necessary vault and click Assign.

Unassigning Storage Vaults

If you remove the assigned vault, the Veeam Backup & Replication server will remain registered in Veeam Data Cloud but you will not be able to create new repositories for the unassigned vault.

To remove storage vault assignment:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Vault plugin tile.
4. In the menu on the left, click Backup Servers.
5. Select the necessary server in the list.

To narrow down the list of servers, you can apply the following filters:

* Company — search servers by the name of Veeam Service Provider Console company.
* Backup Server — search servers by name.
* Connection status — limit the list of servers by status of Veeam Data Cloud registration (Not registered, Registered, Warning, Error).
* Vaults — limit the list of servers by vaults assignment (No vaults, Vaults assigned).
* Vault repositories — limit the list of servers by repository assignment (No repositories, Repositories assigned).
* Application status — limit the list of servers by status of the application running on a computer (Healthy, Inaccessible).
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error).
* Vault compatibility — limit the list of servers by compatibility with Veeam Data Cloud Vault (Compatible, Not compatible).
* Guest OS — limit the list of servers by guest OS (Windows, Linux).

1. At the top of the list, click Vault Management.

Alternatively, you can click a link in the Vaults column.

1. In the Vault Management window, select the necessary vault and click Unassign Vault.
2. In the confirmation window, click Yes.


