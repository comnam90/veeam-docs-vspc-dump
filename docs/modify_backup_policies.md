---
title: "Modifying Backup Policies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_backup_policies.html"
last_updated: "8/1/2025"
product_version: "9.1.0.30636"
---

# Modifying Backup Policies


You can modify settings of all saved backup policies, including predefined policies, policies that you created, and policies created by Company Owner and Company Administrators in the Client Portal and reseller users in the Reseller Portal.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator.

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
* Use the Policy type filter to show only predefined backup policies, policies created by the provider, policies created by reseller users in the Reseller Portal or policies created in the Client Portal.
* Use the Access type filter to show only public or private policies.
* Use the Guest OS filter to show only backup policies for Windows, Linux or macOS.

1. At the top of the policies list, click Edit.

Alternatively, you can right-click the necessary backup policy and choose Edit.

1. Modify backup policy settings as described in [Configuring Backup Policies](configure_backup_policies.md).
2. Save changes.
3. If a backup policy is already assigned to one or more Veeam backup agents, the backup policy wizard will display a notification window prompting to apply changes to agents. Click OK to close the notification window, then click Propagate Changes.

If a policy is assigned to one or more hosted Veeam backup agents and you have changed the backup target to a Veeam Cloud Connect repository, for hosted Veeam backup agents the policy will not be updated.

If you do not apply the modified settings, you can do it later, as described in section [Updating Backup Job Configuration](get_latest_configuration.md).


