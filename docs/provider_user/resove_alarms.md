---
title: "Resolving Alarms"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/resove_alarms.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Resolving Alarms


Triggered alarms can be resolved automatically or manually.

Alarms are resolved automatically in the following cases:

* When an alarm is disabled. For details, see [Enabling and Disabling Alarms](disable_enable_alarms.md).
* When conditions that caused the alarm are eliminated.

You can also resolve alarms manually if the state of the monitored object is back to normal, or if the alarm requires no further investigation, and no corrective actions must be taken.

Required Privileges

To perform these tasks, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Resolving Alarms

To manually resolve one or more alarms:

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
2. At the top of the alarm list, click Resolve.

Alternatively, you can right-click the necessary alarm and choose Resolve.

When you resolve Veeam ONE alarms in Veeam Service Provider Console, these alarms will be automatically resolved in Veeam ONE. When you resolve triggered alarms in Veeam ONE, these alarms will be also resolved in Veeam Service Provider Console.

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12.1 or later. |

1. In the Resolve Alarm window, specify a comment about resolving the alarm.

1. Click Resolve.

The specified alarm resolution comment will be available in the list of alarm status changes. To view the comment, click the N. of Repeats link for the triggered alarm, and then click the Comment link for the necessary status change. For details on viewing alarms, see [Viewing and Exporting Triggered Alarms](view_alarm_details.md).


