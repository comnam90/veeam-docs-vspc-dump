---
title: "Deleting Alarms"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/delete_alarms.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Deleting Alarms


You can delete triggered alarms if you no longer need to keep them in Veeam Service Provider Console.

Required Privileges

To perform these tasks, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Deleting Alarms

To delete one or more triggered alarms:

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
2. At the top of the alarm list, click Delete Alarm.

Alternatively, you can right-click the necessary alarm and choose Delete Alarm.

Note that when you delete Veeam ONE alarms in Veeam Service Provider Console, these alarms are removed from Veeam Service Provider Console portal but remain triggered in Veeam ONE.

|  |
| --- |
| Note: |
| This functionality is available for Veeam ONE version 12 or later. |

1. In the confirmation window, select the necessary option:

* Click Yes to remove the alarm for your company and managed companies.
* Click No to remove the alarm only for your company.


