---
title: "Removing Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_remove_mapping.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Mapping


If you want to stop managing licenses assigned to the company in VCSP Pulse, you can remove mapping. Note that if you remove mapping from a parent company, all merged companies will be split automatically.

To remove mapping:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display the list of all companies managed in VCSP Pulse or Veeam Service Provider Console.

1. From the list of companies, select one or more mapped companies.

To narrow down the list of companies, you can apply the following filters:

* Company Name — search companies by name configured in Veeam Service Provider Console or VCSP Pulse.
* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.
* Status — limit the list of companies by mapping status (Mapped, Unmapped, Creating, Error, All).
* Company Source Type — limit the list of companies by source (VCSP Pulse, Veeam Service Provider Console, All).

1. At the top of the list, click Mapping and select Remove.
2. In the Remove Mapping window, click Yes.


