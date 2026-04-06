---
title: "Managing Site Administrators"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_site_admins.html"
last_updated: "8/26/2025"
product_version: "9.1.0.30636"
---

# Managing Site Administrators


By default, the role of a Site Administrator is granted to the members of the Veeam Backup Administrators group on the Veeam Cloud Connect server added to Veeam Service Provider Console. Veeam Backup Administrators group includes:

* Built-in administrator of the machine running the Veeam Cloud Connect server.
* Users with the Veeam Backup Administrator role assigned in Veeam Backup & Replication on the Veeam Cloud Connect server.

By default, this role is assigned to the members of the local Administrators user group on the Veeam Cloud Connect server.

You can assign the role of a Site Administrator to users and user groups, enable and disable Site Administrators.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Assigning Site Administrator Role

To grant Site Administrator privileges to a user or group, assign to the user or group the role of a Veeam Backup Administrator on the Veeam Cloud Connect server. For details, see section [Managing Users and Roles](https://helpcenter.veeam.com/docs/vbr/userguide/users_roles.html?ver=13) of the Veeam Backup & Replication User Guide.

Disabling Site Administrators

To control access to Veeam Service Provider Console for Site Administrators, you can enable and disable users or groups of users with Site Administrator privileges. It is recommended to disable users to instantly revoke access to the portal for these users.

To disable a user or a user group with Site Administrator privileges:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the My Company tab and navigate to Windows Users.
4. At the top of the page, select the Site Administrator role.
5. Select the necessary user or user group in the list.

To narrow down the list of users, you can apply the following filters:

* Name — limit the list of users by name.
* User type — limit the list of users by type (Users, Groups).

* MFA status — limit the list of users by multi-factor authentication status (Enforced, Not enforced).

1. Click Disable.

Alternatively, you can right-click the necessary user and choose Disable.

Enabling Site Administrators

To enable a user group with Site Administrator privileges:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the My Company tab and navigate to Windows Users.
4. At the top of the page, select the Site Administrator role.
5. Select the necessary user or user group in the list.

To narrow down the list of users, you can apply the following filters:

* Name — limit the list of users by name.
* User type — limit the list of users by type (Users, Groups).

* MFA status — limit the list of users by multi-factor authentication status (Enforced, Not enforced).

1. Click Enable.

Alternatively, you can right-click the necessary user and choose Enable.


