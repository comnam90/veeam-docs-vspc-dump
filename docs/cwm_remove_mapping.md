---
title: "Removing Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/cwm_remove_mapping.html"
last_updated: "8/20/2025"
product_version: "9.1.0.30636"
---

# Removing Mapping


If you want to stop sending data about services consumed by the company to ConnectWise Manage, you can remove mapping:

|  |
| --- |
| Note: |
| When you remove mapping for a company, consider that:   * All configurations with the Veeam Managed Computer type created for the company by Veeam Service Provider Console will be deleted from ConnectWise Manage. * All unresolved tickets created for the company by Veeam Service Provider Console will be closed in ConnectWise Manage. |

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the ConnectWise Manage plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display the list of all companies managed in ConnectWise Manage.

1. To narrow down the list of companies, you can apply the following filters:

* Company name — search companies by name configured in ConnectWise Manage.
* Type — limit the list of companies by type configured in ConnectWise Manage.

* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.

* Status — limit the list of companies by mapping status (Mapped, Unmapped, Creating, Error).

1. From the list of companies, select one or more mapped companies.
2. At the top of the list, click Remove Mapping.
3. In the Remove Mapping window, click Yes.


