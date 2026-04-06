---
title: "Enabling and Disabling Maintenance Mode for Veeam Cloud Connect"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_cloud_maintenance_mode.html"
last_updated: "8/19/2025"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Maintenance Mode for Veeam Cloud Connect


In Veeam Service Provider Console, you can enable and disable maintenance mode for the Veeam Cloud Connect server that is deployed as part of the solution.

In some cases, you may need to perform service actions with the Veeam Cloud Connect, for example, upgrade a server whose resources are consumed by cloud tenants. Such operations may require that cloud resources become temporarily unavailable to cloud tenants, and cloud tenant activities are temporarily put on hold. Before starting the necessary service actions, you can put the Veeam Cloud Connect server to the maintenance mode to prepare your cloud infrastructure for maintenance.

The maintenance mode functionality allows you to do the following:

* Gracefully stop currently running backup and backup copy jobs targeted at cloud repositories.

After you put the Veeam Cloud Connect server to the maintenance mode, Veeam Backup & Replication checks the status of client jobs targeted at the cloud infrastructure. If a Veeam Backup & Replication backup or backup copy job or Veeam backup agent job is running, Veeam Cloud Connect will allow the currently running task to complete. All subsequent tasks for the job will fail. This helps make sure that backed-up data pertaining to a certain VM, VM disk or computer is successfully transferred to the cloud repository before you start service actions in the Veeam Cloud Connect infrastructure.

* Prevent cloud tenant backup and backup copy jobs from starting.

If a cloud tenant starts a backup or backup copy job in Veeam Backup & Replication, or a backup job in Veeam backup agent at the time when the Veeam Cloud Connect server is operating in the maintenance mode, the job will fail.

* Notify companies about maintenance in the cloud infrastructure.

In the statistics window of a client job that completes with the Failed status at the time when the Veeam Cloud Connect server is operating in the maintenance mode, an error message will be displayed informing that the Veeam Cloud Connect server is under maintenance. By default, an error message contains the following maintenance mode notification: 'Service provider is currently undergoing scheduled maintenance'.

For details on the maintenance mode, see section [Maintenance Mode](https://helpcenter.veeam.com/docs/backup/cloud/cc_maintenance_mode.html) of the Veeam Cloud Connect Guide.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator, Site Administrator.

Enabling Maintenance Mode for Veeam Cloud Connect

To enable maintenance mode for Veeam Cloud Connect:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select a Veeam Cloud Connect server, click Maintenance Mode and select Enable.

Alternatively, you can right-click the necessary Veeam Cloud Connect server, choose Maintenance Mode and select Enable.

1. In the displayed dialog box, click Yes to confirm the operation.

Disabling Maintenance Mode for Veeam Cloud Connect

To disable maintenance mode for Veeam Cloud Connect:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Cloud Connect plugin tile.
4. In the menu on the left, click Servers.
5. Select the Veeam Cloud Connect server, click Maintenance Mode and select Disable.

Alternatively, you can right-click the necessary Veeam Cloud Connect server, choose Maintenance Mode and select Disable.


