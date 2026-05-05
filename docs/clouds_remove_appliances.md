---
title: "Removing Appliances"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_remove_appliances.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Removing Appliances


To remove appliances:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.

To narrow down the list of appliances, you can apply the following filters:

* Backup Appliance — search the list of appliances by server name.
* Company — search the list of appliances by company name.
* Status — limit the list of appliances by status (Healthy, Unavailable, Warning, Unknown).
* Platform — limit the list of appliances by platform (Amazon Web Services, Microsoft Azure, Google Cloud).
* Appliance deployment — limit the list of appliances by certificate status (Verified, Unverified).
* Managed company — limit the list of appliances by configured client company (Assigned, Not assigned).

1. Select the necessary appliances in the list.
2. Click Remove.
3. In the confirmation window, select if you want to remove cloud infrastructure resources associated with the appliance:

* [For hosted appliances] To remove the appliance and cloud infrastructure resources associated with the appliance, click Remove Appliance and Cloud Resources.
* To disconnect the appliance from Veeam Service Provider Console and Veeam Cloud Connect without removing cloud infrastructure resources, click Remove Appliance.


