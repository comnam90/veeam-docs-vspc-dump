---
title: "Managing VMware vSphere Tags"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbr_vsphere_tags.html"
last_updated: "9/15/2025"
product_version: "9.1.0.30636"
---

# Managing VMware vSphere Tags


To create vSphere backup jobs on hosted Veeam Backup & Replication servers for client companies, you must assign a VMware vSphere tag to the client company.

A VMware vSphere tag is a label that applies to objects in your VMware vSphere inventory. You can use VMware vSphere tags to create jobs on hosted Veeam Backup & Replication servers and to allow client company users to create jobs on Veeam Backup & Replication servers hosted in your infrastructure. The assigned tag will define the backup scope available for company backup jobs. Note that a company can have only one assigned tag. If you want to assign another tag to a company, you must first remove the previously assigned tag.

For example, a client company has virtual machines in VMware vSphere infrastructure connected to your hosted Veeam Backup & Replication server and wants to back up these VMs to your hosted Veeam Backup & Replication repository. You can assign these VMs a specific tag, allocate repository resources to the company and assign the created VMware vSphere tag. After you have assigned a VMware vSphere tag, the company will be able to create backup jobs targeted to an allocated repository for all VMs with the assigned tag.

For details on VMware vSphere tags, see [VMware Docs](https://docs.vmware.com/en/VMware-vSphere/8.0/vsphere-vcenter-esxi-management/GUID-16422FF7-235B-4A44-92E2-532F6AED0923.html).

Before You Begin

Before you can assign a VMware vSphere tag to a company, make sure that:

* You have created a VMware vSphere tag that you plan to assign to the company. For details, see [VMware Docs](https://docs.vmware.com/en/VMware-vSphere/8.0/vsphere-vcenter-esxi-management/GUID-16422FF7-235B-4A44-92E2-532F6AED0923.html#GUID-2FF21224-B6BC-499B-AD8B-D2C4309AD9DC__GUID-17C6297F-664C-4B5A-968F-42BBB2282081).
* You have assigned the VMware vSphere tag to company VMs. For details, see [VMware Docs](https://docs.vmware.com/en/VMware-vSphere/8.0/vsphere-vcenter-esxi-management/GUID-16422FF7-235B-4A44-92E2-532F6AED0923.html#GUID-379F40D3-8CD6-449E-89CB-79C4E2683221__GUID-D70D5ABF-7FE7-49D2-B7E3-789447C8EDA9).
* You have allocated a hosted Veeam Backup & Replication server to the company. For details, see [Step 4. Configure Hosted Services](allocate_hosted_quota.md).

In This Section

* [Assigning Custom Tags to Veeam Backup & Replication Servers](vbr_assign_vsphere_tag.md)

* [Removing Tags from companies](vbr_remove_vsphere_tag.md)
* [Viewing and Exporting VMware vSphere Tag Details](vbr_view_vsphere_tag.md)


