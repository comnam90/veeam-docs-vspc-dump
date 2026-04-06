---
title: "Copying Backup Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/copy_policies.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Copying Backup Policies


Instead of creating a new backup policy from scratch, you can create a copy of an existing backup policy and modify its settings. This can be useful if you need to create a set of similar backup policies with only a few settings that differ.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

Copying Backup Policies

To create a copy of a backup policy:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Navigate to the Backup Policies tab.
4. Select the necessary policy in the list.

To find a backup policy, you can use the following controls:

* Use the search field to find a backup policy by name.
* Use the Type filter to show backup policies for workstations or servers only.
* Use the Policy type filter to show only policies created by your service provider or policies created in the Client Portal.

* Use the Guest OS filter to show only policies created for computers running Windows, Linux or macOS operating system.

1. At the top of the list, click Copy.

Alternatively, you can right-click the necessary policy and choose Copy.

1. Modify the necessary policy settings as described in [Configuring Backup Policies](configure_backup_policies.md).
2. Save changes.


