---
title: "Managing Locations"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/manage_locations.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Managing Locations


Your company may run multiple Veeam products located in different remote offices and branch offices (ROBO). To differentiate backup services and cloud resources consumed by each office, you can use locations.

A location is a logical group that can include one or more managed Veeam backup agents, Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE and Veeam Backup for Microsoft 365 servers. By default, all managed machines are grouped into a preconfigured system location — Remote location. All jobs and workloads on Veeam Backup & Replication and Veeam Backup for Microsoft 365 servers and Veeam Backup for Public Clouds appliances assigned to your company by service provider, are grouped into a preconfigured Hosted location. In addition to the system locations, you can create locations for remote and branch offices where you have managed Veeam products, and move managed machines to these locations.

Locations are leveraged in different areas of Veeam Service Provider Console, and can be very useful when it comes to controlling the scope of information about managed objects and grouping details about protected workloads in reports and invoices.

Tracking Consumed Services in Invoices

You can use locations to keep track of the type and amount of backup services and cloud resources consumed by different offices or business units in your company. If you configure multiple locations for your company, invoices will provide a breakdown of costs by location. Thus, you can track the cost of backup services provided for specific locations.

For details on details available in invoices, see [Viewing and Downloading Invoices](view_invoices.md).

Limiting Data Scope in the Client Portal

Locations can serve as an instrument of controlling the scope of data that must be available to company users in the Client Portal. When you create a new Location Administrator or Location User, you can choose locations that must be available to this user. By assigning specific locations to a user, you limit the scope of managed Veeam backup agents, Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE and Veeam Backup for Microsoft 365 servers whose details will be available to the user in the Client Portal.

For details on working with portal users, see [Managing Portal Users](manage_users.md).

Filtering Data in Monitoring Dashboards and Alarms

You can use locations to filter the scope of monitoring data.

Monitoring dashboards in the Client Portal allow you either to filter or sort monitoring data by location, so that you could concentrate on details pertaining to specific offices or business units within your company.

For details on monitoring dashboards, see [Monitoring](summary.md).

Veeam Service Provider Console alarms also come with support for locations. Veeam Service Provider Console includes predefined alarms that allow you to track the amount of cloud repository space consumed by each location, and alert on unprotected VMs in company offices. To fine-tune alerting, you can also customize alarms to suit the needs of different offices, and assign these alarms to specific locations.

For details on alarms, see [Working with Alarms](alarms.md).

In This Section

* [Creating Locations](create_locations.md)
* [Setting Locations](set_location_quotas.md)
* [Modifying Locations](modify_locations.md)
* [Removing Locations](remove_locations.md)


