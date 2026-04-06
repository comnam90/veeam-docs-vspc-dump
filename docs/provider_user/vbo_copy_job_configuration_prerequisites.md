---
title: "Before You Begin"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/vbo_copy_job_configuration_prerequisites.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Before You Begin


Before you configure a backup copy job, check the following prerequisites:

* Add an object storage where you want to keep your backups.

You can target backup copy jobs to object storage and archive repositories. For details on storage systems that Veeam Backup for Microsoft 365 supports as a target for backup copy jobs, see section [Backup Copy](https://helpcenter.veeam.com/docs/vbo365/guide/vbo_backup_copy.html) of the Veeam Backup for Microsoft 365 User Guide.

* The target location where you plan to store backup files must have enough free space.

* Make sure that an extended backup repository where you keep your backups and a target backup repository are located on the same backup proxy server or in the same proxy pool and have the same retention type.

* You cannot schedule backup copy jobs configured on Veeam Backup for Microsoft 365 servers that were assigned to you by your service provider if your service provider has disabled scheduling jobs on these servers for your company. To configure schedule for these backup copy jobs, contact your service provider.


