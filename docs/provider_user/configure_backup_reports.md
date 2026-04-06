---
title: "Configuring Backup Reports"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/configure_backup_reports.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Configuring Backup Reports


Before you run a backup report, you must create and save a report configuration. A report configuration stores custom report settings, such as the scope of the report, scheduling settings and so on. You can create multiple report configurations with different report settings for different locations.

Report configuration can be defined both in the Veeam Service Provider Console Administrator Portal and Client Portal. Some report configurations created by the Portal Administrator for your company are available in your Client Portal. Report configurations created in your Client Portal are not available for the Portal Administrator.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Location Administrator.

Configuring Backup Reports

To create a report configuration:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Reports.
2. Open the Configurations tab.
3. At the top of the list, click New and choose the report type:

* Virtual Machines — choose this option to create a report that will analyze VM data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.
* Data Backup — choose this option to create a report that will analyze data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.

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


