---
title: "Updating Appliances"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_upgrade_appliances.html"
last_updated: "3/23/2026"
product_version: "9.1.0.30636"
---

# Updating Appliances


In Veeam Service Provider Console plugin, you can initiate upgrade of Veeam Backup for Public Clouds appliances without accessing remote computers or upload private fixes to up-to-date Veeam Backup for Public Clouds appliances.

|  |
| --- |
| Note: |
| In Veeam Service Provider Console, you can upgrade only the Veeam Backup for Public Clouds appliances. For details about updating the operating system, see Veeam Backup for Public Clouds User Guides:   * [Amazon Web Services](https://helpcenter.veeam.com/docs/vbaws/guide/upgrade_appliance_ui.html) * [Microsoft Azure](https://helpcenter.veeam.com/docs/vbazure/guide/updating_ui.html) * [Google Cloud](https://helpcenter.veeam.com/docs/vbgc/guide/updating_vb.html) |

Upgrading Veeam Backup for Public Clouds Appliances

To upgrade Veeam Backup for Public Clouds appliance:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.
5. Select the necessary appliance in the list.
6. At the top of the list, click Update and select Upgrade Appliance.

Uploading Files to Veeam Backup for Public Clouds Appliances

For the latest versions of managed Veeam Backup for Public Clouds appliances, you can obtain private fixes from Veeam Customer Technical Support. In Veeam Service Provider Console plugin, you can upload the obtained private fix file directly to the Veeam Cloud Connect server managing the appliance and update the appliance.

To update Veeam Backup for Public Clouds appliance using a private fix file:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.
5. Select the necessary appliance in the list.
6. At the top of the list, click Update and select Upload Patch File.
7. Select a private fix file that you want to upload to the appliance.

After the file is successfully uploaded, the appliance status will change to Warning.

1. Select the necessary appliance in the list.
2. At the top of the list, click Update and select Upgrade Appliance.

Checking Upgrade Results

To make sure that appliance upgrade has completed successfully, complete the following steps:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances and find the necessary appliance in the list.
5. Check the value in the Deployment Status column.

If upgrade was successful, the Deployment Status status must be Success.

1. Click a link in the Deployment Status column to display session details of the upgrade procedure.

If the appliance was upgraded successfully but the Deployment Status status is Error, click Clear Logs to update the status.


