---
title: "Managing Veeam Backup for Microsoft 365"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/manage_vbo_servers.html"
last_updated: "4/23/2026"
product_version: "9.2.0.33215"
---

# Managing Veeam Backup for Microsoft 365


Veeam Service Provider Console allows you to create and manage Veeam Backup for Microsoft 365 jobs and monitor Veeam Backup for Microsoft 365 servers.

To manage Veeam Backup for Microsoft 365 jobs, you must complete the following steps:

1. Connect Veeam Backup for Microsoft 365 servers to Veeam Service Provider Console using one of the following ways:

* [Deploy Veeam Service Provider Console management agents](deploy_management_agents.md) on computers hosting Veeam Backup for Microsoft 365 servers.

* Contact your service provider for Veeam Backup for Microsoft 365 servers and repositories assignment.

1. [Activate connected Veeam Backup for Microsoft 365 servers](activate_vbo_servers.md).

To manage Veeam Backup for Microsoft 365 servers, you must install and activate Veeam Backup for Microsoft 365 REST API and PowerShell on connected servers.

1. [Register Microsoft 365 organizations](vbo_organizations.md).

You can register new Microsoft 365 organizations in Veeam Service Provider Console plugin.

1. [Create Veeam Backup for Microsoft 365 jobs](create_vbo_jobs.md).

To protect managed Microsoft 365 workloads, you can configure backup and backup copy jobs on Veeam Backup for Microsoft 365 servers.

1. [Manage Veeam Backup for Microsoft 365 jobs](manage_vbo_jobs.md).

To administer data protection operations in Microsoft 365 environment, you can modify, start, stop, enable and disable jobs configured on Veeam Backup for Microsoft 365 servers.

To access Veeam Backup for Microsoft 365 management, you must have at least one Veeam Backup for Microsoft 365 server in your infrastructure or at least one Veeam Backup for Microsoft 365 server allocated to you by your service provider.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator, Location User.

Location User can only view and export Veeam Backup for Microsoft 365 jobs, servers and protected workloads details.


