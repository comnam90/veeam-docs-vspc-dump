---
title: "Removing Accounts"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/clouds_remove_accounts.html"
last_updated: "6/12/2024"
product_version: "9.1.0.30636"
---

# Removing Accounts


To remove accounts:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Accounts.
5. Open the necessary tab:

* Public Cloud — select this tab to view Amazon Web Services, Microsoft Azure and Google Cloud accounts.
* Databases — select this tab to view database administrator accounts.

1. Select the necessary account in the list.

To narrow down the list of accounts, you can apply the following filters:

* Account Name — search the list of appliances by server name.

* [For databases accounts] Backup Appliance — search the list of account by appliance name.
* Platform — limit the list of appliances by platform (All, Amazon Web Services, Microsoft Azure, Google Cloud).

* [For databases accounts] Database Type — limit the list of accounts by database type (All, AWS RDS, Azure SQL, MySQL (SQL Built-In), PostgreSQL).

1. Click Remove.

Alternatively, you can right-click the necessary account and choose Remove.

1. In the confirmation window, click Yes.


