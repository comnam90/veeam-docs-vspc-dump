---
title: "Starting and Stopping Veeam Backup Agent Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/start_stop_agent_jobs.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Starting and Stopping Veeam Backup Agent Jobs


You can start and stop Veeam backup agent jobs without accessing the Veeam backup agent Control Panel on managed computers. For example, if a backup job has failed, you can start this job again in Veeam Service Provider Console to avoid company data loss.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Starting Jobs

To start Veeam backup agent jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select the necessary Veeam backup agents in the list and click Actions > Start.

Alternatively, you can right-click the necessary Veeam backup agent and choose Actions > Start.

Veeam Service Provider Console will start all jobs configured for the selected Veeam backup agents.

To start specific Veeam backup agent jobs:

1. Find the necessary Veeam backup agent in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
2. In the Agent Backup Job window, select one or more backup jobs.
3. At the top of the list, click Actions > Start.

Alternatively, you can right-click the necessary backup job and choose Actions > Start.

Stopping Jobs

To stop Veeam backup agent jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Computers tab and navigate to Managed by Console.
3. Select the necessary Veeam backup agents in the list and click Actions > Stop.

Alternatively, you can right-click the necessary Veeam backup agent and choose Actions > Stop.

Veeam Service Provider Console will stop all jobs configured for the selected Veeam backup agents.

To stop specific Veeam backup agent jobs:

1. Find the necessary Veeam backup agent in the list and click a link in the Backup Policy, Successful Jobs or Running Jobs column.
2. In the Agent Backup Job window, select one or more backup jobs.
3. At the top of the list, click Actions > Stop.

Alternatively, you can right-click the necessary backup job and choose Actions > Stop.


