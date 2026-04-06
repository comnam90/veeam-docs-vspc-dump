---
title: "Creating Backup Jobs"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_backup_jobs.html"
last_updated: "10/22/2025"
product_version: "9.1.0.30636"
---

# Creating Backup Jobs


In Veeam Service Provider Console, you can configure Veeam Backup & Replication job settings on hosted servers.

You can configure the following job types:

* [vSphere Backup Jobs](create_vsphere_job.md)

A vSphere backup job defines a list of VMs to back up, a repository where to store backups, guest OS processing settings and a schedule according to which new backups must be created.

* [Hyper-V Backup Jobs](create_hyperv_job.md)

A Hyper-V backup job defines a list of VMs to back up, a repository where to store backups, guest OS processing settings and a schedule according to which new backups must be created.

* [Cloud Director Backup Jobs](create_vcd_job.md)

A Cloud Director backup job defines a list of VMware Cloud Director organizations, datacenters, vApps and VMs to back up, a repository where to store backups, guest OS processing settings and a schedule according to which new backups must be created.

* [Backup Copy Jobs](create_copy_job.md)

A backup copy job creates additional instances of restore points created by backup jobs.

|  |
| --- |
| Note: |
| Creating vSphere and Cloud Director backup jobs is available for Veeam Backup & Replication version 12.1 or later.  Creating Hyper-V backup jobs and backup copy jobs is available for Veeam Backup & Replication version 13.0.1 or later.  Make sure you have enabled Veeam Backup & Replication REST API access. |


