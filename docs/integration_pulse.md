---
title: "Integration with VCSP Pulse"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_pulse.html"
last_updated: "8/20/2025"
product_version: "9.1.0.30636"
---

# Integration with VCSP Pulse


Veeam Service Provider Console offers integration with VCSP Pulse to facilitate license management.

Integration allows you to create and manage VCSP Pulse license keys in Veeam Service Provider Console and assign license keys internally or to client companies and resellers without accessing VCSP Pulse portal.

This solution is intended for service providers who:

* Use Veeam Service Provider Console to manage and monitor data protection operations and services.
* Have [Veeam ProPartner Program](https://propartner.veeam.com/) membership.
* Use VCSP Pulse for license management and usage reporting.

This section assumes that you have a good understanding of VCSP Pulse.

Integration Features

To provide integration with VCSP Pulse, Veeam Service Provider Console uses a predefined application plugin. The plugin allows two applications to communicate with each other through integration features — integration points that allow bidirectional synchronization of data.

VCSP Pulse plugin includes the following integration features:

* Company Management is the primary integration feature that allows you to select companies whose data you want to share between Veeam Service Provider Console and VCSP Pulse. After you enable this feature, Veeam Service Provider Console retrieves a list of managed companies from VCSP Pulse. You can then configure mapping to synchronize data about managed companies and enable further integration.
* License Key Management feature allows you to create license keys in VCSP Pulse for products managed in Veeam Service Provider Console. After you enable this feature, Veeam Service Provider Console retrieves a list of license keys from VCSP Pulse. You can then create new license keys and manage license keys created in VCSP Pulse.

In This Section

* [Enabling VCSP Pulse Integration](pulse_enable_integration.md)
* [Configuring Companies Integration](pulse_companies.md)
* [Managing License Keys](pulse_license_keys.md)
* [Synchronizing Data](pulse_synchronize_data.md)


