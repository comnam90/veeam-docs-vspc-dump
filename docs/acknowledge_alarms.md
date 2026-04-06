---
title: "Acknowledging Alarms"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/acknowledge_alarms.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Acknowledging Alarms


You can acknowledge alarms to let other users know that an issue is being investigated or resolved, so no attention is required from their side.

Note that after the issue is resolved, you may need to update the status of the alarm manually. For details, see [Resolving Alarms](resove_alarms.md).

Required Privileges

To perform these tasks, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Acknowledging Alarms

To manually acknowledge one or more alarms:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Active Alarms.

Veeam Service Provider Console will display a list of all triggered alarms.

To narrow down the list of alarms, you can apply the following filters:

* Alarm — search triggered alarms by name.
* Country — limit the list of alarms by country or region of the company for which alarms were triggered.
* Status — limit the list of alarms by the alarm status (Resolved, Warning, Error, Information, Acknowledged, Processing).
* Product — limit the list of alarms by product (Backup portal, Veeam Cloud Connect, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365, Veeam Agent).
* Scope — limit the list of alarms by scope (Internal, Managed companies, Resellers).
* Monitoring platform — limit the list of alarms by the monitoring platform where alarms were triggered (Veeam ONE, Veeam Service Provider Console).
* Time Period — limit the list of alarms by the time when alarms were triggered.
* Site/Reseller/Company/Location — limit the list of alarms by Veeam Cloud Connect site, reseller, company and location for which alarms were triggered. To limit the list of alarms by site, reseller, company and location, use filters at the top left corner of the Veeam Service Provider Console window.

1. Select the necessary alarms in the list.
2. At the top of the alarm list, click Acknowledge Alarm.

Alternatively, you can right-click the necessary alarm and choose Acknowledge Alarm.

When you acknowledge Veeam ONE alarms in Veeam Service Provider Console, these alarms will be automatically acknowledged in Veeam ONE. When you acknowledge triggered alarms in Veeam ONE, these alarms will be also acknowledged in Veeam Service Provider Console.

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12.1 or later. |

1. In the Acknowledge Alarm window, specify a comment about acknowledging the alarm.

To acknowledge the alarm for managed companies, select the Acknowledge alarm in the client's portal check box.

1. Click Acknowledge.

The specified alarm acknowledgment comment will be available in the list of alarm status changes. To view the comment, click the N. of Repeats link for the triggered alarm, and then click the Comment link for the necessary status change. For details on viewing alarms, see [Viewing and Exporting Triggered Alarms](view_alarm_details.md).


