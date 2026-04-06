---
title: "Services"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/services.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Services


There are several types of services for which you can charge companies in Veeam Service Provider Console. The following tables provide a description of these services and information about pricing units used to measure each service.

General

You can charge companies for providing managed backup services and monitoring services.

General

| Service | Pricing Unit | Description |
| Managed services | Monthly fee | Flat fee for backup management services you provide to companies. |
| Monitoring services | Monthly fee | Flat fee for monitoring services you provide to companies. |

Veeam Backup & Replication Management

If you manage a Veeam Backup & Replication infrastructure for a company, you can charge the company for the number of managed VMs, size of managed file shares and object storage and amount of space consumed by backups and archive backups.

Veeam Backup & Replication Management

| Service | Pricing Unit | Description |
| Managed VMs | Per VM | Charged by the number of managed VMs.  A managed VM is a VM that has a backup or replica restore point. |
| Managed VMs with CDP enabled | Per VM | Charged by the number of managed VMs included in CDP policies. |
| Unstructured data | Per GB or TB | Charged by:   * size of source file share or object storage * amount of consumed space on backup repository * amount of consumed space on archive repository |
| Backup repository space | Per GB or TB | Can be charged by:   * amount of allocated space on backup repositories * amount of consumed space on backup repositories |

Veeam Backup Agents Management

If you manage Veeam backup agents for a company, you can charge the company for the number of managed workstation or server agents and for guest OSes running on managed computers.

Veeam Backup Agents Management

| Service | Pricing Unit | Description |
| Managed Workstation Agents | Per workstation | Charged by the number of workstation agents managed by Veeam Service Provider Console or Veeam Backup & Replication servers.  A managed workstation is a physical computer or VM that runs a Veeam backup agent in the Workstation operation mode. |
| Managed Server Agents | Per server | Charged by the number of server agents managed by Veeam Service Provider Console or Veeam Backup & Replication servers.  A managed server is a physical computer or VM that runs a Veeam backup agent in the Server operation mode. |
| Guest OS (Windows workstation) | Per agent | Charged by the number of managed computers running a Windows workstation guest OS.  A managed computer is a physical computer or VM that runs a Veeam backup agent managed by Veeam Service Provider Console or Veeam Backup & Replication server. |
| Guest OS (Windows server) | Per agent | Charged by the number of managed computers running a Windows server guest OS.  A managed computer is a physical computer or VM that runs a Veeam backup agent managed by Veeam Service Provider Console or Veeam Backup & Replication server. |
| Guest OS (Linux) | Per agent | Charged by the number of managed computers running a Linux guest OS.  A managed computer is a physical computer or VM that runs a Veeam backup agent managed by Veeam Service Provider Console or Veeam Backup & Replication server. |
| Guest OS (macOS) | Per agent | Charged by the number of managed computers running a Mac guest OS.  A managed computer is a physical computer or VM that runs a Veeam backup agent managed by Veeam Service Provider Console or Veeam Backup & Replication server. |

Veeam Cloud Connect Resources

If you provide Veeam Cloud Connect resources to companies, you can charge the companies for cloud host or cloud repository resources.

Veeam Cloud Connect Resources

| Service | Pricing Unit | Description |
| VM backups in a cloud repository | Per VM backup | Charged by the number of VM backups stored on cloud repositories. |
| Workstation backups in a cloud repository | Per workstation backup | Charged by the number of workstation backups stored on cloud repositories.  A cloud workstation backup is a backup created by a backup job configured to run in the Workstation operation mode and targeted at a cloud repository. |
| Server backups in a cloud repository | Per server backup | Charged by the number of server backups stored on cloud repositories.  A cloud server backup is a backup created by a backup job configured to run in the Server operation mode and targeted at a cloud repository. |
| Cloud repository space | Per GB or TB | Can be charged by:   * amount of consumed space on cloud repositories * amount of allocated space on cloud repositories * amount of space consumed on different tiers of scale-out backup repositories * amount of space consumed by deleted cloud backups stored in the recycle bin |
| Data transfer out traffic | Per GB or TB | Charged by the amount of data downloaded from a cloud repository. |
| Replicated VM | Per VM replica | Charged by the number of VM replicas registered on cloud hosts. |
| Cloud storage | Per GB or TB | Charged by the amount of space consumed by VM replicas on cloud storage. |
| Compute resources | Per time interval | Charged by the amount of time VM replicas consumed CPU and memory resources on cloud hosts.  VM replicas consume resources only during a failover. |

Veeam Backup for Microsoft 365 Resources

If you provide Veeam Backup for Microsoft 365 resources to companies, you can charge the companies for the number of protected users and amount of space consumed on standard and archive storage.

Veeam Backup for Microsoft 365 Resources

| Service | Pricing Unit | Description |
| Subscription Users | Per user | Charged by the number of protected Microsoft 365 subscription users. |
| Educational Users | Per user | Charged by the number of protected Microsoft 365 users with Education licenses. |
| Microsoft 365 repository space | Per GB or TB | Can be charged by:   * amount of allocated space on Microsoft 365 repositories  * amount of consumed space on local Jet-based repositories and in cloud object storage repositories * amount of consumed space on archive cloud object storage repositories |

Veeam Backup for Public Clouds Resources

If you provide Veeam Backup for Public Clouds resources to companies, you can charge the companies for public cloud host or public cloud repository resources.

Veeam Backup for Public Clouds Resources

| Service | Pricing Unit | Description |
| Cloud VM | Per VM per month | Charged by the number of managed cloud VMs.  A managed cloud VM is a Microsoft Azure VM, AWS EC2 or Google Cloud VM instance protected by Veeam Backup & Replication. |
| Cloud File Shares | Per instance per month | Charged by the number of managed cloud file shares. |
| Cloud Databases | Per instance per month | Charged by the number of managed cloud databases. |
| Cloud Storage | Per GB or TB | Charged by:   * amount of consumed space on backup repository * amount of consumed space on archive repository |
| Cloud Networks | Monthly fee | Flat fee for services you provide to companies that have at least one cloud network configuration protected by Veeam Backup & Replication. |

Rental Licenses

If you use a Rental license for Veeam Service Provider Console, you can charge the company for consumed license instances.

For details on objects that consume rental licenses, see [Licensed Objects](licensed_objects.md).


