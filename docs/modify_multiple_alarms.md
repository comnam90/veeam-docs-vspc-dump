---
title: "Modifying Multiple Alarms"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_multiple_alarms.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Modifying Multiple Alarms


Veeam Service Provider Console supports batch alarm editing. In the batch editing mode, you can change only alarm response actions.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Modifying Multiple Alarms

To modify response actions of several alarms in batch:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Open the Predefined Alarms tab.
4. To narrow down the list of alarms, you can apply the following filters:

* Alarm — search alarms by name.
* Alarm type — limit the list of the alarms by type (Predefined, Custom).
* Category — limit the list of the alarms by alarm object category (Management agent, Veeam Agent, Company, Internal, Discovery rule, Reseller, Site, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365).

1. Select alarms you want to modify.
2. At the top of the list, click Edit.

Alternatively, you can right-click the necessary alarm and choose Edit.

1. At the Actions step of the wizard, modify alarm response actions.

For details, see [Step 3. Specify Alarm Response Actions](modify_alarm_settings.md#alarmActions).

1. Click Finish to save alarm settings.


