---
title: "Starting and Stopping Veeam Backup for Public Clouds Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/start_stop_cloud_jobs.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Starting and Stopping Veeam Backup for Public Clouds Policies


You can start and stop Veeam Backup for Public Clouds policies without accessing the managed backup servers. For example, if a backup policy failed, you can manually start this policy in Veeam Service Provider Console to avoid data loss.

Starting Policies

To start one or more Veeam Backup for Public Clouds policies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to start cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to start cloud file protection policies (Snapshot, Replica snapshot)
* Cloud Databases — select this tab to start cloud database protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Cloud Networks — select this tab to start cloud network protection policies

1. Select the necessary policies in the list.
2. At the top of the list, click Actions > Start.

Alternatively, you can right-click the necessary policy and choose Actions > Start.

Stopping Policies

To stop one or more running Veeam Backup for Public Clouds policies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to stop cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to stop cloud file protection policies (Snapshot, Replica snapshot)
* Cloud Databases — select this tab to stop cloud database protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Cloud Networks — select this tab to stop cloud network protection policies

1. Select the necessary policies in the list.
2. At the top of the list, click Actions > Stop.

Alternatively, you can right-click the necessary policy and choose Actions > Stop.


