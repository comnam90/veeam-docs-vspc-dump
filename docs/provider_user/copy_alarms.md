---
title: "Copying Alarms"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/copy_alarms.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Copying Alarms


If you need a custom alarm, you can create a copy of an existing alarm and modify its settings and assignment scope.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

Copying Alarms

To create an alarm copy:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Open the Predefined Alarms tab.
4. To narrow down the list of alarms, you can apply the following filters:

* Alarm — search alarms by name.
* Alarm type — limit the list of the alarms by type (Predefined, Custom).
* Category — limit the list of the alarms by alarm object category (Management agent, Veeam Agent, Company, User, Discovery rule, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365).

1. Select the necessary alarm in the list.
2. At the top of the list, click Copy.

Alternatively, you can right-click the necessary alarm and choose Copy.

1. In the Copy Alarm window, change the name of an alarm copy.
2. Click Apply.
3. Modify alarm settings as described in [Modifying Alarm Settings](modify_alarm_settings.md).
4. If necessary, change the alarm assignment scope as described in [Changing Alarm Assignment Scope](assign_alarms.md).
5. If necessary, select the alarm and at the top of the list click Enable to enable the alarm.

Alternatively, you can right-click the created alarm and choose Enable.


