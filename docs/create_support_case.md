---
title: "Creating Support Cases"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_support_case.html"
last_updated: "3/21/2024"
product_version: "9.1.0.30636"
---

# Creating Support Cases


In some cases, to troubleshoot issues with managed Veeam products or Veeam Service Provider Console you may need to contact Veeam Customer Technical Support. To speed up the support case creation, you can open a case directly from Veeam Service Provider Console.

You can configure Veeam Service Provider Console to automatically attach log files from the affected products to the support case. If you do so, you do not have to download the log files from different products and attach them to the support case manually. When you create a support case in Veeam Service Provider Console portal, Veeam Service Provider Console transfers the case settings and automatically collected log files to Veeam Customer Technical Support portal. After that, you can manage the created support case from Veeam Customer Technical Support portal or monitor the case status in Veeam Service Provider Console.

Note that Veeam Service Provider Console will keep information on a created support case for 180 days. After that, the case will be removed from Veeam Service Provider Console UI and will only be accessible from Veeam Customer Technical Support portal.

Prerequisites

Before you create a support case, make sure that the machine hosting Veeam Service Provider Console Server component allows outbound traffic to \*.amazonaws.com.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Creating Support Cases

To create a new Veeam Customer Technical Support case in Veeam Service Provider Console, perform the following steps:

1. [Launch the New Support Case wizard](launch_support_wizard.md).
2. [Specify Veeam Customer Technical Support account](specify_support_account.md).
3. [Select product](select_product.md).
4. [Select case category](select_category.md).
5. [Specify case scope](specify_case_scope.md).
6. [Select alarm](select_alarm.md).
7. [Select report](select_report.md).
8. [Select backup jobs](select_backup_jobs.md).
9. [Upload attachments](upload_logs.md).
10. [Select Veeam Customer Technical Support region](specify_support_region.md).
11. [Specify support case severity](specify_severity.md).
12. [Specify support case description](specify_case_description.md).
13. [Review support case settings](review_support_case.md).


