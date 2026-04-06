---
title: "Downloading Logs from Veeam Backup for Microsoft 365 Servers"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/vbo_server_logs.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Downloading Logs from Veeam Backup for Microsoft 365 Servers


You can download Veeam Backup for Microsoft 365 log files from managed Veeam Backup for Microsoft 365 servers without having to access the Veeam Backup for Microsoft 365 console.

Log files are downloaded as a single ZIP archive. If you choose to download logs for more than one Veeam Backup for Microsoft 365 server, the archive will include a separate archive with log files for each chosen server.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Downloading Logs from Veeam Backup for Microsoft 365 Servers

To download logs from one or more Veeam Backup for Microsoft 365 servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Microsoft 365 Backup Servers tab.
3. Select the necessary servers in the list.
4. Click Download Logs.

Alternatively, you can right-click the necessary server and choose Download Logs.

1. In the Download Logs window, specify a number of days for which you want to gather logs from managed Veeam Backup for Microsoft 365 servers.
2. Click Start.

Veeam Service Provider Console will display a window with a message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


