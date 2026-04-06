---
title: "Managing Veeam Backup for Microsoft 365"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_vbo_servers.html"
last_updated: "8/21/2025"
product_version: "9.1.0.30636"
---

# Managing Veeam Backup for Microsoft 365


Veeam Service Provider Console allows you to create and manage Veeam Backup for Microsoft 365 jobs and monitor Veeam Backup for Microsoft 365 servers located in client and hosted infrastructures.

You can also manage hosted Veeam Backup for Microsoft 365 servers and configure Microsoft 365 organizations synchronization using Veeam Service Provider Console plugin for Veeam Backup for Microsoft 365. For details, see [Integration with Veeam Backup for Microsoft 365](integration_vbo.md). Veeam Service Provider Console supports managing both hosted and client Veeam Backup for Microsoft 365 servers at the same time.

To manage Veeam Backup for Microsoft 365 jobs, you must complete the following steps:

1. Connect Veeam Backup for Microsoft 365 servers to Veeam Service Provider Console using one of the following ways:

* [Deploy Veeam Service Provider Console management agents](deploy_management_agents.md) on computers hosting Veeam Backup for Microsoft 365 servers.
* [Connect hosted Veeam Backup for Microsoft 365 servers](vbo_connect_servers.md) in Veeam Service Provider Console plugin.

1. [Activate connected Veeam Backup for Microsoft 365 servers](activate_vbo_servers.md).

To manage Veeam Backup for Microsoft 365 servers, you must install and activate Veeam Backup for Microsoft 365 REST API and PowerShell on connected servers.

1. [Assign Veeam Backup for Microsoft 365 resources](allocate_microsoft_365_resources.md) to client companies.
2. [Configure company mapping in Veeam Service Provider Console plugin](vbo_companies.md).

You can create new companies in Veeam Service Provider Console, register new Microsoft 365 organizations or configure company mapping between Veeam Service Provider Console and Veeam Backup for Microsoft 365.

1. [Create Veeam Backup for Microsoft 365 jobs](create_vbo_jobs.md).

To protect managed Microsoft 365 organizations, you can configure backup and backup copy jobs on client and hosted Veeam Backup for Microsoft 365 servers.

1. [Manage Veeam Backup for Microsoft 365 jobs](manage_vbo_jobs.md).

To administer data protection operations in Microsoft 365 environment, you can modify, start, stop, enable and disable jobs configured on client and hosted Veeam Backup for Microsoft 365 servers.

1. [Charge for backup services](billing.md).

You can charge for backup services you provide with Veeam Backup for Microsoft 365 and Veeam Service Provider Console, send invoices to clients with details on services they consume.

To access Veeam Backup for Microsoft 365 management, you must have at least one Veeam Backup for Microsoft 365 server in the hosted or client infrastructure.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator, Read-only User.

Read-only User can only view and export Veeam Backup for Microsoft 365 jobs, servers and protected objects details.


