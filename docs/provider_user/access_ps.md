---
title: "Accessing Remote PowerShell Console"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/access_ps.html"
last_updated: "3/18/2026"
product_version: "9.2.0.33215"
---

# Accessing Remote PowerShell Console


To fix issues with Microsoft Windows computers directly in Veeam Service Provider Console portal, you can use remote PowerShell console. It allows users to perform the same scope of operations as local console including the Veeam PowerShell commands.

For details on Veeam PowerShell modules, see [Veeam PowerShell Reference](https://helpcenter.veeam.com/docs/backup/powershell/getting_started.html) and [Veeam Backup for Microsoft 365 PowerShell Reference](https://helpcenter.veeam.com/docs/vbo365/powershell/getting_started.html).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Before You Begin

Before you launch remote PowerShell console, make sure your service provider has enabled PowerShell access to remote computers.

Accessing Remote PowerShell Console

To launch remote PowerShell console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. Select the necessary computer in the list.
4. At the top of the list, click PowerShell Session.

Alternatively, you can right-click the necessary computer and choose PowerShell Session.

The new web browser tab will open.

1. In the Login Window, specify credentials of a local user and click Login.

|  |
| --- |
| Note: |
| Consider the following:   * WebSocket Protocol must be enabled on the machine on which Veeam Service Provider Console Web UI component is installed. On the Windows 7 and Windows Server 2008 R2 machines WebSocket Protocol cannot be enabled. * If there are no operations running in the remote console for 15 minutes, the session is canceled and you will be required to authenticate again. * If another user authenticates to the same computer using remote PowerShell console, your session will be canceled. |

You can also remotely access PowerShell console of a Veeam Backup & Replication server that runs a specific virtual machine job. To do that:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Virtual Machines tab and navigate to Virtual Infrastructure.
3. Select a job in the list.
4. At the top of the list, click Advanced and select PowerShell Session.

Alternatively, you can right-click the necessary job and choose Advanced > PowerShell Session.

The new web browser tab will open.

1. In the Login Window, specify credentials of a Veeam Backup & Replication server user and click Login.


