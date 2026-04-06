---
title: "Enabling and Disabling Alarm Synchronization"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/enable_disable_alarm_sync.html"
last_updated: "10/30/2023"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Alarm Synchronization


If you use Veeam Service Provider Console and Veeam ONE to monitor virtual and backup infrastructures, you can enable alarms data collection to synchronize alarms between Veeam Service Provider Console and Veeam ONE. Alarm synchronization allows you to monitor and manage alarms triggered on Veeam ONE servers in Veeam Service Provider Console. For details on managing triggered alarms, see [Working with Triggered Alarms](view_triggered_alarms.md).

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12 or later. |

Enabling Alarms Synchronization

To enable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the ONE Servers tab.

To display all Veeam ONE servers with disabled alarm synchronization, click Filter, in the Alarms data collection section, select Disabled, and click Apply.

1. Select one or more Veeam ONE servers in the list.
2. At the top of the list, set the Alarms Data Collection toggle to On.

After you enable alarms data collection, Veeam Service Provider Console will display alarms from managed Veeam ONE servers on the Active Alarms tab.

Disabling Alarms Synchronization

If you no longer want to manage in Veeam Service Provider Console alarms triggered on Veeam ONE servers, you can disable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the ONE Servers tab.

To display all Veeam ONE servers with enabled alarm synchronization, click Filter, in the Alarms data collection section, select Enabled, and click Apply.

1. Select one or more Veeam ONE servers in the list.
2. At the top of the list, set the Alarms Data Collection toggle to Off.

After you disable alarms data collection, Veeam Service Provider Console will no longer display new and previously collected alarms from managed Veeam ONE servers.


