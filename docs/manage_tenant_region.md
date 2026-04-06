---
title: "Managing Company Region"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_tenant_region.html"
last_updated: "10/27/2025"
product_version: "9.1.0.30636"
---

# Managing Company Region


If you have a large number of client companies distributed across one country, you can set geographical regions for these companies to simplify alarms management and health state monitoring. After you set a geographical region for a company, you will be able to monitor the company health state in the Organizations Health widget and drill down to alarms triggered for all companies in a specific country. For details, see [Overview](overview.md).

Alternatively, you can set a region while creating or modifying a company account. For details, see [Step 2. Specify Company Details](specify_company_details.md).

|  |
| --- |
| Note: |
| Veeam Service Provider Console obtains data on geographical regions from a 3rd party resource. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Managing Company Region

To set or modify a geographical region for a managed company:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary company on the list and click a link in the Country column.

If the column is hidden, click the ellipsis on the right of the list header. In the list of properties that must be displayed, select Country.

Note that a link in the Country column will be inactive if a company configuration task is running or if the previous configuration task has failed.

1. In the Set Company Location window, select a new geographical region for a managed company.

To select a specific region, use the drop-down list at the top of the map or click the necessary region on the map. To zoom out of the selected region, click Go Back.

1. Click Save.

[![Set Company Region](images/set_company_location.webp)](images/set_company_location.webp "Set Company Region")

Removing Company Region

To remove a geographical region for a managed company, you must edit the company account settings. For details, see [Modifying Company Settings](modify_tenants.md).


