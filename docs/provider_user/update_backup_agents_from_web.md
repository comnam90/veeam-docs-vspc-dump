---
title: "Upgrading Veeam Backup Agents from Veeam Installation Server"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/update_backup_agents_from_web.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Upgrading Veeam Backup Agents from Veeam Installation Server


The procedure of upgrading Veeam backup agents from Veeam Installation Server is performed with the help of Veeam Service Provider Console management agents. The management agent downloads the Veeam backup agent setup file from the Veeam Installation Server (over the Internet), uploads this setup file to the remote computer hosting the management agent, and initiates the software upgrade.

Before You Begin

Before you start the upgrade procedure, make sure that:

* Computers on which you plan to upgrade Veeam backup agents are powered on.

If the computer is not powered on and you start the upgrade procedure for this computer, Veeam Service Provider Console will wait for 30 days for the computer to become accessible.

* * Computers are configured to allow upload of a Veeam backup agent setup file: the File and Printer Sharing (SMB-In) firewall rule must allow inbound traffic.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Location Administrator.

Upgrading Veeam Backup Agents

To upgrade Veeam backup agents installed with a discovery rule:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and choose Upgrade.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Upgrade.

After you initiate the upgrade procedure, the value in the Backup Agent Version column will change to Updating. You can click the Updating link to track the progress of the upgrade procedure.

1. Check the value in the Backup Agent Version column.

After the upgrade procedure completes, the value in this column will be set to Up-to-date.

In some cases, after upgrade you may need to perform additional operations. For example, if the setup detects a pending computer reboot, the Backup Agent Version column will display a warning notifying that reboot is required. To complete the upgrade procedure, you can initiate computer reboot in Veeam Service Provider Console. For details, see [Rebooting Remote Computers](reboot_remote_computers.md).


