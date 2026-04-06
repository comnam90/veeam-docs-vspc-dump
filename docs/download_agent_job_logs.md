---
title: "Downloading Veeam Backup Agent Logs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/download_agent_job_logs.html"
last_updated: "1/17/2024"
product_version: "9.1.0.30636"
---

# Downloading Veeam Backup Agent Logs


You can export logs for Veeam backup agent installed on managed computers.

Log files are downloaded as a single ZIP archive. If you choose to download logs for more than one managed Veeam backup agents, the archive will include a separate archive with log files for each chosen Veeam backup agent.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Downloading Veeam Backup Agent Logs

To download Veeam backup agents logs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select the necessary computer in the list.
4. At the top of the list, click Download Logs.

Alternatively, you can right-click the necessary job and choose Download Logs.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.

Downloading Veeam Backup Agent Job Logs

To download logs for specific Veeam backup agent jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Choose the necessary computer in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
4. In the Agent Jobs window, select one or more jobs and click Download Logs.

Alternatively, you can right-click the necessary job and choose Download Logs.

1. [For Microsoft Windows computers] In the Download Logs window, specify a number of days for which logs must be collected and click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.

Other Ways to Download Veeam Backup Agent Logs

You can download Veeam backup agent logs in the list of managed Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Agents tab.
3. Select the necessary Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and select Download Logs.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Download Logs.

1. [For Microsoft Windows computers] In the Download Logs window, specify a number of days for which logs must be collected and click Start.

Veeam Service Provider Console will display a window with message notifying that the download process started. Click OK to close the window.

1. Wait until Veeam Service Provider Console collects log data.

The file with exported data will be saved to the default download location on your computer.


