---
title: "Integration with Veeam ONE"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_one.html"
last_updated: "7/17/2024"
product_version: "9.1.0.30636"
---

# Integration with Veeam ONE


Veeam Service Provider Console offers integration with Veeam ONE to monitor licenses consumed by managed Veeam ONE servers and consolidate license usage data in one place. Integration also allows synchronizing alarms between Veeam ONE and Veeam Service Provider Console.

Integration offers the following capabilities:

* Consolidated monitoring. You can consolidate information about licenses consumed by client and hosted Veeam ONE servers in Veeam Service Provider Console license usage reports.
* Alarms data collection. You can enable alarms data collection to synchronize alarms between Veeam ONE and Veeam Service Provider Console and manage alarms triggered on client and hosted Veeam ONE servers in Veeam Service Provider Console web portal.
* License management. You can install, delete and update Veeam ONE licenses from Veeam Service Provider Console web portal.

This solution is intended for service providers who:

* Use Veeam Service Provider Console to manage and monitor license usage data.
* Manage client companies who have Veeam ONE servers in their infrastructure.
* Use Veeam ONE to monitor own virtual and backup infrastructure.

This section assumes that you have a good understanding of Veeam ONE.

|  |
| --- |
| Note: |
| * To manage Veeam ONE servers in Veeam Service Provider Console, you must deploy Veeam Service Provider Console management agents on client and hosted computers. For details on deploying management agents, see [Deploying Management Agents Manually](deploy_management_agents.md).  * Integration with Veeam Service Provider Console is available for Veeam ONE version 11a or later. |

Integration Features

To provide integration with Veeam ONE, Veeam Service Provider Console uses a predefined application plugin. The plugin allows two applications communicate with each other through integration features — integration points that allow bidirectional synchronization of data.

Veeam ONE plugin includes the License Usage Reporting integration feature, that allows you to include information about license usage for client and hosted Veeam ONE servers in Veeam Service Provider Console license usage reports. This feature is enabled by default.

Related Topics

* [Downloading Logs from Veeam ONE Servers](one_server_logs.md)

* [Viewing and Exporting Veeam ONE Server Details](view_one_details.md)


