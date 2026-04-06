---
title: "Managing Company Tenants"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_company_tenants.html"
last_updated: "11/12/2025"
product_version: "9.1.0.30636"
---

# Managing Company Tenants


Each cloud tenant in Veeam Service Provider Console has one Company Tenant user. A Company Tenant acts on behalf of a cloud tenant that consumes provided services.

Credentials of a Company Tenant are required to:

* Connect to Veeam Service Provider Console client Veeam Backup & Replication servers
* Connect to Veeam Service Provider Console management agents running on client computers that are protected with Veeam backup agents
* Gain access to the Veeam Service Provider Console Client Portal

|  |
| --- |
| Important! |
| After you upgrade Veeam Service Provider Console to version 9, cloud tenants will be created automatically for all managed companies. In this case, Company Tenant will have the same credentials as Company Owner.  To avoid access issues because of overlapping credentials, we recommend that you change the password for the Company Owner. For details, see [Modifying Company Owner Password](manage_company_owners.md#password). |

Creating Company Tenant

Veeam Service Provider Console creates a Company Tenant when you map a cloud tenant to a Veeam Service Provider Console company. For details, see [Configuring Cloud Tenant Mapping](assign_cloud_tenants.md).

You can create cloud tenants in Veeam Service Provider Console, or register cloud tenant accounts in Veeam Cloud Connect. For details, see sections [Creating Cloud Tenants in Veeam Service Provider Console](create_tenant_in_vspc.md) and [Creating Cloud Tenant Accounts in Veeam Cloud Connect](create_tenant_in_cloud.md).

Modifying Company Tenant Password

You can modify a password for an already existing cloud tenant:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Choose to edit a cloud tenant and navigate to the Tenant Info step of the wizard.
6. Change the password for the user who acts as a Company Tenant.
7. Save changes.

For details on modifying a cloud tenant, see [Modifying Cloud Tenant Settings](modify_cloud_tenants.md).

|  |
| --- |
| Note: |
| When modifying the Company Tenant password, consider that the password change is applied immediately, without waiting for any running tasks to complete. If you modify the password while client's backup to cloud, backup copy to cloud or replication to cloud jobs are still running, these jobs will fail because of lost connection to cloud repositories and hosts. |

Modifying Company Tenant Info

You can modify general Company Tenant details:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. Open the Managed Companies tab and navigate to Local Users.
4. To display Company Tenants, in the Role filter select Company Tenant.
5. Select the necessary user and click Edit.
6. Modify user settings as described in [Creating Company Administrators](create_company_admins.md).

You can modify all settings except the user name.

1. Save changes.

Disabling and Deleting Company Tenant

Credentials of a Company Tenant are specified in a cloud tenant account. When you disable or delete a cloud tenant account, the Company Tenant user is disabled or deleted along with it.

For details, see [Disabling and Enabling Cloud Tenants](enable_disabe_cloud_tenants.md) and [Removing Cloud Tenants](remove_cloud_tenants.md).


