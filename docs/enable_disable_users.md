---
title: "Disabling and Enabling Company Users"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_users.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Company Users


To control access to the Veeam Service Provider Console Client Portal, you can enable and disable company users.

Disabling Company Users

To prevent a company user from accessing the Veeam Service Provider Console Client Portal, you can disable this user. It is recommended to disable users to instantly revoke access to the portal for these users.

|  |
| --- |
| Note: |
| You cannot disable a Subtenant if credentials of this user are specified in a Veeam backup agent job settings. This situation is possible if you configured a backup job to write data to a cloud repository under an account of the Subtenant you plan to disable. Before you can disable the user, you must specify another account in the Veeam backup agent job settings. For details on changing Veeam backup agent job settings, see [Modifying Veeam Backup Agent Jobs](modify_agent_job.md). |

To disable a company user:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the Managed Companies tab and navigate to Local Users.
4. To narrow down the list of users, you can apply the following filters:

* Company — search the list of users by company to which the user belongs.
* Login — search the list of users by user login.
* Role — limit the list of users by role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor, Service Provider Global Administrator).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select users in the list.
2. At the top of the user list, click Disable.

Alternatively, you can right-click the necessary user and choose Disable.

1. In the Change Users Status window, click Yes.

Enabling Company Users

To enable a previously disabled company user:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the Managed Companies tab and navigate to Local Users.
4. To narrow down the list of users, you can apply the following filters:

* Company — search the list of users by company to which the user belongs.
* Login — search the list of users by user login.
* Role — limit the list of users by role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor, Service Provider Global Administrator).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select users in the list.
2. At the top of the user list, click Enable.

Alternatively, you can right-click the necessary user and choose Enable.


