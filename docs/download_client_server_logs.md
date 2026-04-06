---
title: "Downloading Logs from Veeam Backup & Replication Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/download_client_server_logs.html"
last_updated: "8/3/2023"
product_version: "9.1.0.30636"
---

# Downloading Logs from Veeam Backup & Replication Servers


You can download Veeam Backup & Replication log files from client and hosted Veeam Backup & Replication servers without having to access the Veeam Backup & Replication console.

Log files are downloaded as a single ZIP archive. If you choose to download logs for more than one backup server, the archive will include a separate archive with log files for each chosen backup server.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Downloading Logs from Veeam Backup & Replication Servers

To download logs from one or more managed backup servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Servers tab.
3. Select the necessary backup servers in the list.
4. Click Server Actions and select Download Logs.

Alternatively, you can right-click the necessary server, choose Server Actions and select Download Logs.

1. In the Download Logs window, specify a number of days for which you want to gather logs from client and hosted backup servers.
2. Click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


