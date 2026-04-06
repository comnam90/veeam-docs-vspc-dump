---
title: "Modifying Cloud Tenant Settings"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_cloud_tenants.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Modifying Cloud Tenant Settings


You can modify settings of cloud tenant accounts.

|  |
| --- |
| Note: |
| When modifying cloud tenant account settings, consider the following:   * If you modify a user name or password, the cloud tenant will need to reconnect to the service provider in Veeam Backup & Replication to regain access to allocated cloud resources. The service provider must also rename Veeam Cloud Connect tenant account and the folder with tenant backups on the cloud repository to continue the backup chain that already exists on the cloud backup repository. For details, see section [Renaming Tenant Accounts](https://helpcenter.veeam.com/docs/backup/cloud/renaming_user_accounts.html) of the Veeam Cloud Connect Guide.  * All changes are applied immediately, without waiting for any running tasks to complete. For example, if you enable traffic throttling while cloud tenant's jobs are still running, Veeam Service Provider Console will throttle all cloud tenant's running jobs. |

Modifying Cloud Tenant Settings

To modify cloud tenant account settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Select the necessary cloud tenant in the list.

To narrow down the list of cloud tenants, you can apply the following filters:

* Cloud Tenant Name — search the list of cloud tenants by name.
* VSPC Company Name — search the list of cloud tenants by mapped VSPC company name.
* Tenant type — limit the list of cloud tenants by type (Native, Cloud Director).
* Mapping status — limit the list of cloud tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Edit.

Alternatively, you can right-click the necessary cloud tenant and choose Edit.

1. Modify cloud tenant account settings as described in [Creating Cloud Tenants](create_cloud_tenant.md).
2. Save changes.


