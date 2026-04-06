---
title: "Downloading Veeam Service Provider Console Logs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/download_product_logs.html"
last_updated: "5/12/2025"
product_version: "9.1.0.30636"
---

# Downloading Veeam Service Provider Console Logs


You can download Veeam Service Provider Console log files, including:

* Logs for the Veeam Service Provider Console Server component
* Logs for the Veeam Service Provider Console Web UI component

Log files are downloaded as a single ZIP archive. The archive includes two folders for log files for the Server and Web UI components.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Downloading Veeam Service Provider Console Logs

To download Veeam Service Provider Console logs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click About.
3. In the Support Information section, click Download Logs.
4. In the Download Logs window, specify a number of days for which you want to gather Veeam Service Provider Console logs.

Note that you can download logs only for the last 100 days.

1. Click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.

|  |
| --- |
| Note: |
| Alternatively, you can obtain Veeam Service Provider Console logs from the remote computer. On Windows machines, Veeam Service Provider Console logs are located in the C:\ProgramData\Veeam\Veeam Availability Console\Log\ folder. |


