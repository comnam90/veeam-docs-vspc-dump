---
title: "License Usage Statistics"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/usage_logging.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# License Usage Statistics


When license auto update is enabled, Veeam Service Provider Console additionally performs automatic usage reporting.

As a part of reporting, Veeam Service Provider Console collects statistics on the current license usage and sends it periodically to the Veeam License Update Server. The report provides information about the contract ID, license ID, product installation ID, the maximum number of workloads managed by client Veeam Backup & Replication servers over the past week (high watermark), the maximum number of Veeam backup agents managed in Veeam Service Provider Console, the number of backups and replicas stored in the cloud, the maximum number of objects managed by Veeam ONE servers and the maximum number of protected Veeam Backup for Microsoft 365 users. The process runs in the background mode once a week, at a random time and day.

The collected data does not include information on the usage of Veeam Service Provider Console or Veeam products by any individual person identifiable for Veeam, or any data protected with or monitored by Veeam products.

Veeam may also use collected data for any other internal business purposes it deems appropriate, including (but not limited to) evaluation, improvement and optimization of Veeam licensing models.

|  |
| --- |
| Important! |
| Even after you have enabled automatic license update and Veeam Service Provider Console has started sending usage statistics, you are still required to submit license usage to your aggregator. For details, see section [Submitting License Usage](https://helpcenter.veeam.com/docs/vcsp/refguide/using_vcsp_pulse.html#submitting-license-usage) of the Veeam Rental Licensing and Usage Reporting Reference Guide. |

Automatic license update is required for automatic license reporting. For details on how to enable automatic license reporting, see section [Automatic License Reporting](https://helpcenter.veeam.com/docs/vcsp/refguide/automatic_license_reporting.html) of the Veeam Rental Licensing and Usage Reporting Reference Guide.

By enabling license auto update, automatic license reporting and sending usage statistics you agree with collection, transmission and use of the license usage data. You must not enable automatic license update in case you do not agree with such collection, transmission and use.

Related Topics

[Updating Veeam Service Provider Console License](update_vac_license.md)


