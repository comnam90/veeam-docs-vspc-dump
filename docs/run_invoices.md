---
title: "Creating Invoices Manually"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/run_invoices.html"
last_updated: "12/13/2023"
product_version: "9.1.0.30636"
---

# Creating Invoices Manually


You can create invoices manually. This functionality can be useful if you did not schedule automatic generation of invoices. You may also need to create invoices manually to view how they will look like, and possibly customize their appearance.

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Creating Invoices Manually

To manually create an invoice for one or more companies:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Invoices.
2. Open the Configurations tab.
3. Select the necessary companies in the list.
4. At the top of the list, select what type of invoices must be generated for selected companies:

* Generate Invoice — choose this option to generate summary or detailed invoices.
* Generate Quota Usage Report — choose this option to generate quota usage reports.

In the Quota Usage Report window, specify a period for which information about services consumed by each company must be included in the report and click Run.

Alternatively, you can right-click the necessary company in the list and choose what type of invoice must be generated.

Veeam Service Provider Console will save a manually created invoice in the invoice list. If you have configured billing notification, Veeam Service Provider Console will automatically send created invoice to a company. To learn how to view details of a created invoice, see [Viewing and Downloading Invoice Details](export_invoice_details.md).


