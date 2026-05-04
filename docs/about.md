---
title: "About Veeam Service Provider Console"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/about.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# About Veeam Service Provider Console


Veeam Service Provider Console is a cloud-enabled platform for centralized management and monitoring of data protection operations and services. The solution is intended for physical, virtual and cloud-based environments protected with Veeam Agent for Microsoft Windows, Veeam Agent for Linux and Veeam Agent for Mac (further referred to as Veeam backup agents), Veeam Backup & Replication and Veeam Backup for Microsoft 365. Veeam Service Provider Console allows service providers to deliver Veeam-powered Backup-as-a-Service (BaaS) and Disaster Recovery-as-a-Service (DRaaS) services to their customers.

This section contains an overview of Veeam Service Provider Console capabilities and Veeam products integrated with it.

General Features

General functionality of Veeam Service Provider Console includes:

* Companies and resellers management. You can manage the scope of provided services and allocate cloud and hosted resources to managed companies and resellers.
* Backup reporting. You can create reports showing whether protected workloads meet established RPO and SLA requirements.
* Billing. You can monitor and calculate the cost of provided resources and automate billing operations for provided services.
* License management and usage reporting. You can manage licenses and collect license usage information for managed Veeam products in a single view. Veeam Service Provider Console also allows you to create and manage VCSP Pulse license keys and assign license keys internally or to client companies and resellers without accessing VCSP Pulse portal.
* REST API. You can perform most of the operations that are available with Web UI using Veeam Service Provider Console REST API. For details, see [REST API Reference](https://helpcenter.veeam.com/references/vac/9.2/rest/3.6.2/tag/SectionAbout).
* Creating Veeam Customer Technical Support cases. You can open support cases for all Veeam products without accessing Veeam Customer Technical Support portal. For managed products, Veeam Service Provider Console will automatically collect the necessary log files and attach them to the support case.

For more detailed description of Veeam Service Provider Console features available for managed Veeam products, see [Veeam Service Provider Console Management Capabilities](capability.md).

Veeam Backup Agents

Veeam backup agents management functionality includes:

* Automated installation, patching and upgrade. You can automate deployment and configuration of Veeam backup agents on machines in client and hosted infrastructures, patch and upgrade managed Veeam backup agents without accessing the remote machines.

* Backup policies and jobs management. You can configure and assign backup policies and individual Veeam backup agents jobs.
* File-level restore. You can recover files and folders from backups created by Veeam backup agent jobs without accessing the remote machines.
* Data protection monitoring. You can monitor the status of data protection for computers protected with Veeam backup agents.

Veeam Backup & Replication

Veeam Backup & Replication management functionality includes:

* Remote installation, patching and upgrade. You can deploy and configure Veeam Backup & Replication on Microsoft Windows machines in client and hosted infrastructures, patch and upgrade Veeam Backup & Replication without accessing the remote machines.
* Private fix uploading for Veeam Software Appliance. You can upload private fix files to Veeam Backup & Replication servers deployed on Veeam Software Appliance without accessing the remote machines.

* Jobs management. You can create backup jobs on hosted Veeam Backup & Replication servers and manage jobs and CDP policies configured to protect VMs, computers, file shares and object storage in client and hosted infrastructures.
* Failover plans. You can run local and cloud failover plans on managed Veeam Backup & Replication servers.
* Data protection monitoring. You can monitor the status of data protection and continuous data protection for VMs, computers, file shares and object storage protected with Veeam Backup & Replication.

Veeam Backup for Public Clouds

Veeam Backup for Public Clouds management functionality includes:

* Remote installation and update. You can connect existing appliances to Veeam Service Provider Console, deploy new appliances in hosted infrastructure, assign appliances to managed companies and update appliances without accessing the remote machines.

* Cloud policies management. You can manage policies configured to protect cloud VMs, file shares, database instances and network configurations. To create new cloud backup policies, you can access Veeam Backup for Public Clouds portal from Veeam Service Provider Console.

* Data restore. You can access Veeam Backup for Public Clouds portal to recover data from backups created by Veeam Backup for Public Clouds policies.

* Cloud data protection monitoring. You can monitor the status of data protection for cloud VMs, file shares, databases and network configurations protected with Veeam Backup for Public Clouds.

Veeam Backup for Microsoft 365

Veeam Backup for Microsoft 365 management functionality includes:

* Organizations management. You can create companies for existing Microsoft 365 organizations, register new organizations and map organizations to managed client companies.
* Jobs management. You can create and manage backup and backup copy jobs in client and hosted infrastructures.
* Restore portal. You can access Veeam Backup for Microsoft 365 Restore Portal to recover data from backups created by Veeam Backup for Microsoft 365 jobs.

* Data protection monitoring. You can monitor the status of data protection for Microsoft 365 workloads protected with Veeam Backup for Microsoft 365.

Veeam ONE

You can enable alarms integration to monitor and manage in Veeam Service Provider Console alarms triggered on client and hosted Veeam ONE servers.

This document describes how to configure and use Veeam Service Provider Console. The document scope is limited to functionality available in the Administrator Portal, and does not cover features available in the Reseller Portal or Client Portal. For details on Veeam Service Provider Console features available in the Client Portal, see [Guide for End Users](https://helpcenter.veeam.com/docs/vac/provider_user/about.html?ver=9.2). For details on Veeam Service Provider Console features available in the Reseller Portal, see [Guide for Resellers](https://helpcenter.veeam.com/docs/vac/reseller/about.html?ver=9.2).


