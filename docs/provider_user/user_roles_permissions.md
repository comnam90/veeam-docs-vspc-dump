---
title: "User Roles and Permissions"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/user_roles_permissions.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# User Roles and Permissions


When you create a new user who can work with the Veeam Service Provider Console Client Portal, you must assign a role to this user. A user role defines permissions for a user, that is, what operations a user can perform, and what scope of data is available to a user in the Client Portal.

|  |
| --- |
| Note: |
| * Your service provider can limit permissions scope for your company. In this case, some job or policy management actions may become unavailable for all user roles. For the list of permissions available to your company, contact your service provider. * You cannot view job session details for jobs configured on Veeam Backup for Microsoft 365 and Veeam Backup & Replication servers that were assigned to you by your service provider. * You cannot view policy session details for policies configured on Veeam Backup for Public Clouds appliances that were assigned to you by your service provider. |

Company Owner

Company Owner is the primary user acting on behalf of a company that consumes provided backup services. The Company Owner user is created when a company account is registered in Veeam Service Provider Console. For each company, there can be only one Company Owner.

You can think of the Company Owner as of a super user at the company level. In the Client Portal, the Company Owner has access to all monitoring and billing data for all company locations, and can perform all types of available configuration and management operations.

Company Administrator

Company Administrator has a similar set of privileges as the Company Owner, but cannot modify or remove Company Owner.

Company Tenant

Company Tenant has a similar set of privileges as the Company Owner, with the following limitations:

* Company Tenant does not have access to billing information, discovery rules, backup reports or Veeam Backup for Public Clouds workloads.
* Company Tenant cannot create, modify or remove locations.
* The scope of data available to a Company Tenant is limited to one Veeam Cloud Connect tenant.

Location Administrator

Location Administrator has a similar set of privileges as the Company Owner, with the following limitations:

* Location Administrator does not have access to billing information.
* Location Administrator cannot create, modify or remove locations.
* The scope of data available to a Location Administrator can be limited to one or more company locations.

Location User

Location User has access to company monitoring data but cannot perform most configuration and management tasks. This user can only work with the functionality available in the Veeam Service Provider Console Client Portal. Data available to a Location User can be limited to one or more company locations, and the user can access data pertaining to all managed Veeam products in these locations.

Subtenant

Subtenant is a user who has cloud repository resources allocated and acts as a subtenant in Veeam Cloud Connect. This user can store backups created with Veeam backup agent, using own credentials. In addition, a Subtenant has access to the Client Portal. The scope of monitoring data available to a Subtenant in the Client Portal is limited to a computer (or computers) that is protected with Veeam backup agent, and whose data is stored on a cloud repository.

For details on Veeam Cloud Connect subtenants, see section [Subtenants](https://helpcenter.veeam.com/docs/backup/cloud/cloud_connect_subtenants.html) of the Veeam Cloud Connect Guide.

Company Invoice Auditor

Company Invoice Auditor has access to billing details pertaining to a company. This user can view invoices and receive billing notifications.

User Permissions

The following table describes what functionality is available to company users in the Client Portal in accordance with their user role.

User Permissions

| Functionality | Company Owner | Company Administrator | Company Tenant | Location Administrator | Location User | Subtenant | Company Invoice Auditor |
| Configuration tasks (locations, portal users, backup policies, alarms, company info, plugin library) | Full | Full | Only portal users (can only create subtenants) | Only portal users | N/A | N/A | N/A |
| Managed computers | Full | Full | Full | Full | Read | N/A | N/A |
| Discovery rules | Full | Full | N/A | Full | N/A | N/A | N/A |
| Veeam backup agents | Full | Full | Full | Full | Read | Read\* | N/A |
| File-level restore | Full | Full | Full | Full | N/A | Full\* | N/A |
| Veeam Backup & Replication | Full | Full | Full | Full | Read | N/A | N/A |
| Jobs assigned by service provider | Full | Full | N/A | Full | Read | N/A | N/A |
| Veeam Backup for Public Clouds | Full | Full | N/A | Full | N/A | N/A | N/A |
| Failover plans | Full | Full | Full | Full | Read | N/A | N/A |
| Veeam Backup for Microsoft 365 | Full | Full | Full | Full | Read | N/A | N/A |
| Veeam ONE | Read | Read | Read | Read | Read | N/A | N/A |
| Invoices | Read | Read | N/A | N/A | N/A | N/A | Read |
| Backup reports | Full | Full | N/A | Full | Read | N/A | N/A |
| Monitoring | Read | Read | Read (only Resources) | Read (except for Overview) | Read (except for Overview) | Read\* (only Resources) | N/A |
| Active alarms | Full | Full | Full | Full | Read | Read\* | N/A |
| Protected data | Read | Read | Read | Read | Read | Read\* | N/A |

\* Limited to computers protected with Veeam backup agents, with backups stored on a cloud repository under the account of a Subtenant.


