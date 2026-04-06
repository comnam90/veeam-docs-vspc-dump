---
title: "Rebooting Remote Computers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/reboot_remote_computers.html"
last_updated: "9/1/2025"
product_version: "9.1.0.30636"
---

# Rebooting Remote Computers


In some cases, you may need to reboot computers that run Veeam Service Provider Console management agents. The most often cases when you need to perform computer reboot are:

* Installation of Veeam backup agents: if a pending computer reboot is detected during Veeam backup agent installation, you must reboot a computer to complete the installation process.
* Installation of the CBT Driver: after you install the CBT driver, you must reboot a computer.
* Installation of Veeam Backup & Replication: if a pending computer reboot is detected during Veeam Backup & Replication installation, you must reboot a computer to complete the installation process.

|  |
| --- |
| Note: |
| You can send commands to Veeam Service Provider Console management agents only for Windows Veeam Backup & Replication servers. For Linux Veeam Backup & Replication servers, use Veeam Host Management Console. For details, see section [Performing Maintenance Tasks](https://helpcenter.veeam.com/docs/vbr/userguide/hmc_perform_maintenance_tasks.html?ver=13) of the Veeam Backup & Replication User Guide. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Rebooting Discovered Computers

To send a command to Veeam Service Provider Console management agents to initiate reboot of remote computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary computers in the list.
4. At the top of the list, click Management Agent and choose Reboot Remote Computer.

Alternatively, you can right-click the necessary computer, choose Management Agent and select Reboot Remote Computer.

1. In the displayed window, click Yes to confirm computer reboot.

Rebooting Veeam Backup & Replication Servers

To send a command to Veeam Service Provider Console management agents to initiate reboot of backup servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Servers tab.
3. Select the necessary backup servers in the list.
4. At the top of the list, click Server Actions and choose Reboot Remote Computer.

Alternatively, you can right-click the necessary backup server, choose Server Actions and select Reboot Remote Computer.

1. In the displayed window, click Yes to confirm reboot of the backup server.

Rebooting Veeam Cloud Connect Servers

To send a command to Veeam Service Provider Console management agents to initiate reboot of Veeam Cloud Connect servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. From the Veeam Cloud Connect servers list, select the server which you want to reboot.
6. At the top of the list, click Server Management and select Reboot Remote Computer.

Alternatively, you can right-click the necessary Veeam Cloud Connect server, choose Server Management and select Reboot Remote Computer.

1. In the displayed window, click Yes to confirm reboot of the server.


