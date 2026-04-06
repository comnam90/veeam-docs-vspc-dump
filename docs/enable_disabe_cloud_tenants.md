---
title: "Disabling and Enabling Cloud Tenants"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disabe_cloud_tenants.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Cloud Tenants


You can disable and enable cloud tenants to control availability of cloud resources, and functionality available to companies in Veeam Service Provider Console.

Disabling Cloud Tenants

To temporarily prevent cloud tenant users from working with Veeam Service Provider Console and consuming cloud resources, you can disable an account for this cloud tenant. After a cloud tenant is disabled, the following limitations are enforced:

* Portal Administrators and Portal Operators cannot perform management tasks for a disabled cloud tenant, such as perform discovery, manage jobs, create invoices and so on.
* Users of a disabled cloud tenant cannot access the Veeam Service Provider Console Portal.
* A disabled cloud tenant and a mapped Veeam Service Provider Console company cannot use allocated cloud resources: start and finish jobs that are targeted at cloud repositories and cloud hosts, restore data from cloud repositories and cloud hosts, and perform failover operations.

|  |
| --- |
| Note: |
| When you disable a cloud tenant, all running tasks that target cloud repositories and cloud hosts, such as backup jobs and restore tasks, are terminated immediately, without waiting for them to finish. All active alarms for a disabled cloud tenant are automatically resolved. |

To disable one or more companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Select one or more cloud tenants in the list.

To narrow down the list of cloud tenants, you can apply the following filters:

* Cloud Tenant Name — search the list of cloud tenants by name.
* VSPC Company Name — search the list of cloud tenants by mapped VSPC company name.
* Tenant type — limit the list of cloud tenants by type (Native, Cloud Director).
* Mapping status — limit the list of cloud tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Disable.

Alternatively, you can right-click the necessary cloud tenant and choose Disable.

1. In the displayed window, click Yes.

Enabling Cloud Tenants

To enable one or more previously disabled cloud tenants:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Select one or more cloud tenants in the list.

To narrow down the list of cloud tenants, you can apply the following filters:

* Cloud Tenant Name — search the list of cloud tenants by name.
* VSPC Company Name — search the list of cloud tenants by mapped VSPC company name.
* Tenant type — limit the list of cloud tenants by type (Native, Cloud Director).
* Mapping status — limit the list of cloud tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Enable.

Alternatively, you can right-click the necessary cloud tenant and choose Enable.


