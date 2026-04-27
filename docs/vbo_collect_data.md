---
title: "Collecting Data from Veeam Backup for Microsoft 365 Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_collect_data.html"
last_updated: "4/23/2026"
product_version: "9.2.0.33215"
---

# Collecting Data from Veeam Backup for Microsoft 365 Servers


By default, Veeam Service Provider Console collects data from Veeam Backup for Microsoft 365 servers every 5 minutes.

To collect data immediately, you can initiate data collection from hosted Veeam Backup for Microsoft 365 servers manually:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary server in the list.
6. Click Data Collection:

* Quick Resync — select this option to collect data changed since the previous data collection session.
* Full Resync — select this option to perform full recollect of data from Veeam Backup for Microsoft 365 server. Click Yes to confirm the operation.

This option is available only if one Veeam Backup for Microsoft 365 server is selected.

Depending on the available data, full recollect can take a considerable period of time. Note that all collected Microsoft 365 SLA statistics will be reset.

Alternatively, you can right-click the necessary Veeam Backup for Microsoft 365 server, choose Data Collection and select the necessary option.

To collect data from client Veeam Backup for Microsoft 365 servers, go to the Discovery > Microsoft 365 Backup Servers tab. For details, see [Collecting Data](collect_agent_data.md#vbo).

Collecting Data from All Veeam Backup for Microsoft 365 Servers

Alternatively, you can initiate data collection from all hosted Veeam Backup for Microsoft 365 servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the menu on the left, click Companies.
5. At the top of the page, click Collect Data.


