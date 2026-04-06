---
title: "Enabling and Disabling Alarms Synchronization"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/enable_disable_alarm_sync.html"
last_updated: "7/11/2024"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Alarms Synchronization


If you or your client companies use Veeam Service Provider Console and Veeam ONE to monitor virtual and backup infrastructures, you can enable alarms data collection to synchronize alarms between Veeam Service Provider Console and Veeam ONE. Alarm synchronization allows you to monitor and manage alarms triggered on Veeam ONE servers in Veeam Service Provider Console. For details on managing triggered alarms, see [Working with Triggered Alarms](view_triggered_alarms.md).

Note that after you enable the alarms data collection for a client company Veeam ONE server, the feature will not be enabled automatically for this company or the reseller managing the company. To allow client company and managing reseller to monitor Veeam ONE alarms in Veeam Service Provider Console portal, alarms data collection must be enabled separately in Client Portal and Reseller Portal.

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12 or later. |

Enabling Alarms Synchronization

To enable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the ONE Servers tab.

To display all Veeam ONE servers with disabled alarm synchronization, click Filter, in the Alarms data collection section, select Disabled, and click Apply.

1. Select one or more Veeam ONE servers in the list.
2. At the top of the list, set the Alarms Data Collection toggle to On.

After you enable alarms data collection, Veeam Service Provider Console will display alarms from managed Veeam ONE servers on the Active Alarms tab.

Disabling Alarms Synchronization

If you no longer want to manage in Veeam Service Provider Console alarms triggered on Veeam ONE servers, you can disable alarms synchronization:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the ONE Servers tab.

To display all Veeam ONE servers with enabled alarm synchronization, click Filter, in the Alarms data collection section, select Enabled, and click Apply.

1. Select one or more Veeam ONE servers in the list.
2. At the top of the list, set the Alarms Data Collection toggle to Off.

After you disable alarms data collection, Veeam Service Provider Console will no longer display new and previously collected alarms from managed Veeam ONE servers.


