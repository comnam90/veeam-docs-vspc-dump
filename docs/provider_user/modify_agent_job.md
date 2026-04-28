---
title: "Modifying Veeam Backup Agent Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/modify_agent_job.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Modifying Veeam Backup Agent Jobs


You can modify Veeam backup agent job settings on a single computer without affecting job configuration applied to other Veeam backup agents.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Modifying Veeam Backup Agent Job

To modify Veeam backup agent job settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Choose the necessary computer in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
4. In the Agent Backup Job window, select the job that you want to modify and click Edit.

Alternatively, you can right-click the necessary backup job and choose Edit.

1. In the Edit Backup Job wizard, modify Veeam backup agent job settings.

For details on backup job settings, see [Configuring Backup Policies](configure_backup_policies.md).

If you chose a cloud repository as the backup destination, make sure you specify the credentials of the Veeam Cloud Connect tenant or subtenant account. The list of available cloud backup repositories may differ depending on the specified credentials. You can also select the target repository on which Veeam Service Provider Console will store backups.

1. Save changes.

|  |
| --- |
| Note: |
| You cannot modify connection settings and advanced settings for cloud jobs targeted to an object storage repository. |

Other Ways to Modify Veeam Backup Agent Job Settings

You can modify Veeam backup agent job settings in the list of discovered computers or discovered Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab or Backup Agents tab.
3. Choose the necessary computer in the list and click a link in the Backup Policy column.
4. In the Assigned Backup Policies window, select the job that you want to modify and click Edit.

Alternatively, you can right-click the necessary backup job and choose Edit.

1. In the Edit Backup Job wizard, modify Veeam backup agent job settings.

For details on backup job settings, see [Configuring Backup Policies](configure_backup_policies.md).

1. Save changes.


