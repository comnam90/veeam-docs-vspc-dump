---
title: "Removing Resellers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_resellers.html"
last_updated: "6/4/2025"
product_version: "9.1.0.30636"
---

# Removing Resellers


If you no longer provide backup services to companies through a reseller, you can remove an account registered for this reseller.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

|  |
| --- |
| Note: |
| When you remove a reseller account, consider the following:   * All companies and cloud tenants managed by this reseller will be moved under management of a Service Provider. * Subscription plans created by this reseller will remain available for the Service Provider. * All backup policies created by this reseller will be deleted. If this policy was assigned to one or more managed Veeam backup agents, the backup policy type on these agents will be changed to Custom. |

Removing Resellers

To remove a reseller account:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Resellers.
2. Select the necessary reseller in the list.
3. At the top of the list, click Remove.

Alternatively, you can right-click the necessary reseller and choose Remove.

1. In the displayed window, click Yes to confirm account removal.


