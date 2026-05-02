---
title: "Restoring Veeam Backup for Public Clouds Workloads"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/restore_clouds.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Restoring Veeam Backup for Public Clouds Workloads


To restore Veeam Backup for Public Clouds VMs, file shares and database instances, you can access Veeam Backup for Public Clouds portal directly from Veeam Service Provider Console.

To access Veeam Backup for Public Clouds portal:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Protected Data.
2. Open the necessary tab:

* Virtual Machines > Public Clouds — select this tab to restore cloud VMs
* Data Backup > Public Clouds — select this tab to restore cloud file shares
* Cloud Databases — select this tab to restore cloud databases
* Cloud Networks — select this tab to restore virtual network configurations

1. Select the necessary workload in the list.
2. At the top of the list, click Restore and select restore type.

Alternatively, you can right-click the necessary workload, choose Restore and select restore type.

Veeam Service Provider Console will open a Veeam Backup for Public Clouds restore wizard.

For details on Veeam Backup for Veeam Backup for Public Clouds restore, see the following sections of the Veeam Backup for Veeam Backup for Public Clouds User Guides:

* [Performing Restore](https://helpcenter.veeam.com/docs/vbaws/guide/recovery.html) of the Veeam Backup for AWS User Guide
* [Performing Restore](https://helpcenter.veeam.com/docs/vbazure/guide/performing_restore.html) of the Veeam Backup for Microsoft Azure User Guide
* [Performing Restore](https://helpcenter.veeam.com/docs/vbgc/guide/performing_restore.html) of the Veeam Backup for Google Cloud User Guide


