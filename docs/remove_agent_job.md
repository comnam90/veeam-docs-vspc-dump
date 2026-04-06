---
title: "Removing Veeam Backup Agent Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_agent_job.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Removing Veeam Backup Agent Jobs


If you no longer want to protect data of a managed computer, you can remove a backup job configuration.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Removing Veeam Backup Agent Job

To remove a job configuration from Veeam backup agent:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Choose the necessary computer in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
4. In the Agent Backup Job window, select one or more jobs that you want to remove and click Delete Job.

Alternatively, you can right-click the necessary backup job and choose Delete Job.

1. In the Delete Backup Job window, click Delete to confirm removal.

If the backup job is pointed to a cloud repository, you can select if you want to remove backup files, created by this job:

* To delete the backup job and all backup files, in the Delete Backup Job window, click Delete All.

Note that you cannot delete backup files for jobs with enabled immutability.

* To delete only the backup job and keep the backup files in the cloud, in the Delete Backup Job window, click Delete Job.

Other Ways to Remove Veeam Backup Agent Job Settings

You can remove a job configuration from Veeam backup agent in the list of discovered computers or discovered Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers > Computers tab or Backup Agents tab.
3. Choose the necessary computer in the list and click a link in the Backup Policy column.
4. In the Assigned Backup Policies window, select one of more jobs that you want to remove and click Delete Job.

Alternatively, you can right-click the necessary backup job and choose Delete Job.

1. In the Delete Backup Job window, click Delete to confirm removal.

If the backup job is pointed to a cloud repository, you can select if you want to remove backup files, created by this job:

* To delete the backup job and all backup files, in the Delete Backup Job window, click Delete All.

Note that you cannot delete backup files for jobs with enabled immutability.

* To delete only the backup job and keep the backup files in the cloud, in the Delete Backup Job window, click Delete Job.


