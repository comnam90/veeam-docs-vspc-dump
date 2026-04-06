---
title: "Deleting Alarms"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/delete_alarms.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Deleting Alarms


You can delete triggered alarms if you no longer need to keep them in Veeam Service Provider Console.

Required Privileges

To perform these tasks, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Deleting Alarms

To delete one or more triggered alarms:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Active Alarms.

Veeam Service Provider Console will display a list of all triggered alarms.

To narrow down the list of alarms, you can apply the following filters:

* Alarm — search triggered alarms by name.
* Status — limit the list of alarms by the alarm status (Resolved, Warning, Error, Information, Acknowledged, Processing).
* Product — limit the list of alarms by product (Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365, Veeam Agent).
* Monitoring platform — limit the list of alarms by the monitoring platform where alarms were triggered (Veeam ONE, Veeam Service Provider Console).
* Time Period — limit the list of alarms by the time when alarms were triggered.
* Location — limit the list of alarms by location for which alarms were triggered. To limit the list of alarms by location, use filter at the top left corner of the Veeam Service Provider Console window.

1. Select the necessary alarms in the list.
2. At the top of the alarm list, click Delete Alarm.

Alternatively, you can right-click the necessary alarm and choose Delete Alarm.

Note that when you delete Veeam ONE alarms in Veeam Service Provider Console, these alarms are removed from Veeam Service Provider Console portal but remain triggered in Veeam ONE.

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12 or later. |

1. In the confirmation window, click Yes to confirm removal.


