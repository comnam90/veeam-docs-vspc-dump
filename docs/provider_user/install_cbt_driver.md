---
title: "Managing CBT Driver"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/install_cbt_driver.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Managing CBT Driver


To increase the speed and efficiency of incremental backups of managed computers, you may need to install the CBT driver. The driver is installed on every server machine protected with Veeam backup agent.

The CBT driver keeps track of data blocks that changed since the latest backup session. Information about changed data blocks is registered, and when a backup job runs, Veeam backup agent uses this information to find out what data blocks have changed since the last run of the job, and then copies only changed data blocks from the disk.

Prerequisites

You can install the CBT driver on managed computers that meet all of the following requirements:

* Computers must run a 64-bit version of Microsoft Windows OS.
* Computers must run one of the following OSes:

* Microsoft Windows 11 (from version 21H2 to version 23H2).
* Microsoft Windows 10 (from version 1803 to version 22H2).
* Microsoft Windows Server OS that is supported by Veeam Agent. For details, see section [System Requirements](https://helpcenter.veeam.com/docs/agentforwindows/userguide/system_requirements.html) of the Veeam Agent for Microsoft Windows User Guide.

* Computers must run the following version of Veeam backup agents:

* Veeam backup agent 5.0 or later for agents running in Server operation mode
* Veeam backup agent 6.0 or later for agents running in Workstation operation mode

|  |
| --- |
| Important! |
| Consider the following:   * Prior to installing the Veeam CBT driver on a computer running Microsoft Windows Server 2008 R2, make sure that update KB3033929 is installed in the OS. For details, see [this Microsoft webpage](https://www.microsoft.com/en-us/download/details.aspx?id=46083).   The update adds the SHA-2 code signing support that is required for verification of the Veeam CBT driver signature. Without this update installed, the OS running on a protected computer will fail to boot after you install the Veeam CBT driver. For details, see [this Microsoft KB article](https://support.microsoft.com/en-us/help/3033929/microsoft-security-advisory-availability-of-sha-2-code-signing-support).   * Do not install the Veeam CBT driver on a computer running Microsoft Windows Server 2008 R2, 2012 or 2012 R2 if one or more volumes on this computer are encrypted with Microsoft BitLocker (or other encryption tool), or if you plan to use Microsoft BitLocker to encrypt volumes on this computer. Concurrent operation of Microsoft BitLocker and Veeam CBT driver may result in driver failures and may prevent the OS from starting. * Do not install the Veeam CBT driver on a computer if you plan to use devices with hardware encryption made according to the TCG Opal Security Subsystem Class Specification. Operation of the driver on such devices may lead to a crash of the operating system. For details about the TCG Opal Security Subsystem Class Specification, see [this Trusted Computing Group webpage](https://trustedcomputinggroup.org/resource/storage-work-group-storage-security-subsystem-class-opal/). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Installing CBT Driver

To install the CBT driver for one or more Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and choose Install CBT Driver.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Install CBT Driver.

1. Check the value in the CBT Driver column.

When installation completes, it must display Installed (Reboot required) status.

1. Reboot computers on which you installed the CBT driver.

You can reboot the remote computer in Veeam Service Provider Console, as described in [Rebooting Remote Computers](reboot_remote_computers.md).

Uninstalling CBT Driver

To uninstall the CBT driver from one or more Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and choose Uninstall CBT Driver.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Uninstall CBT Driver.

1. Reboot computers on which you uninstalled the CBT driver.

You can reboot the remote computer in Veeam Service Provider Console, as described in [Rebooting Remote Computers](reboot_remote_computers.md).


