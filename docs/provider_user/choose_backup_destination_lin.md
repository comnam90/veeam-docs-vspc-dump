---
title: "Step 7. Choose Backup Destination"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/choose_backup_destination_lin.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Step 7. Choose Backup Destination


At the Destination step of the wizard, select a target location for the created backup:

* Local storage — select this option if you want to save the backup on a removable storage device attached to the endpoint, or on a local drive of the endpoint. With this option selected, you will pass to the [Local Storage](specify_storage_settings_lin.md) step of the wizard.
* Shared folder — select this option if you want to save the backup in a network shared folder. With this option selected, you will pass to the [Shared Folder](specify_folder_settings_lin.md) step of the wizard.
* Veeam backup repository — select this option if you want to save the backup on a backup repository managed by a Veeam Backup & Replication server. With this option selected, you will pass to the [Backup Server](specify_backup_server_settings_lin.md) step of the wizard.

* Veeam Cloud Connect repository — select this option if you want to save the backup on a cloud repository exposed by the Veeam Cloud Connect service provider or on an object storage repository. With this option selected, you will pass to the [Cloud Repository](specify_cloud_backup_settings_lin.md) step of the wizard.

|  |
| --- |
| Important! |
| It is strongly recommended that you store backups in the external location like USB storage device, shared network folder or in the cloud. You can also keep your backup files on a separate non-system local drive. |

[![Choose Backup Destination](images/job_template_destination_lin.webp)](images/job_template_destination_lin.webp "Choose Backup Destination")


