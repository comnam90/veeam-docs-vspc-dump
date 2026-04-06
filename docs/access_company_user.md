---
title: "Accessing Veeam Service Provider Console as Company User"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/access_company_user.html"
last_updated: "10/20/2025"
product_version: "9.1.0.30636"
---

# Accessing Veeam Service Provider Console as Company User


If you need to access the Reseller Portal or the Client Portal, you can log in to Veeam Service Provider Console as a company user or a Service Provider Administrator.

For details on Veeam Service Provider Console features available in the Client Portal, see [Guide for End Users](https://helpcenter.veeam.com/docs/vac/provider_user/about.html?ver=9.1). For details on Veeam Service Provider Console features available in the Reseller Portal, see [Guide for Resellers](https://helpcenter.veeam.com/docs/vac/reseller/about.html?ver=9.1).

Required Privileges

To perform the task, a user must have the following role assigned: Portal Administrator.

Accessing Veeam Service Provider Console as Company User

To log in to Veeam Service Provider Console portal as another user:

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

1. Select the necessary user and click Log in as.

Veeam Service Provider Console will open the web portal for the selected user.

1. To return to the Administrator Portal:

1. At the top right corner of the Veeam Service Provider Console window, click the user name and select Log Out.
2. Log in to Veeam Service Provider Console as a Portal Administrator.


