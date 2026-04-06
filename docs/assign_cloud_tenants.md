---
title: "Configuring Cloud Tenant Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/assign_cloud_tenants.html"
last_updated: "12/8/2025"
product_version: "9.1.0.30636"
---

# Configuring Cloud Tenant Mapping


To provide cloud resources to client companies, you must map a cloud tenant to the client company. You can map several cloud tenants to one Veeam Service Provider Console company.

|  |
| --- |
| Note: |
| If you map a VMware Cloud Director cloud tenant to a company and allocate to this company the Veeam Backup & Replication server where a VMware Cloud Director organization is registered, Veeam Service Provider Console will automatically map this company to the VMware Cloud Director organization. |

Before You Begin

To assign Veeam Cloud Connect resources to a company, you must enable cloud services for this company. For details, see [Step 6. Enable Cloud Services](enable_company_cloud.md).

Mapping Cloud Tenants

To map cloud tenants to a client company:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Select one or more cloud tenants in the list.

To narrow down the list of cloud tenants, you can apply the following filters:

* Cloud Tenant Name — search the list of cloud tenants by name.
* VSPC Company Name — search the list of cloud tenants by mapped VSPC company name.
* Tenant type — limit the list of cloud tenants by type (Native, Cloud Director).
* Mapping status — limit the list of cloud tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Map to.

Alternatively, you can right-click the necessary cloud tenant and choose Map to.

1. In the Company Mapping window, select a Veeam Service Provider Console company to which you want to map cloud tenants.
2. Click OK.
3. [For companies managed by resellers] In the confirmation window, click Yes.

Removing Cloud Tenant Mapping

To remove mapping:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Tenants.
5. Select one or more cloud tenants in the list.

To narrow down the list of cloud tenants, you can apply the following filters:

* Cloud Tenant Name — search the list of cloud tenants by name.
* VSPC Company Name — search the list of cloud tenants by mapped VSPC company name.
* Tenant type — limit the list of cloud tenants by type (Native, Cloud Director).
* Mapping status — limit the list of cloud tenants by mapping status (Mapped, Not mapped).

1. At the top of the list, click Remove Mapping.

Alternatively, you can right-click the necessary cloud tenant and choose Remove Mapping.

1. In the confirmation window, click Yes.


