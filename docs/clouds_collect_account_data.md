---
title: "Collecting Data from Accounts"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_collect_account_data.html"
last_updated: "11/14/2025"
product_version: "9.1.0.30636"
---

# Collecting Data from Accounts


By default, Veeam Backup for Public Clouds appliances send data to Veeam Service Provider Console every hour or at specific events, such as policy session failure. If required, you can initiate unscheduled collection of managed accounts details.

To collect data from Veeam Backup for Public Clouds and guest OS accounts:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Accounts.
5. Open the necessary tab:

* Public Cloud — select this tab to view Amazon Web Services, Microsoft Azure and Google Cloud accounts.
* Databases — select this tab to view database administrator accounts.
* Guest OS — select this tab to view guest OS accounts.
* Databases — select this tab to view database administrator accounts.

1. Select the necessary accounts in the list.
2. Click Collect Data.

Alternatively, you can right-click the necessary account and select Collect Data.


