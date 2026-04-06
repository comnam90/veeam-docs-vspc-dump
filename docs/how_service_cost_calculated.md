---
title: "How Cost of Services is Calculated"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/how_service_cost_calculated.html"
last_updated: "11/21/2023"
product_version: "9.1.0.30636"
---

# How Cost of Services is Calculated


Veeam Service Provider Console uses the following formula to calculate the cost of consumed services:

|  |
| --- |
| ((Service 1 \* Rate 1 + Service 2 \* Rate 2 + Service N \* Rate N) - Discount) + Tax |

Where:

* Service N stands for a measured amount of consumed services, such as the number of managed VMs, workstations and servers, number of VMs, workstations or servers stored in backups on cloud repositories, amount of consumed cloud repository space, data transfer out traffic and so on.
* Rate N stands for a charge rate for a consumed service, as specified in a subscription plan.
* Discount stands for a discount amount. The discount is calculated for the total cost of consumed services.
* Tax stands for a tax amount. Tax is calculated for the total cost of consumed services minus Discount.

Example

For example, a subscription plan is configured as follows:

* Managed backup services: 100 per month
* Managed VM: 5 per VM
* Workstation backup agent: 3 per agent
* Server backup agent: 8 per agent
* Data transfer out traffic: 1 per GB
* Discount: 15%
* Tax: 10%
* Currency: USD

The amount of consumed services for a previous month is reported as follows:

* Managed VM: 20
* Workstation backup agents: 10
* Server backup agents: 15

* Data transfer out traffic: 50 GB

The payment amount is calculated as follows:

* Managed services: 100 \* 1 = 100 USD
* Managed VMs: 20 \* 5 = 100 USD
* Workstation backup agents: 10 \* 3 = 30 USD
* Server backup agents: 15 \* 8 = 120 USD
* Data transfer out traffic: 50 \* 1 = 50 USD

* Total cost of services: 100 + 100 + 30 + 120 + 50 = 400 USD
* Discount: 400 \* 15/100 = 60 USD
* Total amount with discount: 400 - 60 = 340 USD
* Tax: 340 \* 10/100 = 34 USD
* Total amount due: 340 + 34 = 374 USD


