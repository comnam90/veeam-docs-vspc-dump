---
title: "Downloading Logs from Veeam ONE Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/one_server_logs.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Downloading Logs from Veeam ONE Servers


You can download Veeam ONE log files from managed Veeam ONE servers without having to access the Veeam ONE Client.

Log files are downloaded as a single ZIP archive. If you choose to download logs for more than one Veeam ONE server, the archive will include a separate archive with log files for each chosen server.

Required Privileges

To manage Veeam ONE servers, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Downloading Logs from Veeam ONE Servers

To download logs from one or more Veeam ONE servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the ONE Servers tab.
3. Select the necessary servers in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Application status — limit the list of servers by application status (Running, Not running).
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error).
* Management agent version — limit the list of servers by management agent version (Up-to-date, Out-of-date, Patch available, N/A).

* Alarms data collection — limit the list of servers by alarms syncronization status (Enabled, Disabled, Error).

1. Click Download Logs.

Alternatively, you can right-click the necessary server and choose Download Logs.

1. In the Download Logs window, specify a number of days for which you want to gather logs from managed Veeam ONE servers.
2. Click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


