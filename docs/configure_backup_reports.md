---
title: "Configuring Backup Reports"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/configure_backup_reports.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Configuring Backup Reports


Before you run a backup report, you must create and save a report configuration. A report configuration stores custom report settings, such as the scope of the report, scheduling settings and so on. You can create multiple report configurations with different report settings for different companies and locations.

Report configuration can be defined in the Veeam Service Provider Console Administrator Portal, Reseller Portal and Client Portal. Individual public report configurations created by the Administrator Portal users for a company are available to this company in the Client Portal and reseller managing this company in the Reseller Portal. Conversely, report configurations created in the Reseller Portal can be managed by the Administrator Portal users. For details on working with report configuration in the Client Portal, see [Guide for End Users](https://helpcenter.veeam.com/docs/vac/provider_user/configure_backup_reports.html?ver=9.2). For details on working with report configuration in the Reseller Portal, see [Guide for Resellers](https://helpcenter.veeam.com/docs/vac/reseller/configure_backup_reports.html?ver=9.2).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Configuring Backup Reports

To create a report configuration:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Reports.
2. Open the Configurations tab.
3. At the top of the list, click New and choose the report type:

* Virtual Machines — choose this option to create a report that will analyze VM data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.
* Data Backup — choose this option to create a report that will analyze unstructured data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.

* Computers — choose this option to create a report that will analyze computer data protection with Veeam backup agents.
* Databases — choose this option to create a report that will analyze cloud databases protection with Veeam Backup for Public Clouds.
* Microsoft 365 Objects — choose this option to create a report that will analyze whether Microsoft 365 objects protected with Veeam Backup for Microsoft 365 are compliant with SLA target.
* Cloud Networks — choose this option to create a report that will analyze virtual network configurations protection with Veeam Backup for Public Clouds.

Veeam Service Provider Console will open a report configuration wizard:

* [Virtual Machines](configure_vms_report.md)
* [Data Backup](configure_file_shares_report.md)

* [Computers](configure_computers_report.md)
* [Databases](configure_databases_report.md)
* [Microsoft 365 Objects](configure_vbo_sla_report.md)
* [Cloud Networks](configure_networks_report.md)


