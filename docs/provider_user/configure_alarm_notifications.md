---
title: "Receiving Alarm Email Notifications"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/configure_alarm_notifications.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Receiving Alarm Email Notifications


To stay informed about potential problems in the managed backup infrastructure and get notified when you are approaching quota limits for allocated cloud resources, you can configure Veeam Service Provider Console to send email notifications about alarms.

To configure Veeam Service Provider Console to send email notifications with alarm details:

1. Specify email notification recipients.

1. [Specify email addresses of Location Administrators, Company Administrators and Company Owner](create_portal_users.md).

By default, all alarms are configured to send email notifications to Location Administrators and Company Administrators. When you create a new portal user, you must specify user's email address. If you assign the Location Administrator or Company Administrator role to the portal user, Veeam Service Provider Console will send alarm notifications at the user's email address.

If you are the Company Owner, and want to receive alarm notifications, make sure you have an email address specified in your user profile. For details on working with user profile details, see [Modifying User Profile](modify_user_profile.md).

1. [Specify additional email notification recipients](modify_alarm_settings.md#alarmActions).

You can configure Veeam Service Provider Console to send email notifications to users other than Location Administrators, Company Administrators and Company Owner. To do so, you can add an alarm response action that will send an email to the necessary recipient.

1. [Specify when email notifications must be sent](modify_alarm_settings.md#alarmActions).

By default, Veeam Service Provider Console sends email notifications every time when a new alarm is triggered, or when the status of an existing alarm changes to Error or Warning. You can configure alarm response actions to send email notifications when an alarm acquires a specific status only. For example, you can choose to receive email notifications about errors and warnings only, and skip notifications about informational and resolved alarms.

The following image illustrates an email notification with alarm details.

[![Alarm Email Notification](images/alarm_email_notification.webp)](images/alarm_email_notification.webp "Alarm Email Notification")


