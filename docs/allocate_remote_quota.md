---
title: "Configure Remote Services"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/allocate_remote_quota.html"
last_updated: "9/9/2025"
product_version: "9.1.0.30636"
---

# Configure Remote Services


On the Remote Services tab, select which remote services you allow the company to manage:

1. In the Managed backup section, select which Veeam products you allow the company to manage:

* To allow company to manage Veeam backup agents, set the Backup agents management toggle to On.

To define the number of Veeam backup agents, for each Veeam backup agent running mode:

1. Clear the Do not set any limit check box.
2. Specify the maximum number of Veeam backup agents you allow a company to manage.

The agent quotas are soft quotas and put no physical restriction on the repository. When the company reaches the specified quota, Veeam Service Provider Console triggers the Company workstation agents quota or Company server agents quota alarm. You can customize these alarms in accordance with your requirements. For details, see [Modifying Alarm Settings](modify_alarm_settings.md).

* To allow a company to manage Veeam Backup & Replication servers, Veeam backup agents managed by Veeam Backup & Replication servers and Veeam Backup for Public Clouds appliances, set the Backup servers management toggle to On.

To limit the amount of backup repository storage space for the company, clear the Do not set any limit check box and specify the repository quota.

The Repository quota is a soft quota and puts no physical restriction on the repository. When the company reaches the specified quota, Veeam Service Provider Console triggers the Remote backup repository storage quota alarm. You can customize this alarm in accordance with your requirements. For details, see [Modifying Alarm Settings](modify_alarm_settings.md).

1. In the Microsoft 365 section, set the Microsoft 365 managed backup toggle to On if you want to allow company to manage remote Microsoft 365 servers.

To limit the amount of Veeam Backup for Microsoft 365 repository storage space for the company, clear the Do not set any limit check box and specify the repository quota.

The Repository quota is a soft quota and puts no physical restriction on the repository. When the company reaches the specified quota, Veeam Service Provider Console triggers the Microsoft 365 backup repository storage quota alarm. You can customize this alarm in accordance with your requirements. For details, see [Modifying Alarm Settings](modify_alarm_settings.md).

1. In the Public clouds section, set the Public cloud managed backup toggle to On if you want to allow company users to manage remote Amazon Web Services, Microsoft Azure and Google Cloud public clouds.

[![Allocate Remote Sevice Quota](images/remote_service_quota.webp)](images/remote_service_quota.webp "Allocate Remote Sevice Quota")


