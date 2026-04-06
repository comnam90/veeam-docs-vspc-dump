---
title: "Disabling and Enabling Veeam Backup Agent Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/disable_enable_agent_jobs.html"
last_updated: "7/1/2025"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Veeam Backup Agent Jobs


You can disable and enable scheduled Veeam backup agent jobs without accessing the Veeam backup agent Control Panel on managed computers. For example, to prevent a backup job from writing data to a cloud repository by a configured schedule, you can temporarily disable this job.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Disabling Jobs

To prevent Veeam backup agent jobs start by the schedule, you can disable them:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Scheduling > Disable.

Alternatively, you can right-click the necessary Veeam backup agent and choose Scheduling > Disable.

Veeam Service Provider Console will disable all scheduled backup jobs on selected Veeam backup agents.

Enabling Jobs

To enabled previously disabled Veeam backup agent jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select one or more Veeam backup agents in the list.
4. At the top of the list, click Scheduling > Enable.

Alternatively, you can right-click the necessary Veeam backup agent and choose Scheduling > Enable.

Veeam Service Provider Console will enable all scheduled backup jobs on selected Veeam backup agents.


