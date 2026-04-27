---
title: "Managing Invoices"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/manage_invoices.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Managing Invoices


To calculate the cost of services you provide to companies, use invoices. Invoices are documents that contain information about provided services, charge rates for these services according to a subscription plan assigned to a company, the cost of each service, applied taxes and discounts and the total cost of consumed services.

In Veeam Service Provider Console, you can generate invoices and send them by email to companies. Invoices are sent as PDF files attached to billing notifications. To automate invoicing, you can configure a schedule according to which invoices will be generated.

To access invoices, you must have at least one managed client company with a subscription plan assigned.

Types of Invoices

Veeam Service Provider Console supports three types of invoices:

* Summary invoice provides information about consumed services and their cost.
* Detailed invoice provides information about consumed services and their cost. In addition, a detailed invoice provides information about services consumed by each company location on each day of a specified period.
* Quota usage report provides information about services consumed by each company location on each day of a specified period. A quota usage report does not include cost details.

You can choose what type of invoices you will generate for each managed company. For details on choosing an invoice type, and examples of available invoice types, see [Choosing Invoice Type](choose_invoice_type.md).

Invoice Status

An invoice can have one of the following statuses:

* Unpaid — an invoice has not been paid, and the payment due date is not passed. This status is automatically applied to new invoices.
* Paid — an invoice has been marked as paid.
* Overdue — an invoice has not been paid, and the payment due date is passed.
* Information — applied to quota usage reports.

You can mark invoices as paid and unpaid to track payments that clients already made, and payments due. For details, see [Marking Invoices as Paid and Unpaid](change_invoice_status.md).

Getting Started with Invoices

To get started with invoices, keep to the following sequence of steps:

1. [Customize invoice appearance and configure billing notifications](configure_notifications_invoices.md).

Customize the appearance of invoices and billing notifications.

1. [Choose invoice type](choose_invoice_type.md).

Choose what type of invoices must be generated for each managed company.

1. [Schedule invoices](schedule_invoices.md).

Create a schedule according to which invoices must be generated.

If you do not schedule invoices, you will need to generate them manually. For details, see [Creating Invoices Manually](run_invoices.md).

1. [Mark invoices as Paid](change_invoice_status.md).

When a client pays an invoice, mark it as Paid.


