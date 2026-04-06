---
title: "Disabling and Enabling Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/disable_enable_vbo_jobs.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Disabling and Enabling Jobs


You can disable and enable scheduled Veeam Backup for Microsoft 365 jobs without accessing the Veeam Backup for Microsoft 365 console on managed backup servers. For example, to prevent a backup job from writing data to a cloud repository, you can temporarily disable this job.

Disabling Jobs

To disable one or more scheduled jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Microsoft 365 Objects tab:
3. Select the necessary job in the list.
4. At the top of the list, click Scheduling > Disable.

Alternatively, you can right-click the necessary job and choose Scheduling > Disable.

Enabling Jobs

To enable one or more previously disabled jobs:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Microsoft 365 Objects tab:
3. Select the necessary job in the list.
4. At the top of the list, click Scheduling > Enable.

Alternatively, you can right-click the necessary job and choose Scheduling > Enable.


