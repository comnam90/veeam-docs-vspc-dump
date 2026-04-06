---
title: "Enabling and Disabling Alarms Synchronization"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/one_enable_disable_alarm_sync.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Alarms Synchronization


If you use Veeam Service Provider Console and Veeam ONE to monitor virtual and backup infrastructures, you can enable alarms data collection to synchronize alarms between Veeam Service Provider Console and Veeam ONE. Alarms synchronization allows you to monitor and manage alarms triggered on Veeam ONE servers in Veeam Service Provider Console. For details on managing triggered alarms, see [Working with Triggered Alarms](view_triggered_alarms.md).

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12 or later. |

Enabling Alarms Synchronization

To enable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam ONE plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary Veeam ONE servers in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error, Info, All).

1. At the top of the list, set the Alarms Data Collection toggle to On.

After you enable alarms data collection, Veeam Service Provider Console will display alarms from managed Veeam ONE servers on the Active Alarms tab.

To enable alarms data collection for client Veeam ONE servers, go to the Discovery > ONE Servers tab. For details, see [Enabling and Disabling Alarms Synchronization](enable_disable_alarm_sync.md#enable).

Disabling Alarms Synchronization

If you no longer want to manage alarms triggered on Veeam ONE servers in Veeam Service Provider Console, you can disable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam ONE plugin tile.
4. In the menu on the left, click Servers.
5. Select the necessary Veeam ONE servers in the list.

To narrow down the list of servers, you can apply the following filters:

* Hostname — search the list of servers by server name.
* Management agent status — limit the list of servers by management agent status (Healthy, Warning, Error, Info, All).

1. At the top of the list, set the Alarms Data Collection toggle to Off.

After you disable alarms data collection, Veeam Service Provider Console will no longer display new and previously collected alarms from managed Veeam ONE servers.

To disable alarms data collection for client Veeam ONE servers, go to the Discovery > ONE Servers tab. For details, see [Enabling and Disabling Alarms Synchronization](enable_disable_alarm_sync.md#disable).


