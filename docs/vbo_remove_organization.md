---
title: "Removing Microsoft 365 Organizations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_remove_organization.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Microsoft 365 Organizations


You can remove registered Microsoft 365 organizations from Veeam Service Provider Console and Veeam Backup for Microsoft 365. In this case, all backup and backup copy jobs configured for the removed organization will be deleted. Backed up data will remain on backup repositories and data on consumed licenses will not be affected.

To remove an organization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Microsoft 365 plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display the list of all organizations managed in Veeam Backup for Microsoft 365 and all companies managed in Veeam Service Provider Console.

1. To narrow down the list of companies and organizations, you can apply the following filters:

* Microsoft 365 Organization Name — search organizations by name configured in Veeam Backup for Microsoft 365.
* VSPC Company Name — search companies by name configured in Veeam Service Provider Console.
* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.
* Backup server — limit the list of organizations by name of the server on which Veeam Backup for Microsoft 365 is deployed.
* Status — limit the list of companies and organizations by mapping status (Mapped, Not mapped, Creating, Error).
* Company source type — limit the list of companies and organizations by source type (Veeam Backup for Microsoft 365, Veeam Service Provider Console).

1. From the list of companies, select the necessary organization.
2. At the top of the list, click Remove Organization.

Alternatively, you can right-click the necessary organization and choose Remove.

1. In the confirmation window, click Remove.


