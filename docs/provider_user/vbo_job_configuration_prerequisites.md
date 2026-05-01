---
title: "Before You Begin"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/vbo_job_configuration_prerequisites.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Before You Begin


Before you configure a backup job, consider the following:

* The target location where you plan to store backup files must have enough free space.

* You can create only one entire organization backup job per organization.

* Objects that are already added to the scope of any of your backup jobs will be skipped from the entire organization processing list.
* Due to possible access limitations some Sites objects may be unavailable.
* Due to Microsoft limitations, you cannot add the following objects for Microsoft 365 organizations with enabled [security defaults](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-security-defaults): Discovery Search Mailboxes, Public Folder Mailboxes and Dynamic Distribution Groups.
* You cannot schedule backup jobs configured on Veeam Backup for Microsoft 365 servers that were assigned to you by your service provider if your service provider has disabled scheduling jobs on these servers for your company. To configure schedule for these backup jobs, contact your service provider.


