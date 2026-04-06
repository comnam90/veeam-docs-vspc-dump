---
title: "Removing Backup Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/remove_backup_policies.html"
last_updated: "12/22/2023"
product_version: "9.1.0.30636"
---

# Removing Backup Policies


You can remove backup policies created by your company users in the Client Portal.

|  |
| --- |
| Note: |
| * You cannot remove predefined backup policies and policies configured by your service provider.  * If the policy is used in the deployment settings of Veeam backup agents, you must remove this policy from the settings first. For details, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

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
* Use the Policy type filter to show only predefined backup policies, policies created by your service provider or policies created in the Client Portal.

* Use the Guest OS filter to show only backup policies for Windows, Linux or macOS.

1. At the top of the policies list, click Remove.

Alternatively, you can right-click the necessary backup policy and choose Remove.

1. In the Delete Policy window, do one of the following:

* If the backup policy is not assigned to any Veeam backup agents, click Yes to confirm removal.
* If the backup policy is assigned to one or more Veeam backup agents:

* To remove the backup policy and all Veeam backup agent jobs configured according to this policy, click Yes.
* To remove the backup policy but leave on Veeam backup agents job configurations associated with this policy, click No.

For Veeam backup agents from which the backup policy is removed, the policy type will change to Custom.


