---
title: "Viewing Backup Reports"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/view_backup_report.html"
last_updated: "10/2/2024"
product_version: "9.1.0.30636"
---

# Viewing Backup Reports


Backup reports that were generated manually or automatically, according to a specified schedule, are saved in the All Reports list. Backup reports are available as PDF documents that you can download and view.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator, Read-only User.

Viewing Backup Reports

To view a backup report:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Reports.

Veeam Service Provider Console will display a list of all generated backup reports. To narrow down the list of reports, you can use the following filters:

* Report — search backup reports by report configuration name.
* Type — limit the list of reports by type (All, Protected VMs (RPO & SLA), Protected data backup (RPO), Protected computers (RPO), Protected databases (RPO), Microsoft 365 object backup (SLA), Protected cloud networks (RPO)).
* (For Portal Administrator, Site Administrator) Managing company — limit the list of report by the type of user who created the report configuration (All, My company, Reseller).
* Report configuration — limit the list of reports by configuration type (All, Individual report, Summary report).

* Time period — limit the list of backup reports by generation date or period.

* Site/Reseller/Company/Location — limit the list of reports by Veeam Cloud Connect site, company and location to which reports belong. To limit the list of reports by site, reseller, company and location, use filters at the top left corner of the Veeam Service Provider Console window.

1. Select the necessary backup report in the list and click View at the top of the list.

Alternatively, you can right-click the necessary report and choose View or click a link in the Report column.

The backup report PDF file will be saved to the default download location on your computer.

In Veeam Service Provider Console you can view the following summary and individual backup reports:

* [Protected VMs](protected_vms_report.md)

* [Protected Data Backup](protected_file_shares_report.md)
* [Protected Computers](protected_computers_report.md)
* [Protected Databases](protected_databases_report.md)
* [Protected Microsoft 365 Objects](vbo_sla_compliance_report.md)
* [Protected Cloud Networks](protected_networks_report.md)


