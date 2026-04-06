---
title: "Accessing Veeam Backup & Replication Server PowerShell Console"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/vbr_ps.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Accessing Veeam Backup & Replication Server PowerShell Console


To fix Veeam Backup & Replication server issues directly on Veeam Service Provider Console portal, you can use remote PowerShell console. It allows users to perform the same scope of operations as local console including the Veeam PowerShell commands.

For details on the Veeam Backup PowerShell module, see [Veeam PowerShell Reference](https://helpcenter.veeam.com/docs/backup/powershell/getting_started.html).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Accessing Veeam Backup & Replication server PowerShell Console

To launch remote PowerShell console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Servers tab.
3. Select a Veeam Backup & Replication server in the list.
4. At the top of the list, click PowerShell Session.

Alternatively, you can right-click the necessary server and choose PowerShell Session.

The new web browser tab will open.

1. In the Login Window, specify credentials of a Veeam Backup & Replication server user and click Login.

|  |
| --- |
| Note: |
| Consider the following:   * WebSocket Protocol must be enabled on the machine on which Veeam Service Provider Console Web UI component is installed. On the Windows 7 and Windows Server 2008 R2 machines WebSocket Protocol cannot be enabled. * If there are no operations running in the remote console for 15 minutes, the session is canceled and you will be required to authenticate again. * If another user authenticates to the same Veeam Backup & Replication server using remote PowerShell console, your session will be canceled. |

You can also remotely access PowerShell console of a Veeam Backup & Replication server that runs a specific virtual machine job. To do that:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. Select a job in the list.
4. At the top of the list, click PowerShell Session.

Alternatively, you can right-click the necessary job and choose PowerShell Session.

The new web browser tab will open.

1. In the Login Window, specify credentials of a Veeam Backup & Replication server user and click Login.


