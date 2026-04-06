---
title: "Updating Backup Job Configuration"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/get_latest_configuration.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Updating Backup Job Configuration


When you modify settings of a backup policy, you can immediately apply them to Veeam backup agents that have this policy assigned. If you do not apply modified settings, the status of a backup policy for Veeam backup agents will be set to Outdated. To put Veeam backup agent job settings in sync with the updated backup policy, you must get the latest job configuration.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Updating Veeam Backup Agent Job Configuration

To update Veeam backup agent job configuration and synchronize it with the backup policy:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Backup Agents tab.
3. Click Filter. In the Filter backup agents by assigned policy section, select the Outdated check box only. Click Apply.

The list of Veeam backup agents will display backup agents whose backup job settings were not updated in accordance with the new backup policy settings.

1. Select the necessary Veeam backup agent in the list and click a link in the Backup Policy column.

The Assigned Backup Policies window will open.

1. From the list of backup policies, select one or more policies whose settings you want to propagate to Veeam backup agent.
2. At the top of the list, click Update Config.

Alternatively, you can right-click the necessary backup policy and choose Update Config.

Other Ways to Update Veeam Backup Agent Job Configuration

Alternatively, you can update backup job configuration in the list of Veeam backup agent jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select the necessary computer in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
4. In the Agent Jobs window, click Filter. In the Filter agents backup jobs by assigned policy section, select the Outdated check box only. Click Apply.

The list of backup jobs will display jobs whose settings were not updated in accordance with the new backup policy settings.

1. Select the necessary jobs in the list.
2. At the top of the list, click Update Config.

Alternatively, you can right-click the necessary job and choose Update Config.


