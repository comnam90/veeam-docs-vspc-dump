---
title: "Protected Computers Backup Report"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/protected_computers_report.html"
last_updated: "8/22/2025"
product_version: "9.1.0.30636"
---

# Protected Computers Backup Report


The Protected Computers report analyzes the efficiency of computer data protection with Veeam backup agents.

* The Report Parameters section provides information about RPO and operation mode of Veeam backup agents that run on computers in the report scope, mask for the computers excluded from the report scope, the way Veeam backup agent data is grouped in the report, Veeam backup agent management type and guest OS. For individual report, this section provides information about company locations in the report scope. For summary report, this section provides information about the number of companies in the report scope and inclusion of company details in the report.

* [For individual report] The Summary section includes information about the number of company locations in the report scope and the number of discovered, protected and unprotected computers in each location.
* The report charts display information about protected and unprotected computers. For summary report, the charts display information about servers and workstations state. For individual report, the charts display information about the number of protected computers, type and platform of computers protected with Veeam backup agents, the latest backup status of each job on protected computers, and reasons for a failure to meet RPO requirements.

* [For summary report] The Overview section provides information about the number of protected and unprotected computers for each company in the report scope.

* The Details section provides information about all protected and unprotected computers including host name, management type, backup policy name, backup source and target, number of available restore points, guest OS, and date and time of the latest backup.

For summary report, the Details section is included only if you have selected the Include detailed information to the report check box during report configuration.

* The Unprotected Agents subsection displays a list of hosted and client computers that do not have valid restore points within the configured RPO period. Information on unprotected computers in each company location is grouped by the age of the latest backup files.
* The Protected Agents subsection displays a list of hosted and client computers that have at least one restore point that meets RPO requirements specified in the report configuration. Information on protected computers in each company location is grouped by Veeam backup agent or backup policy, as configured in the report parameters.

[![View Report Details](images/generated_protected_computers_report.webp)](images/generated_protected_computers_report.webp "View Report Details")


