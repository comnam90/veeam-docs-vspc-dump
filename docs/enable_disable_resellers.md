---
title: "Disabling and Enabling Resellers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_resellers.html"
last_updated: "6/4/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Resellers


You can disable and enable resellers to control availability of cloud resources, and functionality available to companies in Veeam Service Provider Console.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Disabling Resellers

To temporarily prevent a reseller from working with Veeam Service Provider Console and consuming cloud resources, you can disable an account for this reseller. After a reseller is disabled, the following limitations are enforced:

* Portal Administrators and Portal Operators cannot perform management tasks for a disabled reseller and companies managed by this reseller, such as perform discovery, manage jobs, create invoices and so on.
* Users of a disabled reseller and companies managed by this reseller cannot access the Veeam Service Provider Console Portal.
* cloud tenants managed by a disabled reseller cannot use allocated cloud resources: start and finish jobs that are targeted at cloud repositories and cloud hosts, restore data from cloud repositories and cloud hosts, and perform failover operations.

|  |
| --- |
| Note: |
| When you disable a reseller, all companies and cloud tenants managed by this reseller are also disabled. All running tasks that target cloud repositories and cloud hosts, such as backup jobs and restore tasks, are terminated immediately, without waiting for them to finish. |

To disable one or more resellers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Resellers.
2. Select one or more resellers in the list.
3. At the top of the list, click Disable.

Alternatively, you can right-click the necessary reseller and choose Disable.

1. In the confirmation window, click Yes.

Enabling Resellers

To enable one or more previously disabled resellers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Resellers.
2. Select one or more resellers in the list.
3. At the top of the list, click Enable.

Alternatively, you can right-click the necessary reseller and choose Enable.

Veeam Service Provider Console will enable selected resellers and all companies managed by these resellers.


