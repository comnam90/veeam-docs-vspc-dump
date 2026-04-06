---
title: "Removing Cloud Tenants"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_cloud_tenants.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Cloud Tenants


If you no longer provide backup services to a company, you can remove an cloud tenant account registered for this company.

|  |
| --- |
| Note: |
| When you remove a cloud tenant account, consider the following:   * Veeam Service Provider Console management agents on all machines that belong to the cloud tenant will be assigned the Unverified connection status. You will have to verify the connection manually. For details, see [Setting Cloud Tenant to Management Agents](set_cloud_tenant.md). * All Veeam backup agents that belong to the cloud tenant will be switched to the Unmanaged mode (Free mode). * All cloud tenant VM replicas on the cloud host will be unregistered and actual replica files will be deleted from the datastore or volume. * If cloud tenant backup copy and replication jobs used WAN accelerators, data for the cloud tenant will be deleted from the global cache on the target WAN accelerator. |

Removing Cloud Tenants

To remove a cloud tenant account:

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

1. At the top of the list, click Remove.

Alternatively, you can right-click the necessary cloud tenant and choose Remove.

1. In the confirmation window, do one of the following:

* If the cloud tenant does not have allocated cloud resources, click Yes.
* If the cloud tenant has allocated cloud resources, select the necessary option:

* Click Yes to remove cloud tenant account and delete all cloud tenant backup data from the cloud repository.
* Click No to remove cloud tenant account and leave cloud tenant backup data intact.


