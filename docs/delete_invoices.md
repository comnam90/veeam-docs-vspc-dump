---
title: "Deleting Invoices"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/delete_invoices.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Deleting Invoices


You can delete invoices that you no longer need.

|  |
| --- |
| Important! |
| To avoid mischarging a company for data transfer out traffic and compute resources, do not delete an invoice that is followed by another invoice.  The cost of data transfer out traffic and compute resources is calculated starting from the date when the previous invoice was generated. For example, you generate Invoice 1 for January and Invoice 2 for February. If you delete Invoice 1, and then generate Invoice 3 for March, data transfer out traffic and compute resources for January will not be included in Invoice 3, as Invoice 3 takes into account traffic starting from the date when Invoice 2 was generated (since February). As a result, the cost of data transfer out traffic and compute resources for January will be leaved out of account.  To learn how consumed services are measured when an invoice is generated, see [Measuring Amount of Consumed Services](measure_services.md). |

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Deleting Invoices

To delete one or more invoices:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Invoices.
2. On the All Invoices tab, select the necessary invoices in the list.
3. Click Remove.

Alternatively, you can right-click the necessary invoice and choose Remove.

1. In the displayed window, click Yes to confirm the operation.


