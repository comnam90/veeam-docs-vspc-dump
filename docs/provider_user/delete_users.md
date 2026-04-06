---
title: "Removing Portal Users"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/delete_users.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Removing Portal Users


You can remove portal users that you previously created for your company.

|  |
| --- |
| Note: |
| When removing portal users, consider the following limitations:   * You cannot remove the Company Owner or Company Tenant users. These users can be removed by the Portal Administrator only. * You cannot remove a Subtenant if credentials of this user are specified in a Veeam backup agent job settings. This situation is possible if you configured a backup job to write data to a cloud repository under an account of the Subtenant you plan to remove. Before you can remove the user, you must specify another account in the Veeam backup agent job settings. For details on changing Veeam backup agent job settings, see [Configuring Backup Job Settings for Individual Computers](change_backup_job_settings.md). |

Required Privileges

To perform the task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

* Company Owner can delete any users except Company Tenant.
* Company Administrator can delete any users except Company Owner and Company Tenant.
* Location Administrator can delete Location Users and Subtenants only.
* Company Tenant can delete Subtenants only.

Removing Portal Users

To remove one or more portal users:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users and navigate to Local Users.
3. To narrow down the list of users, you can apply the following filters:

* Company — name of a company to which user belongs.
* Role — user role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select the necessary user in the list.
2. At the top of the user list, click Remove.

Alternatively, you can right-click the necessary policy and choose Remove.

1. In the Remove User window, click Yes.


