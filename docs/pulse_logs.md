---
title: "Downloading VCSP Pulse Plugin Logs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_logs.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Downloading VCSP Pulse Plugin Logs


You can download VCSP Pulse plugin log files, including:

* Logs for the VCSP Pulse plugin Server component
* Logs for the VCSP Pulse plugin Web UI component

Log files are downloaded as a single ZIP archive. The archive includes two folders for log files for the Server and Web UI components.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Downloading VCSP Pulse Plugin Logs

To download VCSP Pulse plugin logs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Support Information.
5. Click the Download Logs button.
6. In the Download Logs window, specify the number of days for which you want to gather logs from client backup servers.
7. Click Start.
8. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


