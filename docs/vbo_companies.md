---
title: "Configuring Companies Integration"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbo_companies.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Configuring Companies Integration


You can select Veeam Backup for Microsoft 365 organizations which you want to link to Veeam Service Provider Console companies. To do that, you must configure mapping in Veeam Service Provider Console. Mapping triggers synchronization of organizations data, including configured jobs, protected objects and license usage information, allows you to manage Veeam Backup for Microsoft 365 jobs and monitor the number of organizations licensed users, and includes organization data in Veeam Service Provider Console license usage reports for more detailed reporting.

Prerequisites

Before configuring integration of managed companies, enable the Company Mapping integration feature. For details, see [Enabling Veeam Backup for Microsoft 365 Integration](vbo_enable_integration.md).

|  |
| --- |
| Note: |
| This functionality is available for Veeam Backup for Microsoft 365 version 7 or later. |

Configuring Companies Integration

To configure integration between companies in Veeam Service Provider Console and Veeam Backup for Microsoft 365, you can do either of the following:

* [Create new companies in Veeam Service Provider Console](vbo_create_new_company.md).

Use this method if you want to create company accounts in Veeam Service Provider Console and tenant accounts in Veeam Cloud Connect for organizations that you already manage in Veeam Backup for Microsoft 365.

* [Register new Microsoft 365 organizations](vbo_register_organization.md).

Use this method if you want to register Microsoft 365 organizations in Veeam Backup for Microsoft 365 for companies that you already manage in Veeam Service Provider Console.

* [Create mapping between companies in Veeam Backup for Microsoft 365 and Veeam Service Provider Console](vbo_map_companies.md).

Use this method if you have company accounts registered in Veeam Service Provider Console and you want to map them to Veeam Backup for Microsoft 365 organization accounts.


