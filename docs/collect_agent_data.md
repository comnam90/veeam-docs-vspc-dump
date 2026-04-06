---
title: "Collecting Data"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/collect_agent_data.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Collecting Data


By default, Veeam Service Provider Console management agents send data to Veeam Service Provider Console every hour, or when specific events, such as backup job failure, occur. If required, you can initiate unscheduled data collection from machines that run management agents. These can be machines hosting Veeam backup agents, Veeam ONE, Veeam Backup for Microsoft 365, Veeam Backup & Replication and Veeam Backup Enterprise Manager.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Collecting Data from Veeam Backup Agents

To initiate data collection from Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Agents tab.
3. Select one or more Veeam backup agents in the list.
4. Click Data Collection:

* Quick Resync — select this option to collect data changed since the previous data collection session.
* Full Resync — select this option to perform full recollect of data from Veeam backup agent. Click Yes to confirm the operation.

This option is available only if one Veeam backup agent is selected.

Alternatively, you can right-click the necessary Veeam backup agent, choose Data Collection and select the necessary option.

Collecting Data from Veeam Backup & Replication

To initiate data collection from Veeam Backup & Replication and Veeam Backup Enterprise Manager servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Servers tab.
3. Select one or more backup servers in the list.
4. Click Collect Data.

Alternatively, you can right-click the necessary backup server and choose Collect Data.

Collecting Data from Veeam ONE

To initiate data collection from Veeam ONE servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the ONE Servers tab.
3. Select one or more Veeam ONE servers in the list.
4. Click Collect Data.

Alternatively, you can right-click the necessary Veeam ONE server and choose Collect Data.

Collecting Data from Veeam Backup for Microsoft 365

To initiate data collection from Veeam Backup for Microsoft 365 servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Microsoft 365 Backup Servers tab.
3. Select one or more Veeam Backup for Microsoft 365 servers in the list.
4. Click Data Collection:

* Quick Resync — select this option to collect data changed since the previous data collection session.
* Full Resync — select this option to perform full recollect of data from Veeam Backup for Microsoft 365 server. Click Yes to confirm the operation.

This option is available only if one Veeam Backup for Microsoft 365 server is selected.

Depending on the available data, full recollect can take a considerable period of time. Note that all collected Microsoft 365 SLA statistics will be reset.

Alternatively, you can right-click the necessary Veeam Backup for Microsoft 365 server, choose Data Collection and select the necessary option.

Collecting Data from Veeam Backup for Public Clouds

To initiate data collection from Veeam Backup for Public Clouds appliances:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Cloud Appliances tab.
3. Select one or more Veeam Backup for Public Clouds appliance in the list.
4. Click Data Collection:

* Quick Resync — select this option to collect data changed since the previous data collection session.
* Full Resync — select this option to perform full recollect of data from appliances. Click Yes to confirm the operation.

Alternatively, you can right-click the necessary appliance, choose Data Collection and select the necessary option.

Collecting Data from Veeam Cloud Connect

To initiate data collection from Veeam Cloud Connect servers:

1. Log in to Veeam Service Provider Console as a Portal Administrator or Site Administrator.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary Veeam Cloud Connect server in the list.
6. Click Server Management and select Collect Data.

Alternatively, you can right-click the necessary Veeam Cloud Connect server, choose Server Management and select Collect Data.


