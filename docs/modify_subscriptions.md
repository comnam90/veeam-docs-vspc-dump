---
title: "Modifying Subscription Plans"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_subscriptions.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Modifying Subscription Plans


You can modify settings of existing subscription plan.

|  |
| --- |
| Note: |
| After Veeam Service Provider Console upgrade to version 9, all free of charge workloads and storage configured in existing subscription plans will be moved to the Remote Services section. To configure free of charge workloads and storage for hosted services, you must edit the required subscription plan. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator.

Site Administrator can only view subscription plan summary.

Modifying Subscription Plan

To modify settings of a subscription plan:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click click Templates and navigate to the Subscription Plans tab.
3. Select the necessary subscription plan in the list.
4. At the top of the list, click Edit.

Alternatively, you can right-click the necessary subscription plan and choose Edit.

1. Modify subscription plan settings as described in [Creating Subscription Plans](create_subscriptions.md).
2. Save changes.

Settings of a modified subscription plan will be used to generate new invoices. Invoices generated before making changes will not be affected.


