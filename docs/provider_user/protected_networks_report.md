---
title: "Protected Cloud Networks Backup Report"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/protected_networks_report.html"
last_updated: "4/11/2024"
product_version: "9.1.0.30636"
---

# Protected Cloud Networks Backup Report


The Protected Cloud Networks report analyzes the efficiency of virtual network configuration protection with Veeam Backup for Public Clouds.

* The Report Parameters section provides information about company locations and platform type of cloud networks in the report scope.

* The report chart displays information about the number of network configurations protected with backup policies.

* The Details section provides information about all protected and unprotected network configurations including instance name, account name, region or subscription, appliance name, number of available restore points and date and time of the latest policy run.

* The Unprotected Instances subsection displays a list of network configurations that have outdated or missing restore points. Information on unprotected network configurations in each company location is grouped by backup policy.
* The Protected Instances subsection displays a list of network configurations that have at least one restore point created during the last 30 days. Information on protected databases in each company location is grouped by backup policy.

[![View Report Details](images/generated_protected_networks_report.webp)](images/generated_protected_networks_report.webp "View Report Details")


