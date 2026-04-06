---
title: "Managing Veeam ONE"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_one.html"
last_updated: "9/12/2025"
product_version: "9.1.0.30636"
---

# Managing Veeam ONE


Veeam Service Provider Console allows you to manage Veeam ONE servers located in client and hosted infrastructures and monitor alarms triggered on these servers.

To manage Veeam ONE servers, you must complete the following steps:

1. [Install Veeam ONE servers on discovered computers](one_install.md) or connect Veeam ONE servers to Veeam Service Provider Console using one of the following ways:

* [Deploy Veeam Service Provider Console management agents](deploy_management_agents.md) on computers hosting Veeam ONE servers.
* [For hosted infrastructure] [Connect Veeam ONE servers](one_connect_servers.md) in Veeam Service Provider Console plugin.

1. [Enable alarms synchronization for managed Veeam ONE servers](enable_disable_alarm_sync.md).

You can enable alarms data collection for connected Veeam ONE servers to manage in Veeam Service Provider Console alarms triggered on these servers.

1. [Charge for backup services](billing.md).

You can charge for monitoring services you provide with Veeam ONE and send invoices to clients with details on the services they consume.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator, Read-only User.

Read-only Users can only view and export Veeam ONE server details.

Portal Operators cannot connect Veeam ONE servers in the Veeam Service Provider Console plugin.


