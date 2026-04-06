---
title: "Applying Patches to Veeam Backup Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/apply_backup_agent_patch.html"
last_updated: "8/1/2025"
product_version: "9.1.0.30636"
---

# Applying Patches to Veeam Backup Agents


From time to time, you may obtain from Veeam Software patches aimed to fix known issues in the Veeam backup agent software. Applying patches on individual computers in the hosted and client infrastructures may take a lot of time and effort. To streamline this process, you can apply patches to a group of Veeam backup agents managed in Veeam Service Provider Console.

The procedure of applying patches to Veeam backup agents is performed with the help of management agents. The management agents obtain a patch file provided by the Administrator Portal user, upload this file to managed computers within the patching scope, and initiate the patching process on these computers.

Before You Begin

Before you start the procedure of applying patches, make sure that:

* Computers that run Veeam backup agents are powered on.
* [For Microsoft Windows computers] Computers are configured to allow upload of a Veeam backup agent patch file: the File and Printer Sharing (SMB-In) firewall rule must allow inbound traffic.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Applying Patches to Veeam Backup Agents

To apply a patch to Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Agents tab.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Backup Agent and choose Patch.

Alternatively, you can right-click the necessary Veeam backup agent, choose Backup Agent and select Patch.

1. In the Windows Open dialog box, select a file with the patch, and click Open.


