---
title: "Creating Subtenants"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_subtenant_user.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Creating Subtenants


You can create a new portal user with the Subtenant role and allocate to this user cloud repository space, or user quota. A user quota is an amount of storage space allocated for a specific user within the company quota on a cloud repository.

A Subtenant can consume storage resources provided through the user quota for storing Veeam agent backups in the cloud. When pointing a Veeam backup agent job to a cloud repository, you can specify credentials of a Subtenant. Backup files created by the Veeam backup agent job will consume cloud space within the Subtenant quota only.

In addition to storing backups on a cloud repository, a Subtenant can access the Veeam Service Provider Console Client Portal. The scope of monitoring data available to a Subtenant in the Client Portal is limited to a computer (or computers) protected with Veeam backup agents whose data is stored on a cloud repository under the account of the Subtenant. That is, a Subtenant can view details only about those Veeam backup agents that are configured to store backup data to the cloud under credentials of this user.

|  |
| --- |
| Note: |
| You can create subtenant accounts only for companies based on native Veeam Cloud Connect tenants. Creating subtenant accounts for companies based on VMware Cloud Director tenant accounts is not supported. |

To create a new Subtenant in Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the Managed Companies tab and navigate to Local Users.
4. On the Local Users tab, click New.

Alternatively, you can right-click the user list and choose New.

Veeam Service Provider Console will launch the New User wizard.

1. At the Company step of the wizard, select the company for which the user will be created.

[![Select Company](images/select_company.webp)](images/select_company.webp "Select Company")

1. At the Role step of the wizard, choose Subtenant and select cloud tenant for which the user will be created.

[![Select Cloud Tenant](images/select_cloud_tenant.webp)](images/select_cloud_tenant.webp "Select Cloud Tenant")

1. At the User Info step of the wizard, specify user title, first name, last name and email address.

Veeam Service Provider Console can use this address to send email notifications to the user, such as password reset notifications.

[![Specify User Info](images/create_company_user.webp)](images/create_company_user.webp "Specify User Info")

1. At the Login Info step of the wizard, in the Login, Password and Confirm password fields, type a user login name and password.

It is recommended to use a password that contains characters from at least 3 of the following categories: uppercase characters, lowercase characters, base 10 digits (0 through 9), non-alphanumeric characters. The recommended password length is 6 or more characters.

[![Specify User Credentials](images/specify_subtenant_credentials.webp)](images/specify_subtenant_credentials.webp "Specify User Credentials")

1. At the Locations step of the wizard, click the link and select company locations whose data must be available for the user in the Client Portal. Click Apply.

[![Specify Location](images/specify_location_subtenant.webp)](images/specify_location_subtenant.webp "Specify Location")

1. At the Quota step of the wizard, allocate cloud repository resources to the user.

You can specify the size of the user quota or create an unlimited user quota. With an unlimited user quota, the Subtenant can consume all storage space within the company quota on a cloud repository.

[![Specify Quota](images/create_company_user_quota.webp)](images/create_company_user_quota.webp "Specify Quota")

1. At the Multi-Factor Authentication step of the wizard you can assign a second authentication factor to the user. For details on MFA, see [Configuring Multi-Factor Authentication](mfa.md).

To enable MFA for the new user, set the Mandatory MFA usage toggle to On. On the next authorization session, the user will be prompted to configure MFA.

[![Configure MFA Access](images/create_company_subtenant_mfa.webp)](images/create_company_subtenant_mfa.webp "Configure MFA Access")

1. At the Summary step of the wizard, review user details and click Finish.

[![Review User Details](images/create_company_subtenant_summary.webp)](images/create_company_subtenant_summary.webp "Review User Details")

Automatic Creation of Subtenants

Veeam Service Provider Console can automatically create Subtenants. This normally happens if you use a backup policy that is configured to store backup data on a cloud repository and to create subtenant accounts for each managed Veeam backup agent automatically. When such backup policy is assigned to Veeam backup agents, Veeam Service Provider Console creates a Subtenant account for each Veeam backup agent to which the backup policy is assigned. For details, see [Step 14. Specify Cloud Repository Quota](specify_cloud_quota.md).

Veeam backup agents use these Subtenant accounts to write data to a cloud repository. The name of each Subtenant account is formed according to the following pattern: <company\_name>\_<computer\_name>.


