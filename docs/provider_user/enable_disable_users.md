---
title: "Disabling and Enabling Portal Users"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/enable_disable_users.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Portal Users


To control access to the Veeam Service Provider Console Client Portal, you can enable and disable users.

|  |
| --- |
| Note: |
| When disabling portal users, consider the following limitations:   * You cannot disable a Subtenant if credentials of this user are specified in a Veeam backup agent job settings. This situation is possible if you configured a backup job to write data to a cloud repository under an account of the Subtenant you plan to disable. Before you can disable the user, you must specify another account in the Veeam backup agent job settings. For details on changing Veeam backup agent job settings, see [Configuring Backup Job Settings for Individual Computers](change_backup_job_settings.md). * You cannot disable or enable a Company Tenant. The Company Tenant user is disabled when your service provider disables a cloud tenant account that uses credentials of this Company Tenant. To enable a Company Tenant account, contact your service provider. |

Required Privileges

To perform the task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

* Company Owner can disable and enable any users except Company Tenant.
* Company Administrator can disable and enable any users except Company Owner and Company Tenant.
* Location Administrator can disable and enable Location Users and Subtenants only.

* Company Tenant can disable and enable Subtenants only.

Disabling Portal Users

To disable a portal user:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users and navigate to Local Users.
3. To narrow down the list of users, you can apply the following filters:

* Company — name of a company to which user belongs.
* Role — user role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select users in the list.
2. At the top of the user list, click Disable.

Alternatively, you can right-click the necessary policy and choose Disable.

1. In the Change Users Status window, click Yes.

Enabling Portal Users

To enable a portal user you previously disabled:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users and navigate to Local Users.
3. To narrow down the list of users, you can apply the following filters:

* Company — name of a company to which user belongs.
* Role — user role (Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User, Subtenant, Company Invoice Auditor).
* MFA status — indicates whether multi-factor authentication is enforced for user (Enforced, Not enforced, Not configured).

1. Select users in the list.
2. At the top of the user list, click Enable.

Alternatively, you can right-click the necessary policy and choose Enable.


