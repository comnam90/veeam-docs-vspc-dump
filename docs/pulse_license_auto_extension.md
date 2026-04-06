---
title: "Enabling Automatic License Reporting"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_license_auto_extension.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Enabling Automatic License Reporting


You can configure Veeam Service Provider Console to report on VCSP Pulse license keys automatically. Automatically reported licenses are valid for 2,5 months and will be automatically updated if you submit the license usage report for these licenses. For details, see [Submitting License Usage Report](submit_license_usage_report.md).

|  |
| --- |
| Note: |
| This functionality is available only if you have license-level reporting enabled for your VCSP Pulse account. For details on how to enable license-level reporting, see section [Automatic License Reporting](https://helpcenter.veeam.com/docs/vcsp/refguide/automatic_license_reporting.html) of the Veeam Rental Licensing and Usage Reporting Reference Guide.  If you have a No Commit contract configured in VCSP Pulse, automatic license reporting will be enabled by default and you will not be able to change the setting.  You cannot enable automatic reporting for license keys with Multi-Customer Usage usage type. |

To enable automatic license reporting:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click License Keys.

Veeam Service Provider Console will display a list of all license keys managed in VCSP Pulse.

1. Select the necessary license keys.

To select only license keys with disabled automatic reporting, click Filter, in the Automatic Reporting section select Disabled, and click Apply.

1. At the top of the list, set the Automatic Reporting toggle to On.

Disabling Automatic License Reporting

To disable automatic license reporting:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click License Keys.

Veeam Service Provider Console will display a list of all license keys managed in VCSP Pulse.

1. Select the necessary license keys.

To select only license keys with enabled automatic reporting, click Filter, in the Automatic Reporting section select Enabled, and click Apply.

1. At the top of the list, set the Automatic Reporting toggle to Off.


