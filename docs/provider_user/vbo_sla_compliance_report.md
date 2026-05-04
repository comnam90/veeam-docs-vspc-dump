---
title: "Protected Microsoft 365 Objects Backup Report"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/vbo_sla_compliance_report.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Protected Microsoft 365 Objects Backup Report


The Protected Microsoft 365 Objects report analyzes the efficiency of Microsoft 365 workload protection with Veeam Backup for Microsoft 365.

* The Report Parameters section provides information about SLA, time period, types of objects in the report scope and mask for the objects excluded from the report scope.

* The report charts display information about the number of users, groups, sites and teams that meet and breach the target SLA.
* * The Details section provides information about all objects that meet and breach the target SLA including object name, number of available restore points, backup job name and destination, number of successful job sessions, Veeam Backup for Microsoft 365 server name, SLA percentage and configured job schedule in Coordinated Universal Time (UTC).

* The Objects that breach target SLA subsection displays a list of objects with SLA lower than the SLA value specified in the report configuration. Information on objects is grouped by Microsoft 365 organization.
* The Objects that meet target SLA subsection displays a list of objects with SLA equal to or greater than the SLA value specified in the report configuration. Information on objects is grouped by Microsoft 365 organization.

[![Protected Microsoft 365 Objects Report](images/generated_protected_vbo_report.webp)](images/generated_protected_vbo_report.webp "Protected Microsoft 365 Objects Report")
[![Protected Microsoft 365 Objects Report](images/generated_protected_vbo_report_table.webp)](images/generated_protected_vbo_report_table.webp "Protected Microsoft 365 Objects Report")


