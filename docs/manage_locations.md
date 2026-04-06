---
title: "Managing Locations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_locations.html"
last_updated: "2/21/2025"
product_version: "9.1.0.30636"
---

# Managing Locations


A client company may run multiple Veeam products located in different remote offices and branch offices (ROBO). To differentiate backup services and cloud resources consumed by each company office, you can use locations.

A location is a logical group that can include one or more managed Veeam backup agents, Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE and Veeam Backup for Microsoft 365 servers. By default, all managed machines of a company are grouped into a preconfigured system location — Remote. All jobs and workloads on Veeam Backup & Replication and Veeam Backup for Microsoft 365 servers and Veeam Backup for Public Clouds appliances assigned to a company by service provider, are grouped into a preconfigured Hosted location. In addition to the system locations, you can create locations for remote and branch offices where a client company has managed Veeam products, and move managed machines to these locations.

Locations are leveraged in different areas of Veeam Service Provider Console, and can be useful when it comes to controlling the scope of information about managed objects and grouping details about protected workloads in reports and invoices.

Tracking Consumed Services in Invoices

You can use locations to keep track of the type and amount of backup services, hosted and cloud resources consumed by different offices or business units of a company. If you configure multiple locations for a company, invoices will provide a breakdown of costs by location. Thus, you can track the cost of backup services provided for specific locations.

Note that some resources consumption and services usage cannot be tracked by location in invoices. For example, cloud repository tiers and insider protection usage will be assigned to Remote location even if these services are distributed among different locations.

For information on details available in invoices, see [Viewing and Downloading Invoice Details](export_invoice_details.md).

Limiting Data Scope in the Client Portal

Locations can serve as an instrument of controlling the scope of data that must be available to company users in the Client Portal. When you create a new Location Administrator or Location User, you can choose locations that must be available to this user. By assigning specific locations to a user, you limit the scope of managed Veeam backup agents, Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE and Veeam Backup for Microsoft 365 servers whose details will be available to the user in the Client Portal.

For details on working with portal users, see [Managing Portal Users](manage_users.md).

Filtering Data in Monitoring Dashboards and Alarms

You can use locations to filter the scope of monitoring data.

For details on monitoring dashboards, see [Monitoring](monitoring.md).

Veeam Service Provider Console alarms also come with support for locations. Veeam Service Provider Console includes predefined alarms that allow you to track the amount of cloud repository space consumed by each company location, and alert on unprotected VMs in company offices. To fine-tune alerting, you can also customize alarms to suit the needs of different offices, and assign these alarms to specific locations.

For details on alarms, see [Working with Alarms](alarms.md).

You can also use geographical regions to manage triggered alarms and monitor companies health states. For details, see [Managing Company Region](manage_tenant_region.md) and [Managing Reseller Region](manage_reseller_region.md).

In This Section

* [Creating Locations](create_locations.md)
* [Setting Locations](set_location_quotas.md)
* [Modifying Locations](modify_locations.md)
* [Removing Locations](remove_locations.md)


