---
title: "Removing Veeam Backup for Public Clouds Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/remove_cloud_jobs.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Removing Veeam Backup for Public Clouds Policies


To remove Veeam Backup for Public Clouds policies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to view cloud VM protection policies (Backup, Snapshot, Replica snapshot, Archive)
* Data Backup > Public Clouds — select this tab to view cloud file protection policies (Snapshot, Replica snapshot)
* Cloud Databases — select this tab to view cloud database protection policies (Backup, Snapshot, Replica snapshot, Archive)

1. Select the necessary policies in the list.
2. At the top of the list, click Remove.

Alternatively, you can right-click the necessary policy and choose Remove.

1. In the confirmation window, click Yes.

|  |
| --- |
| Important! |
| If you delete a backup policy from Veeam Service Provider Console, the policy will be automatically deleted from the Veeam Backup for Public Clouds appliance. |


