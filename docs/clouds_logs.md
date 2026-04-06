---
title: "Downloading Veeam Service Provider Console Logs from Veeam Backup for Public Clouds Plugin"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_logs.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Downloading Veeam Service Provider Console Logs from Veeam Backup for Public Clouds Plugin


From Veeam Backup for Public Clouds plugin, you can download Veeam Service Provider Console log files, including:

* Logs for the Veeam Service Provider Console Server component
* Logs for the Veeam Service Provider Console Web UI component

Log files are downloaded as a single ZIP archive. The archive includes two folders for log files for the Server and Web UI components.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Downloading Veeam Backup for Public Clouds Plugin Logs

To download Veeam Backup for Public Clouds plugin logs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Support Information.
5. Click the Download Logs button.
6. In the Download logs window, specify the number of days for which you want to gather logs from client backup servers.
7. Click Start.
8. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


