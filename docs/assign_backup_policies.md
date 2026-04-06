---
title: "Assigning Backup Policies"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/assign_backup_policies.html"
last_updated: "8/1/2025"
product_version: "9.1.0.30636"
---

# Assigning Backup Policies


To configure Veeam backup agent job settings on one or more managed computers, you can assign one or more saved backup policies to these computers. You can assign any backup policy, including predefined policies, policies that you created, and policies created by Company Owner in the Client Portal.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

|  |
| --- |
| Note: |
| Consider the following:   * Backup policies created by Company Owners in the Client Portal can be assigned only to this particular Company. If you want to assign such policies to other companies, you can copy them as described in section [Copying Backup Policies](copy_policies.md). * When you assign cloud backup policies to computers, some of the configured advanced settings may get disabled automatically depending on type of repository assigned to the company. * You cannot assign cloud backup policies to computers hosted in your infrastructure. |

Assigning Backup Policies

To assign a backup policy to one or more managed computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Agents tab.
3. Select the necessary computers in the list.
4. At the top of the list, click the Assign link.

Alternatively, you can right-click the necessary computer and choose Assign.

1. In the Backup Policies window, select one or more policies and click Assign.
2. To check the status of the policy assignment, click the link in the Backup Policy column.

The Assigned Backup Policies window will open.

If the policy was assigned successfully, the Name column will display the policy name. If there was a problem assigning the policy, the column will display the Failed to apply error message. Click the message to review possible causes.

Other Ways to Assign Backup Policies

You can also assign backup policies:

* As part of the discovery process, in the discovery rule settings.

For details, see [Deploying Management Agents with Discovery Rules](install_agents_discovery.md).

* As a template for individual job configuration.

For details, see [Configuring Backup Job Settings for Individual Computers](change_backup_job_settings.md).

* As part of Veeam backup agent installation process.

For details, see [Installing Veeam Backup Agents Manually](install_agents_manually.md#initiate).

* As part of automatic deployment process.

For details, see [Installing Veeam Backup Agents Automatically](automate_discovery_installation.md).


