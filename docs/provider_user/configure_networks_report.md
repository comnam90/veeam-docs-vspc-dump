---
title: "Creating Protected Cloud Networks Report"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/configure_networks_report.html"
last_updated: "8/13/2025"
product_version: "9.1.0.30636"
---

# Creating Protected Cloud Networks Report


To create a Protected Cloud Networks report configuration:

1. At the Name step of the wizard, specify the report name and description.

The report name and description will be displayed in reports generated based on this report configuration.

[![Specify Report Name and Description](images/backup_report_name_network.webp)](images/backup_report_name_network.webp "Specify Report Name and Description")

1. At the Locations step of the wizard, select one or more company locations. Use the search field at the top to find the necessary location.

By choosing a location you can limit the scope of the report: only databases that belong to the chosen locations will appear in the report.

[![Choose Locations](images/backup_report_locations_network.webp)](images/backup_report_locations_network.webp "Choose Locations")

1. At the Parameters step of the wizard, specify cloud platform that must be included in the report (All, Amazon Web Services, Microsoft Azure).

[![Specify Report Parameters](images/backup_report_parameters_network.webp)](images/backup_report_parameters_network.webp "Specify Report Parameters")

1. At the Schedule step of the wizard, specify a schedule according to which the report must be generated:

1. In the Scheduling options section, select the Generate this report automatically check box to enable scheduling and define report scheduling:

1. To generate the report at specific time daily, on defined week days or with specific periodicity, select the Daily at option. Use the fields on the right to configure the necessary schedule.
2. To generate the report once a month on specific days, select the Monthly at option. Use the fields on the right to configure the necessary schedule.
3. From the Time zone drop-down list, select the time zone in which the daily or monthly schedule must be run.

1. In the Notification options section, provide the email address to which the report must be sent.

You can specify multiple email addresses separated with commas (,) or semicolons. To send a notification to multiple users with a specific role, you can use email variables. For a list of available email variables, click View Help.

To receive the report, the user must configure an email address in the user profile. For details, see .

[![Specify Report Schedule](images/backup_report_schedule_network.webp)](images/backup_report_schedule_network.webp "Specify Report Schedule")

1. At the Summary step of the wizard, review the report configuration and click Finish.

[![Review Report Configuration](images/backup_report_review_network.webp)](images/backup_report_review_network.webp "Review Report Configuration")


