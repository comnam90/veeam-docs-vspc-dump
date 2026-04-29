---
title: "Disabling and Enabling Veeam Backup for Public Clouds Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/disable_enable_cloud_jobs.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Disabling and Enabling Veeam Backup for Public Clouds Policies


You can disable and enable scheduled cloud VM, file and database policies without accessing the Veeam Backup for Public Clouds appliance on managed backup servers.

Disabling Policies

To disable one or more scheduled policies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to disable cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to disable cloud file protection policies (Snapshot, Replica snapshot)
* Cloud Databases — select this tab to disable cloud database protection policies (Snapshot, Replica snapshot, Archive)
* Cloud Networks — select this tab to disable cloud network protection policies

1. Select the necessary policies in the list.
2. At the top of the list, click Scheduling > Disable.

Alternatively, you can right-click the necessary policy and choose Scheduling > Disable.

Enabling Policies

To enable one or more previously disabled policies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to enable cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to enable cloud file protection policies (Backup, Backup copy)
* Cloud Databases — select this tab to enable cloud database protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Cloud Networks — select this tab to enable cloud network protection policies

1. Select the necessary policies in the list.
2. At the top of the list, click Scheduling > Enable.

Alternatively, you can right-click the necessary policy and choose Scheduling > Enable.


