---
title: "Downloading Veeam Service Provider Console Management Agent Logs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/download_vac_agent_logs.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Downloading Veeam Service Provider Console Management Agent Logs


You can download logs from Veeam Service Provider Console management agents.

Log files are downloaded as a single ZIP archive. If you choose to download logs for more than one computer, the archive will include a separate archive with log files for each chosen Veeam Service Provider Console management agent.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Downloading Veeam Service Provider Console Management Agent Logs

To download logs from one or more client computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary computers in the list.
4. At the top of the list, click Management Agent and select Download Logs.

Alternatively, you can right-click the necessary computer, choose Management Agent and select Download Logs.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.

|  |
| --- |
| Note: |
| If the management agent is inaccessible from Veeam Service Provider Console, you can obtain agent logs from the remote computer. On Windows machines, Veeam Service Provider Console management agent logs are located in the C:\ProgramData\Veeam\Veeam Availability Console\Log\Agent folder. On Linux and Mac machines, Veeam Service Provider Console management agent logs are located in the /var/log/veeamma folder. |


