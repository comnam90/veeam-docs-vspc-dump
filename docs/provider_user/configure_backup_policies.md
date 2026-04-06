---
title: "Configuring Backup Policies"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/configure_backup_policies.html"
last_updated: "12/18/2023"
product_version: "9.1.0.30636"
---

# Configuring Backup Policies


To configure Veeam backup agent job settings on a managed computer, you can assign a backup policy to it. A backup policy describes configuration of a Veeam backup agent job and can be used as a saved template. Backup policies speed up the process of configuring backup job settings on managed computers: instead of specifying backup job settings manually, you can apply settings from a preconfigured backup policy to a group of computers. For details, see [Assigning Backup Policies](assign_backup_policies.md).

By default, Veeam Service Provider Console includes the following predefined backup policies:

* Linux server - Entire computer
* Linux workstation - Home directory
* Mac server - Entire computer
* Mac workstation - Users directory
* Windows server - Entire computer
* Windows workstation - Personal files

In addition to predefined backup policies, you can create multiple custom backup policies with different configuration settings and assign them to different groups of computers. For example, you can configure backup policies for different machine types, applications, locations, and so on.

Backup policies can be configured in the Veeam Service Provider Console Administrator Portal and Client Portal. Predefined backup policies and public policies configured by the Portal Administrator are available to all companies in the Client Portal. Backup policies configured by Company Owner and Company Administrators and private policies configured by the Portal Administrator for a company are available to this company only, but can be managed in the Administrator Portal.

In This Section

* [Creating Windows Backup Policies](create_backup_policies.md)
* [Creating Linux Backup Policies](create_backup_policies_linux.md)
* [Creating Mac Backup Policies](create_backup_policies_mac.md)

* [Creating Backup Policies from Backup Job Configurations](create_policies_from_jobs.md)

* [Assigning Backup Policies](assign_backup_policies.md)
* [Modifying Backup Policies](modify_backup_policies.md)
* [Updating Backup Job Configuration](get_latest_configuration.md)
* [Copying Backup Policies](copy_policies.md)
* [Removing Backup Policies](remove_backup_policies.md)


