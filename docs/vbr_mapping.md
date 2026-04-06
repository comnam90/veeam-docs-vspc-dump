---
title: "Managing VMware Cloud Director Mapping"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/vbr_mapping.html"
last_updated: "9/15/2025"
product_version: "9.1.0.30636"
---

# Managing VMware Cloud Director Mapping


To create Cloud Director backup jobs on hosted Veeam Backup & Replication servers for client companies, you must map a VMware Cloud Director organization to the client company.

If you created a Veeam Service Provider Console company based on a VMware Cloud Director organization and allocated to this company the Veeam Backup & Replication server where VMware Cloud Director organization is registered, Veeam Service Provider Console will automatically map this company to the VMware Cloud Director organization. To remove this mapping, you will need to remove hosted Veeam Backup & Replication server allocation from the company.

For details on VMware Cloud Director organizations, see [VMware Docs](https://docs.vmware.com/en/VMware-Cloud-Director/10.5/VMware-Cloud-Director-Service-Provider-Admin-Guide/GUID-2F217F99-48C1-42F3-BF06-5ABBACADE2BA.html).

Before You Begin

Before you can map a VMware Cloud Director organization to a company, make sure that you have allocated hosted Veeam Backup & Replication resources to the company. For details, see [Step 4. Configure Hosted Services](allocate_hosted_quota.md).

In This Section

* [Mapping VMware Cloud Director Organizations](vbr_map_vcd.md)
* [Removing Mapping](vbr_remove_vcd_mapping.md)
* [Viewing and Exporting VMware Cloud Director Organization Details](vbr_view_vcd.md)


