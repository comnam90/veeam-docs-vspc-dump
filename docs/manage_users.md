---
title: "Managing Portal Users"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_users.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Managing Portal Users


Veeam Service Provider Console controls access to its functionality and monitoring data with the help of user roles. A user role defines what functionality, and what scope of data is available to a user or a user group in Veeam Service Provider Console. A user role also dictates whether a user or a group has access to the Veeam Service Provider Console Administrator Portal or Client Portal.

Administrator Portal

The Administrator Portal is the main configuration and management interface of Veeam Service Provider Console. In this portal, users act on behalf of the service provider and can perform management and administrative tasks.

To gain access to the Veeam Service Provider Console Administrator Portal, a user must have the Portal Administrator, Site Administrator, Portal Operator or Read-only User role assigned.

* A Portal Administrator has full access to all types of tasks in Veeam Service Provider Console.
* A Site Administrator has an activity scope limited to management of one Veeam Cloud Connect site.
* A Portal Operator has an activity scope limited to management of one or more companies.
* A Read-only User has an activity scope limited to monitoring data of one or more companies.

For details see, [Managing Administrator Portal Users](manage_admin_portal_users.md).

Client Portal

The Client Portal is a self-service area for companies that act as consumers of managed backup services. In this portal, users can monitor how much resources they have consumed, deploy Veeam backup agents, manage backup jobs, view invoices, perform basic configuration tasks and so on.

In the Administrator Portal, you can create and manage users for client companies. For details, see [Managing Company Users](manage_tenant_users.md).


