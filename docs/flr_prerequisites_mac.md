---
title: "Before You Begin"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/flr_prerequisites_mac.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Before You Begin


Before you perform restore, check the following prerequisites:

* The backup from which you plan to restore data must be successfully created at least once.
* [For backups stored in network shared folders, on Veeam Backup & Replication repositories and Veeam Cloud Connect repositories] You must have access to the target location where the backup file resides.
* [For backups stored on Veeam Backup & Replication repositories] You must have access permissions on the target backup repository. For details, see section [Setting Up User Permissions on Backup Repositories](https://helpcenter.veeam.com/docs/agentformac/userguide/integrate_permissions.html) of the Veeam Agent for Mac User Guide.

* Multiple users can browse only one restore point on one Veeam backup agent at the same time.

* If you want to download restored files and folders to your computer, you must have credentials to a user account with super user privileges on the protected computer.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.


