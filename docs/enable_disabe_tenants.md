---
title: "Disabling and Enabling Companies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disabe_tenants.html"
last_updated: "6/4/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Companies


You can disable and enable companies to control availability of cloud resources, and functionality available to companies in Veeam Service Provider Console.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Disabling Companies

To temporarily prevent company users from working with Veeam Service Provider Console and consuming cloud resources, you can disable an account for this company. After a company is disabled, the following limitations are enforced:

* Portal Administrators and Portal Operators cannot perform management tasks for a disabled company, such as perform discovery, manage jobs, create invoices and so on.
* Users of a disabled company cannot access the Veeam Service Provider Console Portal.

|  |
| --- |
| Note: |
| All active alarms for a disabled company are automatically resolved. |

To disable one or more companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select one or more companies in the list.
3. At the top of the list, click Disable.

Alternatively, you can right-click the necessary company and choose Disable.

1. In the displayed window, click Yes.

Enabling Companies

To enable one or more previously disabled companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select one or more companies in the list.
3. At the top of the list, click Enable.

Alternatively, you can right-click the necessary company and choose Enable.


