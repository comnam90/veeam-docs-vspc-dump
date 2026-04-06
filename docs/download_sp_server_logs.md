---
title: "Downloading Logs from Veeam Cloud Connect Server"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/download_sp_server_logs.html"
last_updated: "9/16/2025"
product_version: "9.1.0.30636"
---

# Downloading Logs from Veeam Cloud Connect Server


You can download Veeam Backup & Replication log files from a Veeam Cloud Connect server without having to access the Veeam Backup & Replication console. Log files are downloaded as a single ZIP archive.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator.

Downloading Logs from Veeam Cloud Connect Server

To download logs from a Veeam Cloud Connect server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select a Veeam Cloud Connect server in the list.
6. At the top of the list, click Server Management and select Download Logs.

Alternatively, you can right-click the necessary server, choose Server Management and select Download Logs.

1. In the Download Logs window, specify a number of days for which logs must be collected.
2. Click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


