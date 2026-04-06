---
title: "Modifying Portal Users"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/modify_users.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Modifying Portal Users


You can modify settings of Veeam Service Provider Console portal users.

Required Privileges

To perform the task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

* Company Owner can modify settings for users having any role assigned.
* Company Administrator can modify settings for any users except Company Owner.
* Location Administrator can modify settings for Location Users and Subtenants only.
* Company Tenant can modify settings for Subtenants only.

Modifying Portal User Settings

To modify settings of portal users:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users and navigate to Local Users.
3. To narrow down the list of users, you can apply the following filters:

* Company — name of a company to which user belongs.
* Role — user role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select the necessary user and click Edit.

Alternatively, you can right-click the necessary user and choose Edit.

1. Modify user settings as described in [Creating Portal Users](create_portal_users.md).

You can modify all settings except the user name.

1. Save changes.

|  |
| --- |
| Note: |
| When modifying Company Tenant password, consider that the password change is applied immediately, without waiting for any running tasks to complete. If you modify the password while client's backup to cloud, backup copy to cloud or replication to cloud jobs are still running, these jobs will fail because of lost connection to cloud repositories and hosts. |


