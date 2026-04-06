---
title: "Working with Alarms"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/alarms.html"
last_updated: "12/6/2023"
product_version: "9.1.0.30636"
---

# Working with Alarms


Veeam Service Provider Console comes with a set of predefined alarms that notify about important events, state changes and potential problems in managed client backup infrastructures, and inform about issues with Veeam Service Provider Console. All alarms include detailed knowledge base articles. If a problem occurs, you will have all necessary information for troubleshooting and finding the root cause of an issue. For a list of predefined alarms, see [Alarms](appendix_alarms.md).

Depending on your requirements, you can customize predefined alarms, modify alarm rules and change alarm response actions.

Alarm Rules

Alarms can be triggered in response to:

* Changed state of backup infrastructure objects
* Specific events
* Resource usage values exceeding or falling below thresholds

Conditions under which alarms must be triggered are described with alarm rules. You can customize alarm rules in accordance with your requirements.

|  |
| --- |
| Note: |
| Consider that RPO-based alarms will trigger for the following objects:   * VMs that were included in a job and for which new restore points were not created in the amount of time specified in alarm settings. * VM templates that were included in a job and for which new full restore points were not created in the amount of time specified in alarm settings. |

Alarm Severity

Every triggered alarm has its own status, or alarm severity. Alarm severity defines how serious the state change or event is, and how badly it can affect a backup infrastructure object or hinder data protection.

There are four alarm severity levels, color-coded as follows:

* Error (red) indicates a critical situation or major problem that requires immediate action.
* Warning (yellow) indicates a potential problem or non-critical issue that needs your attention. If the issue is left without attention, it can potentially cause a major problem.
* Resolved (green) indicates that the issue was eliminated because the condition has changed, or shows that an alarm was resolved manually.
* Information (blue) indicates general information about a specific condition, or health state of a backup infrastructure object.

Alarm Response Actions

When an alarm is triggered, it becomes available in the Active Alarms dashboard in Veeam Service Provider Console. You can either view alarms in Veeam Service Provider Console or configure Veeam Service Provider Console to perform additional actions in response to triggered alarms or alarm status changes:

* Send an email notification with alarm details
* Run a custom script
* Perform all these actions at once

In This Section

* [Managing Alarms](configure_alarms.md)
* [Working with Triggered Alarms](view_triggered_alarms.md)


