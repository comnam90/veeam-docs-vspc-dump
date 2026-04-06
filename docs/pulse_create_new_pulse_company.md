---
title: "Creating New Companies in VCSP Pulse"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_create_new_pulse_company.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Creating New Companies in VCSP Pulse


You can create companies in VCSP Pulse based on contact data from accounts of companies managed in Veeam Service Provider Console.

When you create a new company, VCSP Pulse:

1. Retrieves company id and general company data from Veeam Service Provider Console.
2. Creates a company based on retrieved information and maps it automatically to a source company in Veeam Service Provider Console.

Creating Companies

To create new companies in VCSP Pulse:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Companies.

Veeam Service Provider Console will display a list of all companies managed in VCSP Pulse and Veeam Service Provider Console.

1. From the list of companies, select unmapped Veeam Service Provider Console companies for which you want to create companies in VCSP Pulse.

To narrow down the list of companies, you can apply the following filters:

* Company Name — search companies by name configured in Veeam Service Provider Console or VCSP Pulse.
* Site — limit the list of companies by Veeam Cloud Connect server on which the company is registered.
* Status — limit the list of companies by mapping status (Mapped, Unmapped, Creating, Error, All).
* Company Source Type — limit the list of companies by source (VCSP Pulse, Veeam Service Provider Console, All).

1. At the top of the list, click Create Company and choose In VCSP Pulse.

Enabling Automatic Creation of New Companies in VCSP Pulse

You can configure Veeam Service Provider Console to create new companies in VCSP Pulse automatically:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click Companies.
5. At the top of the list, set the Company Creation in VCSP Pulse toggle to On.

After you enable this option, Veeam Service Provider Console will automatically create companies in VCSP Pulse for each company created in Veeam Service Provider Console. Note that this option will affect only companies created after the toggle was enabled.


