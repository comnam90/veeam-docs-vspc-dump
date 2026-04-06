---
title: "Collecting Data from Appliances"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_collect_data.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Collecting Data from Appliances


By default, Veeam Backup for Public Clouds appliances send data to Veeam Service Provider Console every hour or at specific events, such as policy session failure. If required, you can initiate unscheduled data collection from managed appliances.

To collect data from managed Veeam Backup for Public Clouds appliances:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.
5. Select the necessary appliance in the list.
6. Click Data Collection:

* Quick Resync — select this option to collect data changed since the previous data collection session. Click OK to confirm the operation.
* Full Resync — select this option to perform full recollect of data from appliances.

Alternatively, you can right-click the necessary appliance, choose Data Collection and select the necessary option.

To collect data from Veeam Backup for Public Clouds appliances managed by Veeam Backup & Replication servers, go to the Discovery > Cloud Appliances tab. For details, see [Collecting Data](collect_agent_data.md#vb).


