---
title: "Enabling and Disabling Alarms"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/disable_enable_alarms.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Enabling and Disabling Alarms


You can enable and disable alarms.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Enabling Alarms

Out of the box, the most critical alarms are enabled. However, some alarms are disabled by default. These are non-critical alarms and alarms requiring that you review and customize alarm rules or assignment scope in accordance with your needs.

To enable one or more alarms:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Open the Predefined Alarms tab.
4. To narrow down the list of alarms, you can apply the following filters:

* Alarm — search alarms by name.
* Alarm type — limit the list of the alarms by type (Predefined, Custom).
* Category — limit the list of the alarms by alarm object category (Management agent, Veeam Agent, Company, Internal, Discovery rule, Reseller, Site, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365).

1. Select the necessary alarms in the list.
2. At the top of the list, click Enable.

Alternatively, you can right-click the necessary alarm and choose Enable.

Disabling Alarms

You can disable alarms that you do not use for monitoring. Disabled items will not trigger alarms for any companies and locations, even if the alarm conditions are met.

To disable one or more alarms:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Open the Predefined Alarms tab.
4. To narrow down the list of alarms, you can apply the following filters:

* Alarm — search alarms by name.
* Alarm type — limit the list of the alarms by type (Predefined, Custom).
* Category — limit the list of the alarms by alarm object category (Management agent, Veeam Agent, Company, Internal, Discovery rule, Reseller, Site, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365).

1. Select the necessary alarms in the list.
2. At the top of the alarm list, click Disable.

Alternatively, you can right-click the necessary alarm and choose Disable.

|  |
| --- |
| Note: |
| After you disable an alarm, all unresolved Warning or Error notifications that were triggered by this alarm will change their status to Resolved. |


