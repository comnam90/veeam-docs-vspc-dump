---
title: "Backup Reporting"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/backup_reports.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Backup Reporting


To track the efficiency of data protection, you can create backup reports:

* Protected VMs report analyzes the efficiency of VM data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.

The report examines whether managed VMs have backup, replica or archive restore points, snapshots or replica snapshots created within the specified time range (RPO period) and whether managed VMs protected by CDP policies are compliant with SLA target.

Note that the report does not analyze data protection with backup copy and backup to tape jobs. To view VMs protected by these job types, go to the Protected Data > Virtual Machines tab. For details, see [Virtual Machines](export_protected_vms.md).

* Protected data backup report analyzes the efficiency of data protection with Veeam Backup & Replication and Veeam Backup for Public Clouds.

The report examines whether managed file shares have primary or archive restore points or snapshots created within last 30 days by data backup jobs, provides information on the completion status of recent data backup job sessions and percentage of processed data.

* Protected computers report analyzes the efficiency of computer data protection with Veeam backup agents.

The report examines whether managed computers have backup restore points created within the specified time range (RPO period), and provides information on the completion status of recent backup job sessions.

* Protected databases report analyzes the efficiency of database data protection with Veeam Backup for Public Clouds.

The report examines whether managed databases have backup or archive restore points, snapshots or replica snapshots created within last 30 days.

* Protected Microsoft 365 objects report analyzes the efficiency of Microsoft 365 object data protection with Veeam Backup for Microsoft 365.

The report examines whether protected Microsoft 365 objects are compliant with SLA target.

* Protected cloud networks report analyzes the efficiency of virtual network configuration protection with Veeam Backup for Public Clouds.

The report examines whether managed network configurations have backup restore points.

The reports can help you identify workloads that function without a proper protection, and make sure the existing backups or replicas meet established RPO requirements or comply with SLA target.

In Veeam Service Provider Console, you can generate backup reports and send them by email. Reports are sent as PDF files attached to report notifications. To automate reporting, you can configure a schedule according to which backup reports will be generated.

To access backup reports, you must have at least one managed Veeam product in the hosted or client infrastructure.

To get started with backup reports, keep to the following sequence of steps:

1. [Customize backup report logo and configure report notifications](configure_notifications_reports.md).

Customize the logo that must be displayed in backup reports, and configure report notifications.

1. [Configure backup report settings](configure_backup_reports.md).

Specify settings of backup reports. When you configure a backup report, you can create a schedule according to which the report must be generated. If you do not schedule backup reports, you will need to generate them manually.

1. [View backup reports](view_backup_report.md).

View reports generated manually or according to the configured schedule.


