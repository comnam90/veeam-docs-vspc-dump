---
title: "Checking for Updates"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/update_notifications.html"
last_updated: "11/2/2023"
product_version: "9.1.0.30636"
---

# Checking for Updates


To stay aware of Veeam Service Provider Console and managed Veeam products updates and patches, you can configure notifications and automatic updates or check for updates manually. Updates eliminate the risk of using out-of-date components and enhance your work experience with the product.

Note that Veeam Service Provider Console automatically downloads updates only for managed Veeam backup agents. Updates and patches for other products must be downloaded and installed manually.

Required Privileges

To perform the task, a user must have the following role assigned: Portal Administrator.

Configuring Update Notifications

To enable notifications about new product versions and updates and download updates for Veeam backup agents automatically:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click About.
3. In the Product Updates & Download section, switch the Automatic checks (recommended) toggle to On.

Veeam Service Provider Console will connect to the Veeam Update Notification Server (vac.butler.veeam.com) and collect information about available updates every 24 hours. If new product versions, patches and updates are available, Veeam Service Provider Console will inform you about them with a notification in the notification bell and download updates for Veeam backup agents. This notification is visible to all users with the Portal Administrator role.

Checking for Updates Manually

To manually check if new product versions and updates for managed Veeam products are available:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click About.
3. In the Product Updates & Download section, click the Check for Updates button.

Veeam Service Provider Console will connect to the Veeam Update Notification Server (vac.butler.veeam.com) and collect information about available updates. If new product versions, patches and updates are available, Veeam Service Provider Console will inform you about them with a notification in the notification bell and download updates for Veeam backup agents. This notification is visible to all users with the Portal Administrator role.


