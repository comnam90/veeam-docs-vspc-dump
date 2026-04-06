---
title: "Merging Companies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_merge_companies.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Merging Companies


A client company may run multiple Veeam backup agents, Veeam ONE, Veeam Backup for Microsoft 365, Veeam Backup & Replication and Veeam Backup Enterprise Manager servers located in different remote offices and branch offices (ROBO). To aggregate licenses consumed by each company office in one place, you can merge branch offices to one parent company, mapped to a VCSP Pulse company. In this case, VCSP Pulse will assign license keys only to the parent company. These license keys will be available to all merged companies.

Prerequisites

Before merging companies, configure mapping between at least one Veeam Service Provider Console company and VCSP Pulse company. For details, see [Configuring Companies Integration](pulse_companies.md#mapping).

Merging Companies

To merge companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display the list of all companies managed in VCSP Pulse or Veeam Service Provider Console.

1. From the list of companies, select one mapped company (parent company) and one or more unmapped Veeam Service Provider Console companies.

To narrow down the list of companies, you can apply the following filters:

* Company Name — search companies by name configured in Veeam Service Provider Console or VCSP Pulse.
* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.
* Status — limit the list of companies by mapping status (Mapped, Unmapped, Creating, Error, All).
* Company Source Type — limit the list of companies by source (VCSP Pulse, Veeam Service Provider Console, All).

1. At the top of the list, click Merge Options and select Merge.

After you merge branch companies, their status will change to Mapped and the value in the Parent Company column will display the parent company name.

Splitting Companies

If you want to stop managing multiple Veeam Service Provider Console companies as one VCSP Pulse company, you can split merged companies. After you split companies, you will be able to manage branch companies as separate companies. Branch companies will lose access to licenses assigned to parent company. Licenses downloaded by branch companies before split will not be affected.

To split previously merged companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display the list of all companies managed in VCSP Pulse or Veeam Service Provider Console.

1. From the list of companies, select companies mapped to one parent company.

To narrow down the list of companies, you can apply the following filters:

* Company Name — search companies by name configured in Veeam Service Provider Console or VCSP Pulse.
* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.
* Status — limit the list of companies by mapping status (Mapped, Unmapped, Creating, Error, All).
* Company Source Type — limit the list of companies by source (VCSP Pulse, Veeam Service Provider Console, All).

1. At the top of the list, click Merge Options and select Split.


