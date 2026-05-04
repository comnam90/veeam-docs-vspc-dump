---
title: "Before You Begin"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/flr_prerequisites_win.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Before You Begin


Before you perform restore, check the following requirements and limitations.

Requirements

Consider the following requirements:

* The backup from which you plan to restore data must be successfully created at least once.
* [For backups stored in network shared folders, on Veeam Backup & Replication repositories and Veeam Cloud Connect repositories] You must have access to the target location where the backup file resides.
* [For backups stored on Veeam Backup & Replication repositories] You must have access permissions on the target backup repository. For details, see section [Setting Up User Permissions on Backup Repositories](https://helpcenter.veeam.com/docs/agentforwindows/userguide/integrate_permissions.html) of the Veeam Agent for Microsoft Windows User Guide.
* If you want to download restored files and folders to your computer, you must have credentials to a user account with administrative privileges on the protected computer.

Limitations

Consider the following limitations:

* You can restore only files and folders from basic disks and dynamic disks (including simple, mirrored and striped volumes).
* You cannot restore pipes and other file system objects. File-level restore supports recovery of files and folders only.
* You cannot restore files from a backup created in the reverse incremental mode if the backup job is being performed. If the backup is created in the incremental backup mode and the backup job is being performed, you can restore files from any available restore point.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Location Administrator, Subtenant.


