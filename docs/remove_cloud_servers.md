---
title: "Removing Veeam Cloud Connect Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_cloud_servers.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Removing Veeam Cloud Connect Servers


If you no longer use a Veeam Cloud Connect server to provide backup services, you can remove a connection to this Veeam Cloud Connect server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. From the Veeam Cloud Connect servers list, select the server that you want to disconnect.
6. At the top of the list, click Remove and select one of the following options:

* Unregister — select this option if you want to remove from Veeam Service Provider Console data of cloud tenants registered on the Veeam Cloud Connect server.

This will uninstall Veeam Service Provider Console management agent from the Veeam Cloud Connect server, management agents installed on client computers protected with Veeam backup agent, and management agents installed on client Veeam Backup & Replication servers. Tenant accounts on the Veeam Cloud Connect server will not be deleted.

In the Unregister Cloud Connect Server window, click Unregister.

|  |
| --- |
| Important! |
| Do not select this option to troubleshoot issues with a managed Veeam Cloud Connect server. For troubleshooting, contact Veeam Customer Technical Support. For details, see [Creating Support Cases](create_support_case.md). |

* Migrate — select this option if you want to preserve in Veeam Service Provider Console data of tenants registered on the Veeam Cloud Connect server and plan to migrate Veeam Cloud Connect configuration database to another server.

This will remove the connection to Veeam Cloud Connect server but preserve Veeam Service Provider Console management agents on all computers and Veeam Backup & Replication servers of cloud tenants registered on this Veeam Cloud Connect server. All companies with cloud tenants assigned to resellers and all cloud resources from this Veeam Cloud Connect server allocated to resellers will be removed from these resellers.

In the Migrate Cloud Connect Server window, click Migrate.

For details on configuration database migration, see section [Migrating Veeam Backup & Replication to Another Backup Server](https://helpcenter.veeam.com/docs/vbr/userguide/vbr_config_migrate.html?ver=13) of the Veeam Backup & Replication User Guide.

|  |
| --- |
| Note: |
| If on the migrated server you had cloud tenants that were managed by resellers, consider the following:   * Companies with allocated cloud tenants will be unassigned from resellers. You must re-assign these companies manually. For details, see [Step 9. Assign Companies](add_reseller_companies.md). * Cloud resources from migrated Veeam Cloud Connect server will be removed from resellers. You must re-allocate these resources manually. For details, see [Step 3. Allocate Cloud Resources](allocate_cloud_reseller_quota.md).  * Backup policies configured by resellers will change ownership and will be shown in Veeam Service Provider Console as created by the service provider. Resellers must copy or re-create such backup policies. For details, see section [Configuring Backup Policies](https://helpcenter.veeam.com/docs/vac/reseller/configure_backup_policies.html?ver=9.2) of the Guide for Resellers. |


