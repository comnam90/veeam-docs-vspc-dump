---
title: "Integration with Veeam Backup & Replication"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/integration_vbr.html"
last_updated: "8/20/2025"
product_version: "9.1.0.30636"
---

# Integration with Veeam Backup & Replication


Veeam Service Provider Console offers integration with Veeam Backup & Replication. Integration allows you to allocate hosted Veeam Backup & Replication resources to client companies and create backup jobs for client companies on hosted Veeam Backup & Replication servers.

Integration offers the following capabilities:

* Allocating hosted Veeam Backup & Replication resources. You can allocate Veeam Backup & Replication servers and repositories hosted in your infrastructure to client companies.
* Creating client backup jobs. You and client company users can configure client backup jobs on hosted Veeam Backup & Replication servers.

This solution is intended for service providers who:

* Use Veeam Service Provider Console to manage and monitor license usage data.
* Manage client companies who does not have Veeam Backup & Replication servers in their infrastructure.
* Use Veeam Backup & Replication to back up virtual infrastructure workloads.

Before You Begin

To allocate Veeam Backup & Replication resources to client companies, you must deploy Veeam Service Provider Console management agents on hosted computers. You can install management agents as part of the discovery process in hosted infrastructure, or deploy management agents on computers hosting Veeam Backup & Replication servers manually. For details on configuring discovery rules, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md). For details on deploying management agents manually, see [Deploying Management Agents Manually](deploy_management_agents.md).

Alternatively, you can connect Veeam Backup & Replication servers in plugin or install Veeam Backup & Replication on hosted computers. For details, see sections [Connecting Veeam Backup & Replication Servers](vbr_connect_servers.md) and [Installing Veeam Backup & Replication](vbr_install.md).

This section assumes that you have a good understanding of Veeam Backup & Replication.

|  |
| --- |
| Note: |
| Integration with Veeam Service Provider Console is available for Veeam Backup & Replication version 12.1 or later.  Make sure you have enabled Veeam Backup & Replication REST API access. |

Related Topics

* [Managing Veeam Backup & Replication](manage_vbr.md)
* [Downloading Logs from Veeam Backup & Replication Servers](download_client_server_logs.md)


