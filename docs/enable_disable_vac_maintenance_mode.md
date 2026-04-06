---
title: "Enabling and Disabling Maintenance Mode for Veeam Service Provider Console"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_vac_maintenance_mode.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Maintenance Mode for Veeam Service Provider Console


When you perform crucial configuration changes to the Veeam Service Provider Console portal, you may need to put the portal to the maintenance mode.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Enabling Maintenance Mode for Veeam Service Provider Console

When maintenance mode is enabled for the Veeam Service Provider Console portal, users will not be able to authenticate to the portal remotely. The portal welcome page will display a message saying that the portal is undergoing maintenance, and all services are temporarily unavailable.

|  |
| --- |
| Important! |
| If you installed Veeam Service Provider Console using the distributed deployment scenario, you will not be able to upgrade Veeam Service Provider Console Web UI component when maintenance mode is enabled. |

To enable maintenance mode for Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Server Settings.
3. At the top, open the Maintenance Mode tab.
4. Set the Backup portal maintenance mode toggle to On.
5. In the Maintenance Mode window, click Yes.

[![Enable Maintenance Mode](images/enable_maintenance_sp.webp)](images/enable_maintenance_sp.webp "Enable Maintenance Mode")

Disabling Maintenance Mode for Veeam Service Provider Console

To disable maintenance mode for Veeam Service Provider Console:

1. Log on to the machine that hosts Veeam Service Provider Console as a local administrator.

If you installed Veeam Service Provider Console using the distributed deployment scenario, log on to the machine that hosts the Veeam Service Provider Console Web UI component.

1. Log in to Veeam Service Provider Console as a local administrator.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

Note that to disable maintenance mode, you must log in using local host address:

https://localhost:1280

1. In the Server Settings section, open the Maintenance Mode tab.
2. Set the Backup portal maintenance mode toggle to Off.

After you disable the maintenance mode for Veeam Service Provider Console, portal users will be able to authenticate to the portal in a usual way.


