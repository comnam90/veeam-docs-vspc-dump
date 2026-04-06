---
title: "Restarting Management Agent Service"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/restart_management_agent.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# Restarting Management Agent Service


Veeam Service Provider Console is implemented as a Veeam Management Agent Service that runs on a managed computer. If something goes wrong with this service, you may try to restart it on a managed computer.

|  |
| --- |
| Note: |
| In Veeam Service Provider Console, you can restart the management agent service only for Windows Veeam Backup & Replication servers. For Linux Veeam Backup & Replication servers, use Veeam Host Management Console. For details, see section [Performing Maintenance Tasks](https://helpcenter.veeam.com/docs/vbr/userguide/hmc_perform_maintenance_tasks.html?ver=13) of the Veeam Backup & Replication User Guide. |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Restarting Management Agent Service

To restart the management agent service on one or more managed computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab .
3. Select the necessary computers in the list.
4. At the top of the list, click Management Agent and choose Restart Agent Service.

Alternatively, you can right-click the necessary computer, choose Management Agent and select Restart Agent Service.


