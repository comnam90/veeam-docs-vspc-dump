---
title: "Removing Backup Policies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_backup_policies.html"
last_updated: "8/1/2025"
product_version: "9.1.0.30636"
---

# Removing Backup Policies


You can remove any saved backup policies, including predefined policies, policies that you created, and backup policies created by Company Owner and Company Administrators in the Client Portal and reseller users in the Reseller Portal.

|  |
| --- |
| Note: |
| * If the policy is used in the auto deployment settings of Veeam backup agents, you must remove this policy from the settings first. For details, see [Configuring Auto Deployment Settings](automate_discovery_installation.md#auto).  * If the policy is used in the deployment settings of Veeam backup agents, you must remove this policy from the settings first. For details, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator.

Removing Backup Policies

To remove a backup policy:

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

1. At the top of the policies list, click Remove.

Alternatively, you can right-click the necessary backup policy and choose Remove.

1. In the Delete Policy window, do one of the following:

* If the backup policy is not assigned to any Veeam backup agents, click Yes to confirm removal.
* If the backup policy is assigned to one or more Veeam backup agents:

* To remove the backup policy and all Veeam backup agent jobs configured according to this policy, click Yes.
* To remove the backup policy but leave on Veeam backup agents job configurations associated with this policy, click No.

For Veeam backup agents from which the backup policy is removed, the policy type will change to Custom.


