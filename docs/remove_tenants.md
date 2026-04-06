---
title: "Removing Companies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_tenants.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Removing Companies


If you no longer provide backup services to a company, you can remove an account registered for this company.

|  |
| --- |
| Note: |
| When you remove a company account, consider the following:   * All objects associated with the company, such as managed backup servers and computers, jobs, invoices and so on, will be removed from Veeam Service Provider Console database. * Veeam Service Provider Console management agents will be removed from all machines that belong to the company and mapped cloud tenants.   If you want management agents to remain on machines that belong to mapped cloud tenants, remove mapping between these tenants and the company you want to remove. For details, see [Configuring Cloud Tenant Mapping](assign_cloud_tenants.md#remove).   * All Veeam backup agents that belong to the company will be switched to the Unmanaged mode (Free mode). * All company mappings configured in Veeam Service Provider Console plugins will be removed.   If you have assigned Rental licenses to the company, you will have to remove these licenses from managed Veeam products manually. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator.

Removing Companies

To remove a company account:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary company in the list.
3. At the top of the list, click Remove.

Alternatively, you can right-click the necessary company and choose Remove.

1. In the confirmation window, click Yes.


