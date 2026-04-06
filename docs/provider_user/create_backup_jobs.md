---
title: "Creating Backup Jobs"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/create_backup_jobs.html"
last_updated: "9/5/2023"
product_version: "9.1.0.30636"
---

# Creating Backup Jobs


In Veeam Service Provider Console, you can configure Veeam Backup & Replication job settings on servers assigned to you by your service provider.

You can configure the following job types:

* [vSphere Backup Jobs](create_vsphere_job.md)

A vSphere backup job defines a list of VMs to back up, a repository where to store backups, guest OS processing settings and a schedule according to which new backups must be created.

* [Cloud Director Backup Jobs](create_vcd_job.md)

A Cloud Director backup job defines a list of VMware Cloud Director organizations, datacenters, vApps and VMs to back up, a repository where to store backups, guest OS processing settings and a schedule according to which new backups must be created.

|  |
| --- |
| Note: |
| This functionality is available for Veeam Backup & Replication version 12.1 or later.  Make sure your service provider has enabled Veeam Backup & Replication REST API access. |


