---
title: "Integration with Veeam Backup for Microsoft 365"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_vbo.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Integration with Veeam Backup for Microsoft 365


Veeam Service Provider Console offers integration with Veeam Backup for Microsoft 365 to manage Veeam Backup for Microsoft 365 jobs and restore protected Microsoft 365 objects from Veeam Service Provider Console portal. Integration also allows you to monitor the state of protected Microsoft 365 workloads and consolidate license usage data in one place.

Integration offers the following capabilities:

* Organizations management. You can create and manage Microsoft 365 organizations from Veeam Service Provider Console web portal.
* Job management. You can create and manage jobs on hosted and client Veeam Backup for Microsoft 365 servers from Veeam Service Provider Console portal.
* Data restore. You can access Veeam Backup for Microsoft 365 Restore Portal from Veeam Service Provider Console to restore data of backed up Microsoft 365 organizations.
* Consolidated billing and reporting. You can view information on protected Microsoft 365 objects in Veeam Service Provider Console Protected Microsoft 365 Objects report and charge for allocated services.
* License management and usage reporting. You can install and update Veeam Backup for Microsoft 365 licenses from Veeam Service Provider Console portal and consolidate information about licenses consumed by managed Veeam Backup for Microsoft 365 servers in Veeam Service Provider Console license usage reports.

This solution is intended for service providers who:

* Use Veeam Service Provider Console to manage and monitor license usage data.
* Manage client companies who does not have Veeam Backup for Microsoft 365 servers in their infrastructure.
* Use Veeam Backup for Microsoft 365 to back up and restore data of Microsoft 365 organizations.

This section assumes that you have a good understanding of Veeam Backup for Microsoft 365.

|  |
| --- |
| Note: |
| * To manage Veeam Backup for Microsoft 365 servers in Veeam Service Provider Console, you must deploy Veeam Service Provider Console management agents on client and hosted computers. You can install management agents as part of the discovery process in client or hosted infrastructure or deploy management agents on computers hosting Veeam Backup for Microsoft 365 servers manually. For details on configuring discovery rules, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md). For details on deploying management agents manually, see [Deploying Management Agents Manually](deploy_management_agents.md).   Alternatively, you can connect hosted Veeam Backup for Microsoft 365 servers in Veeam Service Provider Console plugin. For details, see [Connecting Veeam Backup for Microsoft 365 Servers](vbo_connect_servers.md).   * Integration with Veeam Service Provider Console is available for Veeam Backup for Microsoft 365 version 6 or later. Veeam Backup for Microsoft 365 jobs management, organization management, reporting and restore are available for Veeam Backup for Microsoft 365 version 7 or later. |

Integration Features

To provide integration with Veeam Backup for Microsoft 365, Veeam Service Provider Console uses a predefined application plugin. The plugin allows the applications to communicate with each other through integration features — integration points that allow data synchronization.

Veeam Backup for Microsoft 365 plugin includes the following integration features:

* Company Mapping feature allows you to select Microsoft 365 organizations which you want to map to Veeam Service Provider Console companies to differentiate Veeam Backup for Microsoft 365 jobs, protected objects and consumed licenses.
* License Usage Reporting feature allows you to include information about license usage for client and hosted Veeam Backup for Microsoft 365 servers in Veeam Service Provider Console license usage reports. This feature is enabled by default.

Related Topics

* [Downloading Logs from Veeam Backup for Microsoft 365 Servers](vbo_server_logs.md)

* [Viewing and Exporting Veeam Backup for Microsoft 365 Server Details](export_vbo_details.md)


