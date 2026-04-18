---
title: "Moving Veeam Agent Backups"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/appendix_move_backups.html"
last_updated: "4/17/2026"
product_version: "9.2.0.33215"
---

# Moving Veeam Agent Backups


This section describes how to place existing Veeam agent backups in a cloud repository in the Veeam Cloud Connect infrastructure so that the Veeam backup agent job continues the existing backup chain. The scenarios described in this section can be helpful when you need to back up a large amount of data to the Veeam Cloud Connect repository but the network connection is slow. In this case, you can create backups locally and move them to the Veeam Cloud Connect repository.

This section covers the following scenarios:

* [Move a backup to a simple backup repository used as a cloud repository](#simple).
* [Move a backup to a scale-out backup repository used as a cloud repository](#sobr).

How It Works

Mapping of a backup job to the previously made backups is performed in the following way:

1. Service provider moves local backup files to the target repository.
2. Veeam Backup Administrator rescans the repository in the Veeam Backup & Replication console.
3. Veeam Service Provider Console Portal Administrator restarts the Veeam backup agent job in the Veeam Service Provider Console portal.

Moving Backup to Simple Backup Repository

Use this scenario if you want to move a locally stored backup to a simple backup repository used as a cloud repository. For details about simple backup repositories, see the [Backup Repositories](https://helpcenter.veeam.com/docs/vbr/userguide/backup_repository.html?ver=13) section in the Veeam Backup & Replication User Guide.

To move Veeam agent backups to a simple repository:

1. The service provider must move locally stored backup files to the cloud repository:

1. Browse to the folder where Veeam backup repository stores backup files. For example, C:\Backup.

For details, see the [Configure Backup Repository Settings](https://helpcenter.veeam.com/docs/vbr/userguide/repository_repository.html?ver=13) section of the Veeam Backup & Replication User Guide.

1. In the C:\Backup folder, create a new folder in the following format:

* [For tenant accounts] C:\Backup\<tenant\_name>\<folder\_name>
* [For subtenant accounts] C:\Backup\<tenant\_name>\Users\<subtenant\_name>\<folder\_name>

where:

* <tenant\_name> — name of the tenant account used to connect to the service provider. For details, see the [Tenant Account Credentials](https://helpcenter.veeam.com/docs/backup/cloud/cloud_tenant_creds.html) section of the Veeam Cloud Connect Guide.
* <subtenant\_name> — name of the subtenant account used to connect to the service provider. For details, see the [Managing Subtenant Accounts on SP Side](https://helpcenter.veeam.com/docs/backup/cloud/cloud_connect_subtenants_manage.html) section of the Veeam Cloud Connect Guide.
* <folder\_name> — name of the target folder to store backups. You can use the name of the original backup job or specify a new name for the folder.

For example: C:\Backup\ABC\_Company\System\_Backup or C:\Backup\ABC\_Company\Users\John\_Smith\System\_Backup.

1. Move all backup files to the folder created at step 2 using external tools.

1. The Veeam Backup Administrator must rescan the cloud repository.

For details on how to rescan a repository, see the [Rescanning Backup Repositories](https://helpcenter.veeam.com/docs/vbr/userguide/rescanning_backup_repositories.html?ver=13) section in the Veeam Backup & Replication User Guide.

The information about the added backup will be displayed in the rescan job session window.

1. The Veeam Service Provider Console Portal Administrator must restart Veeam backup agent job:

1. Edit the Veeam backup agent job:

1. At the Destination step of the wizard, select Veeam Cloud Connect repository.
2. At the Credentials step of the wizard, specify credentials for the Veeam Cloud Connect tenant or subtenant account.
3. At the Backup Resources step of the wizard, choose the necessary Veeam Cloud Connect repository.
4. At the Summary step of the wizard, click Finish to save changes.

1. Run the Veeam backup agent job.

The backup job will continue the backup chain for the full backup that was moved to the cloud repository.

Moving Backup to Scale-Out Backup Repository

Use this scenario if you want to move a locally stored backup to a scale-out backup repository used as a cloud repository. For details about scale-out backup repositories, see the [Scale-Out Backup Repositories](https://helpcenter.veeam.com/docs/vbr/userguide/backup_repository_sobr.html?ver=13) section of the Veeam Backup & Replication User Guide.

|  |
| --- |
| Important! |
| Before you move the backup files, make sure that the backup job name, the target backup folder name, the VBM filename, names of VBM files and paths to VBM files meet the following requirements:   * The names contain only allowed alphanumeric characters: a-z, A-Z, 0-9. * The names contain only allowed special characters: \_ - . + = @ ^. * The names of VBM files and paths to VBM files do not contain spaces. If the names or the paths contain spaces, replace them with underscores. |

To move Veeam agent backups to a scale-out backup repository:

1. The service provider must move locally stored backup files to the cloud repository:

1. Browse to the folder where the cloud repository stores backup files. For example, C:\Backup.

For more information, see the [Configure Backup Repository Settings](https://helpcenter.veeam.com/docs/vbr/userguide/repository_repository.html?ver=13) section of the Veeam Backup & Replication User Guide.

1. In the C:\Backup folder, create new folders for each extent of the scale-out backup repository. The folders must be in the following format:

* [For tenant accounts] C:\Backup\<extent\_name>\<tenant\_name>\<folder\_name>
* [For subtenant accounts] C:\Backup\<extent\_name>\<tenant\_name>\Users\<subtenant\_name>\<folder\_name>

where:

* <extent\_name> — name of the backup repository you use as an extent. For details, see the [Add Performance Extents](https://helpcenter.veeam.com/docs/vbr/userguide/sobr_add_extents.html?ver=13) section of the Veeam Backup & Replication User Guide.
* <tenant\_name> — name of the tenant account that you use to connect to the service provider. For details, see the [Tenant Account Credentials](https://helpcenter.veeam.com/docs/backup/cloud/cloud_tenant_creds.html) section of the Veeam Cloud Connect Guide.
* <subtenant\_name> — name of the subtenant account that you use to connect to the service provider. For details, see the [Managing Subtenant Accounts on SP Side](https://helpcenter.veeam.com/docs/backup/cloud/cloud_connect_subtenants_manage.html) section of the Veeam Cloud Connect Guide.
* <folder\_name> — name of the target folder to store backups. You can use the name of the original backup job or specify a new name for the folder.

For example, C:\Backup\Extent\_1\ABC\_Company\System\_Backup or C:\Backup\Extent\_1\ABC\_Company\Users\John\_Smith\System\_Backup.

1. Copy the VBM file to both folders created at step 2 using external tools.
2. Copy the VBK and VIB files to the folders created at step 2 using external tools according to the placement policy specified for the backup repository. For details, see the [Backup File Placement](https://helpcenter.veeam.com/docs/vbr/userguide/backup_repository_sobr_placement.html?ver=13) section of the Veeam Backup & Replication User Guide.

1. The Veeam Backup Administrator must rescan the cloud repository.

For details on how to rescan the repository, see the [Rescanning Backup Repositories](https://helpcenter.veeam.com/docs/vbr/userguide/rescanning_backup_repositories.html?ver=13) section of the Veeam Backup & Replication User Guide.

The information about the added backup will be displayed in the rescan job session window.

1. The Veeam Service Provider Console Portal Administrator must restart the Veeam backup agent job:

1. Edit the Veeam backup agent job:

1. At the Destination step of the wizard, select Veeam Cloud Connect repository.
2. At the Credentials step of the wizard, specify settings for the Veeam Cloud Connect tenant or subtenant account.
3. At the Backup Resources step of the wizard, choose the necessary Veeam Cloud Connect repository.
4. At the Summary step of the wizard, click Finish to save changes.

1. Run the Veeam backup agent job.

The backup job will continue the backup chain for the full backup that was moved to the cloud repository.


