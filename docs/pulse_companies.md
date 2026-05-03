---
title: "Configuring Companies Integration"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_companies.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Configuring Companies Integration


You can select companies whose data you want to share between Veeam Service Provider Console and VCSP Pulse. To start sharing data of managed companies, you must configure mapping in Veeam Service Provider Console. Mapping triggers synchronization of companies contact information, and enables further integration.

Prerequisites

Before configuring integration of managed companies, check the following prerequisites:

* Configure VCSP Pulse Plugin connection. For details, see [Configure Plugin Connection](pulse_connect_plugin.md).
* Enable the Company Management integration feature. For details, see [Enable Integration Features](pulse_enable_features.md).

Configuring Companies Integration

To configure integration between companies in Veeam Service Provider Console and VCSP Pulse, you can do either of the following:

* [Create new companies in Veeam Service Provider Console](pulse_create_new_company.md).

Use this method if you want to create company accounts in Veeam Service Provider Console and tenant accounts in Veeam Cloud Connect for companies that you already manage in VCSP Pulse.

* [Create new companies in VCSP Pulse](pulse_create_new_pulse_company.md).

Use this method if you want to create company accounts in VCSP Pulse for companies that you already manage in Veeam Service Provider Console.

* [Configure mapping between companies in VCSP Pulse and Veeam Service Provider Console](pulse_map_companies.md).

Use this method if you have company accounts registered in Veeam Service Provider Console and you want to map them to VCSP Pulse company accounts.


