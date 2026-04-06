---
title: "Modifying Backup Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/modify_backup_policies.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Modifying Backup Policies


You can modify settings of all saved backup policies, including predefined policies, policies that you created and policies created by Location Administrators in the Client Portal.

|  |
| --- |
| Note: |
| Predefined backup policies and policies configured by your service provider cannot be modified directly in the Client Portal. When you choose to edit a predefined backup policy or a policy configured by your service provider, Veeam Service Provider Console will create a copy of this policy. You can modify settings of this copy and assign it to Veeam backup agents. For details on working with backup policy copies, see [Copying Backup Policies](copy_policies.md). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

Modifying Backup Policies

To modify settings of a backup policy:

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

1. At the top of the policies list, click Edit.

Alternatively, you can right-click the necessary policy and choose Edit.

1. Modify backup policy settings as described in [Configuring Backup Policies](configure_backup_policies.md).
2. Save changes.
3. If a backup policy is already assigned to one or more Veeam backup agents, the backup policy wizard will display a notification window prompting to apply changes to agents. Click OK to close the notification window, then click Propagate Changes.

If you do not apply the modified settings, you can do it later, as described in section [Updating Backup Job Configuration](get_latest_configuration.md).


