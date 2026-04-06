---
title: "Removing Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbr_remove_vcd_mapping.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Mapping


If you want to stop managing VMware Cloud Director jobs and protected VMware Cloud Director objects, you can remove company mapping:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup & Replication plugin tile.
4. In the menu on the left, click Mappings.

Veeam Service Provider Console will display the list of all managed in VMware Cloud Director organizations.

1. To narrow down the list of companies, you can apply the following filters:

* Company — search companies by name configured in Veeam Service Provider Console.
* Organization — search organizations by name configured in VMware Cloud Director.
* Status — limit the list of companies and organizations by mapping status (Mapped, Not mapped).

1. From the list of companies, select one or more mapped organizations.
2. At the top of the list, click Remove Mapping.
3. In the Remove Mapping window, click Yes.

After you remove a VMware vSphere tag from a company, you will not be able to create new VMware Cloud Director jobs for this company or edit previously created jobs.


