---
title: "Integration with ConnectWise Manage"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_cwm.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Integration with ConnectWise Manage


Veeam Service Provider Console offers built-in integration with ConnectWise Manage to combine the functionality of both products and consolidate client data in one place.

Integration offers the following capabilities:

* Consolidated billing. You can consolidate information about services consumed by the clients into a single invoice in ConnectWise Manage.

* Automated ticketing. You can automatically create service tickets in ConnectWise Manage based on Veeam Service Provider Console alarms.

This solution is intended for service providers who both:

* Use Veeam Service Provider Console to manage and monitor data protection operations and services
* Use ConnectWise Manage as the primary business management platform

This section assumes that you have a good understanding of ConnectWise Manage.

Integration Features

To provide integration with ConnectWise Manage, Veeam Service Provider Console uses a predefined application plugin. The plugin allows two applications to communicate with each other through integration features — integration points that allow bidirectional synchronization of data.

ConnectWise Manage plugin includes the following integration features:

* Companies is the primary integration feature that allows you to select companies whose data you want to share between Veeam Service Provider Console and ConnectWise Manage. After you enable this feature, Veeam Service Provider Console retrieves a list of managed companies from ConnectWise Manage. You can then configure mapping to synchronize data about managed companies and enable further integration.
* Configurations feature allows you to create configurations in ConnectWise Manage for computers managed in Veeam Service Provider Console. This includes Veeam Backup & Replication servers, VMs, and physical computers that have a Veeam Service Provider Console management agent installed and that reside in the infrastructure of mapped companies. After you enable this feature, Veeam Service Provider Console creates a configuration for each managed computer with the Veeam Managed Computer configuration type.
* Ticketing feature allows you to create service tickets in ConnectWise Manage. The tickets are based on alarms triggered in Veeam Service Provider Console for a mapped company. Each service ticket contains a configuration of a managed computer associated with the triggered alarm. After you enable this feature, Veeam Service Provider Console retrieves a list of service boards available in ConnectWise Manage. You can then configure ticket creation parameters.
* Billing feature allows you to include information about type and quantity of Veeam-powered services consumed by the clients into invoices in ConnectWise Manage. After you enable this feature, Veeam Service Provider Console retrieves products from ConnectWise Manage product catalog and agreements available for mapped companies. You can then configure mapping of services and products, and select agreements which will be used to generate overall invoices.

In This Section

* [Enabling ConnectWise Manage Integration](cwm_enable_integration.md)
* [Configuring Companies Integration](cwm_companies.md)
* [Configuring Consolidated Billing](cwm_billing.md)
* [Configuring Automated Ticketing](cwm_ticketing.md)
* [Refreshing Data](cwm_refresh_data.md)


