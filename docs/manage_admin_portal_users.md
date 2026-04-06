---
title: "Managing Administrator Portal Users"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_admin_portal_users.html"
last_updated: "7/10/2025"
product_version: "9.1.0.30636"
---

# Managing Administrator Portal Users


By default, the only user that can access the Administrator Portal on behalf of a service provider is Portal Administrator. Veeam Service Provider Console grants this role to members of the Local Administrators user group on the machine where Veeam Service Provider Console Server component is installed.

To allow other users to work with the Veeam Service Provider Console Administrator Portal, you can assign them the following roles:

* Portal Administrator — can perform all administrative activities in Veeam Service Provider Console including: performing portal configuration, creating and managing reseller and company accounts, managing subscription plans and invoices, accessing data of all managed client companies, and so on.

To learn how to create and manage Portal Administrators, see [Managing Portal Administrators](manage_admins.md).

* Site Administrator — can perform administrative activities in Veeam Service Provider Console limited to one Veeam Cloud Connect site and manage all client companies registered on this site.

To learn how to create and manage Site Administrators, see [Managing Site Administrators](manage_site_admins.md).

* Portal Operator — can perform full management for companies in the access scope, but cannot create or remove companies.

To learn how to create and manage Portal Operators, see [Managing Portal Operators](manage_operators.md).

* Read-only User — can monitor data of companies in the access scope. You can assign a Read-only User role to third party users who will have access to monitoring data but will not be able to perform any management actions.

To learn how to create and manage Read-only Users, see [Managing Read-only Users](manage_read_only_users.md).

User Permissions

The following table describes what functionality is available to users in the Administrator Portal in accordance with their user role.

User Permissions

| Functionality | Portal Administrator | Site Administrator | Portal Operator | Read-only User |
| Configuration tasks | Full | Only for managed Veeam Cloud Connect site | Only managed companies users | Read (only managed companies users) |
| Plugin library | Full | N/A | N/A | N/A |
| Resellers | Full | N/A | N/A | N/A |
| Client companies | Full | Full\* | Full (except for creation and removal) | Read |
| Managed computers | Full | Full\* | Full | Read |
| Discovery rules | Full | Full\* | Full | Read |
| Veeam backup agent | Full | Full\* | Full | Read |
| File-level restore | Full | Full\* | Full | N/A |
| Veeam Backup & Replication | Full | Full\* | Full | Read |
| Assigning hosted jobs | Full | Read | Read | Read |
| Veeam Backup for Public Clouds | Full | Full\* | Full | Read |
| Failover plans | Full | Full\* | Full | Read |
| Veeam Backup for Microsoft 365 | Full | Full\* | Full | Read |
| Veeam ONE | Full | Full\* | Full | Read |
| Licensing | Full | N/A | N/A | N/A |
| Invoices | Full | Full\* | Full | Read |
| Backup reports | Full | Full\* | Full | Read |
| Monitoring | Read | Read\* (except for Trends and Overview) | Read (except for Trends and Overview) | Read (except for Trends and Overview) |
| Active alarms | Full | Full\* | Full | Read |
| Protected data | Read | Read\* | Read | Read |
| Logs | Full | Full\* (except for Veeam Service Provider Console logs) | Full (except for Veeam Service Provider Console logs) | N/A |
| Support cases | Full | N/A | N/A | N/A |

\* Limited to companies registered on the managed Veeam Cloud Connect site.


