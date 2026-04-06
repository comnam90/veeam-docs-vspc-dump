---
title: "Adding Veeam Backup for Google Cloud Appliances"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_add_google.html"
last_updated: "6/25/2024"
product_version: "9.1.0.30636"
---

# Adding Veeam Backup for Google Cloud Appliances


To allow Veeam Service Provider Console to communicate with a hosted Veeam Backup for Google Cloud appliance, you must configure a connection to the appliance:

* [Connect to existing Veeam Backup for Google Cloud appliances](clouds_connect_google.md).

If you have already deployed Veeam Backup for Google Cloud appliances, you can register these appliances in Veeam Service Provider Console.

* [Deploy new Veeam Backup for Google Cloud appliances](clouds_deploy_google.md).

If you have not yet deployed Veeam Backup for Google Cloud appliances, you can deploy them using Veeam Service Provider Console plugin. In this case, Veeam Service Provider Console will connect to Google Cloud and deploy new instances of Veeam Backup for Google Cloud.

Prerequisites

Before you start adding Veeam Backup for Google Cloud appliances, consider requirements specified in the [Planning and Preparation](https://helpcenter.veeam.com/docs/vbgc/guide/planning.html) section of the Veeam Backup for Google Cloud User Guide.

|  |
| --- |
| Note: |
| To avoid performance issues, it is not recommended to deploy more than 20 appliances on one Google Cloud project. |


