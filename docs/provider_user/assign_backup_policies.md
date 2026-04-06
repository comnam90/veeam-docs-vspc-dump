---
title: "Assigning Backup Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/assign_backup_policies.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Assigning Backup Policies


To configure Veeam backup agent job settings on one or more managed computers, you can assign a saved backup policy to these computers. You can assign any backup policy, including predefined policies, policies created by your company users, and policies created by your service provider.

|  |
| --- |
| Note: |
| When you assign cloud backup policies to computers, some of the configured advanced settings may get disabled automatically depending on type of repository assigned to the company. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Assigning Backup Policies

To assign a backup policy to one or more managed computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Select the necessary computers in the list.
4. At the top of the list, click the Assign link.
5. In the Backup Policies window, select the necessary policy and click Assign.
6. Check the status of the policy assignment in the Backup Policy column.

If the policy was assigned successfully, the Name column will display the policy name. If there was a problem assigning the policy, the column will display the Failed to apply error message. Click the message to review possible causes.

Other Ways to Assign Backup Policies

You can also assign backup policies:

* As part of the discovery process, in the discovery rule settings.

For details, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md).

* As a template for individual job configuration.

For details, see [Configuring Backup Job Settings for Individual Computers](change_backup_job_settings.md).

* As part of Veeam backup agent installation process.

For details, see [Installing Veeam Backup Agents Manually](install_agents_manually.md).


