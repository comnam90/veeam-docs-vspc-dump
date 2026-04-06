---
title: "Alarms"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/appendix_alarms.html"
last_updated: "10/17/2025"
product_version: "9.1.0.30636"
---

# Alarms


Veeam Service Provider Console includes a set of predefined alarms described in the following table.

Alarms

| Alarm Name | Alarm Description | Object | Enabled |
| Backup agent connection state | This alarm checks whether a Veeam backup agent is running or can be contacted. | Backup agent | Yes |
| Backup agent job state | This alarm checks whether a Veeam backup agent job session failed or finished with a warning. | Backup agent job | Yes |
| Backup agent job state (managed by backup server) | This alarm checks whether a Veeam backup agent job session configured on a Veeam Backup & Replication server failed or finished with a warning. | Backup agent job | Yes |
| Backup agent version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam backup agent version and the Veeam backup agent requires upgrade. | Backup agent | Yes |
| Backup appliance connection state | This alarm checks whether a Veeam Backup for Public Clouds appliance is running or can be contacted. | Backup appliance | Yes |
| Backup appliance version is out-of-date | This alarm checks whether the version of a Veeam Backup for Public Clouds appliance matches the version of Veeam Backup & Replication installed on a backup server. | Backup appliance | Yes |
| Backup Enterprise Manager connection state | This alarm checks whether the Veeam Backup Enterprise Manager service is running. | Enterprise Manager | Yes |
| Backup High Availability cluster state | This alarm checks whether a High Availability cluster is offline or destroyed and whether a switchover or a failover was initiated. | Backup server | Yes |
| Backup portal infrastructure performance | This alarm checks whether the growth of the staging database affects Veeam Service Provider Console performance. | Internal | Yes |
| Backup proxy connection state | This alarm checks the connection status between a Veeam backup server and backup proxy. | Backup proxy | Yes |
| Backup proxy version is out-of-date | This alarm checks whether the version of a backup proxy matches the version of Veeam Backup & Replication installed on a backup server. | Backup proxy | Yes |
| Backup repository connection state | This alarm checks the connection status between a Veeam backup server and backup repository. | Backup repository | Yes |
| Backup repository version is out-of-date | This alarm checks whether the version of a backup repository matches the version of Veeam Backup & Replication installed on a backup server. | Backup repository | Yes |
| Backup server connection state | This alarm checks whether the Veeam Backup Service is running on a backup server. | Backup server | Yes |
| Backup server license exceeded | This alarm checks whether the Veeam Backup & Replication product license was exceeded. | Backup server | Yes |
| Backup server license expiration | This alarm checks whether the Veeam Backup & Replication product license has expired. | Backup server | Yes |
| Backup server support contract expiration | This alarm checks whether the Veeam Backup & Replication support contract has expired. | Backup server | Yes |
| CDP policy compliance | This alarm checks whether SLA for workloads protected with CDP policies has dropped below the configured threshold. | Job | No |
| Cloud backup health check session state | This alarm checks whether a health check session of a Veeam Backup for Public Clouds policy failed or finished with a warning. | Job | Yes |
| Cloud Connect connection state | This alarm checks whether Veeam Service Provider Console has connection to the Veeam Cloud Connect server. | Site | Yes |
| Cloud database without backup | This alarm checks whether cloud databases have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud database without replica snapshot | This alarm checks whether replica snapshots for cloud databases have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud database without snapshot | This alarm checks whether snapshots for cloud databases have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud file share without replica snapshot | This alarm checks whether replica snapshots for cloud file shares have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud file share without snapshot | This alarm checks whether replica snapshots for cloud file shares have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud gateway connection state | This alarm checks the connection status between a Veeam Cloud Connect server and cloud gateway. | Cloud gateway | Yes |
| Cloud gateway version is out-of-date | This alarm checks whether the version of a cloud gateway matches the version of Veeam Backup & Replication installed on the Veeam Cloud Connect server. | Cloud gateway | Yes |
| Cloud host memory quota | This alarm tracks whether the total amount of configured memory for cloud replicas has breached the configured threshold. | Site | Yes |
| Cloud host storage quota | This alarm tracks whether storage quota assigned to a company as a part of the hardware plan has been exceeded. | Site | Yes |
| Cloud host vCPU ratio | This alarm checks whether the number of replicated VMs vCPUs has breached the configured threshold. | Site | Yes |
| Cloud policy archive session state | This alarm checks whether a public cloud archive policy session failed or finished with a warning. | Job | Yes |
| Cloud policy backup session state | This alarm checks whether a public cloud backup policy session failed or finished with a warning. | Job | Yes |
| Cloud policy replica snapshot session state | This alarm checks whether a public cloud replica snapshot session failed or finished with a warning. | Job | Yes |
| Cloud policy snapshot session state | This alarm checks whether a public cloud snapshot session failed or finished with a warning. | Job | Yes |
| Cloud VM without backup | This alarm checks whether cloud VMs have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud VM without replica snapshot | This alarm checks whether replica snapshots for cloud VMs have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud VM without snapshot | This alarm checks whether snapshots for cloud VMs have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Company cloud storage quota | This alarm checks whether a company is running out of space on a cloud repository. | Company | Yes |
| Company data download quota | This alarm checks whether a company is running out of the data transfer out quota on cloud repositories. | Company | No |
| Company lease expiration date | This alarm checks whether a cloud repository lease time is about to expire. | Company | Yes |
| Company server agents quota | This alarm checks whether a company has exceeded the maximum allowed number of managed Veeam backup agents running in Server mode. | Company | Yes |
| Company workstation agents quota | This alarm checks whether a company has exceeded the maximum allowed number of managed Veeam backup agents running in Workstation mode. | Company | Yes |
| Computer without backup | This alarm checks whether computers running Veeam Backup Agents have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup agent | Yes |
| Computer without backup (managed by backup server) | This alarm checks whether computers running Veeam Backup Agents and managed by Veeam Backup & Replication have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| ConnectWise Manage plugin state | This alarm checks whether ConnectWise Manage plugin is having connectivity or configuration issues or product mapping configuration has changed. | Plugin | Yes |
| Database configuration issue | This alarm checks whether the Veeam Service Provider Console database collation matches the collation of Microsoft SQL Server. | Internal | Yes |
| Deleted backups recycle bin quota | This alarm tracks whether the size of backups moved to the recycle bin has breached the configured threshold. | Company | No |
| Discovery rule state | This alarm checks whether a discovery rule failed. | Discovery rule | Yes |
| Duplicate Installation ID detected | This alarm checks whether Veeam Backup & Replication or Veeam ONE servers with the same installation IDs are present in the infrastructure. | Internal | Yes |
| Failover Plan session state | This alarm checks whether one or more VMs in a failover plan failed to start. | VM failover plan | Yes |
| File-level recovery session state | This alarm checks whether a file-level recovery session failed or finished with a warning. | Backup agent | Yes |
| Hosted backup repository storage quota | This alarm checks whether the size of company backups exceeds the storage quota configured for a hosted backup repository. | Company | Yes |
| Immediate backup copy job state | This alarm checks whether an immediate backup copy job session failed or finished with a warning. | Job | Yes |
| Invoice payment status | This alarm checks whether an invoice was not marked as paid in 30 days after generation. | Company | No |
| Job session state | This alarm checks whether a job session failed or finished with a warning. | Job | Yes |
| Job state | This alarm checks whether a job was in a disabled state or unscheduled for more than an allowed time period. | Job | Yes |
| License auto-update state | This alarm checks whether License auto-update feature is enabled. | Internal | Yes |
| Management agent connection state | This alarm checks the connection status between Veeam Service Provider Console and a management agent running on a Veeam Backup & Replication server, Veeam Backup Enterprise Manager server or a computer protected with Veeam backup agent. | Management agent | No |
| Management agent version is out-of-date | This alarm checks whether the version of a management agent running on a Veeam Backup & Replication server, Veeam Backup Enterprise Manager server or a computer protected with Veeam backup agent matches the version of Veeam Service Provider Console. | Management agent | No |
| Max allowed backup agent job duration | This alarm checks whether a Veeam backup agent job session has exceeded the maximum allowed session duration. | Backup agent job | No |
| Max allowed job duration | This alarm checks whether a Veeam Backup & Replication job session has exceeded the maximum allowed session duration. | Job | No |
| Microsoft 365 backup proxy connection state | This alarm checks the connection status between a Veeam Backup for Microsoft 365 server and backup proxy. | Veeam Backup for Microsoft 365 proxy | Yes |
| Microsoft 365 backup repository free space | This alarm checks whether a Veeam Backup for Microsoft 365 backup repository is running out of space. | Veeam Backup for Microsoft 365 repository | Yes |
| Microsoft 365 backup repository storage quota | This alarm checks whether the size of company backups exceeds the storage quota configured for the Veeam Backup for Microsoft 365 repository. | Company | Yes |
| Microsoft 365 job session state | This alarm checks whether a Veeam Backup for Microsoft 365 job session failed or finished with a warning. | Veeam Backup for Microsoft 365 server job | Yes |
| Microsoft 365 license expiration | This alarm checks whether the Veeam Backup for Microsoft 365 product license has expired. | Veeam Backup for Microsoft 365 server | Yes |
| Microsoft 365 max allowed job duration | This alarm checks whether a Veeam Backup for Microsoft 365 job session has exceeded the maximum allowed session duration. | Veeam Backup for Microsoft 365 server job | No |
| Microsoft 365 server connection state | This alarm checks the connection status between Veeam Service Provider Console and Veeam Backup for Microsoft 365 server. The alarm also checks the Veeam Backup for Microsoft 365 server application status. | Veeam Backup for Microsoft 365 server | Yes |
| Microsoft 365 server license exceeded | This alarm checks whether the Veeam Backup for Microsoft 365 product license was exceeded. | Veeam Backup for Microsoft 365 server | Yes |
| Microsoft 365 server version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam Backup for Microsoft 365 server version and the server requires upgrade. | Veeam Backup for Microsoft 365 server | Yes |
| Potential malware activity | This alarm checks whether Veeam Backup & Replication detects potential malware activity in a restore point. | Backup server | Yes |
| Protected users quota | This alarm checks whether a company has exceeded the max allowed number of users stored in the Veeam Backup for Microsoft 365 repository. | Company | Yes |
| Remote backup repository storage quota | This alarm checks whether the size of company backups exceeds the storage quota configured for a remote backup repository. | Company | Yes |
| Repository free space | This alarm checks whether a backup repository is running out of space. | Backup repository | Yes |
| Reseller cloud storage quota | This alarm checks whether reseller clients are running out of space allocated on a cloud repository. | Reseller | Yes |
| Reseller data download quota | This alarm checks whether reseller clients are running out of the data transfer out quota on cloud repositories. | Reseller | Yes |
| Reseller hardware plans quota | This alarm checks whether a reseller has exceeded the max allowed number of companies assigned to a hardware plan. | Reseller | Yes |
| Reseller managed tenants quota | This alarm checks whether a reseller has exceeded the max allowed number of managed tenants. | Reseller | Yes |
| Reseller points quota | This alarm checks whether a reseller is running out of allocated points quota. | Reseller | Yes |
| Reseller server agents quota | This alarm checks whether reseller clients have exceeded the max allowed number of managed Veeam backup agents running in Server mode. | Reseller | Yes |
| Reseller server cloud backups quota | This alarm checks whether reseller clients have exceeded the max allowed number of Server Veeam backup agents stored in the cloud. | Cloud storage | Yes |
| Reseller VM cloud backups quota | This alarm checks whether reseller clients have exceeded the max allowed number of VM backups stored in the cloud. | Cloud storage | Yes |
| Reseller workstation agents quota | This alarm checks whether reseller clients have exceeded the max allowed number of managed Veeam backup agents running in Workstation mode. | Reseller | Yes |
| Reseller workstation cloud backups quota | This alarm checks whether reseller clients have exceeded the max allowed number of Workstation Veeam backup agents stored in the cloud. | Cloud storage | Yes |
| Scale-out backup repository offload session state | This alarm checks whether a scale-out backup repository offload, download, archiving, or retrieval data transfer session failed or finished with a warning. | Job | Yes |
| Server agent backups stored in cloud repository | This alarm checks whether a company has exceeded the maximum allowed number of server agent backups stored in the cloud. | Cloud repository | Yes |
| Shared license key usage | This alarm checks whether the license key with the same ID has been installed on multiple servers. | Internal | Yes |
| SQL Server Express database size | This alarm checks whether the database size is close to the maximum database size supported by the SQL Server Express edition. | Internal | Yes |
| SureBackup job session state | This alarm checks whether a SureBackup job session failed or finished with a warning. | VM job (SureBackup) | Yes |
| Suspicious user login activity | This alarm tracks multiple failed login attempts to the Veeam Service Provider Console portal for the user from the same IP address. | Internal | Yes |
| VCSP Pulse connection state | This alarm checks the connection status between VCSP Pulse and Veeam Service Provider Console. | Company | Yes |
| Veeam Backup & Replication version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam Backup & Replication or Veeam Cloud Connect server version and the server requires upgrade. | Backup server | Yes |
| Veeam ONE license expiration | This alarm checks whether the Veeam ONE product license has expired. | Veeam ONE server | Yes |
| Veeam ONE server connection state | This alarm checks the connection status between Veeam Service Provider Console and Veeam ONE server. | Veeam ONE server | Yes |
| Veeam ONE server license exceeded | This alarm checks whether the Veeam ONE product license was exceeded. | Veeam ONE server | Yes |
| Veeam ONE support contract expiration | This alarm checks whether Veeam ONE prepaid support contract has expired. | Veeam ONE server | Yes |
| Veeam ONE version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam ONE server version and the server requires upgrade. | Veeam ONE server | Yes |
| Veeam Service Provider Console license expiration | This alarm checks whether the Veeam Service Provider Console product license has expired. | Internal | Yes |
| Veeam Service Provider Console license update state | This alarm checks whether Veeam Service Provider Console failed to obtain a new license key from the Veeam License Update Server. | Internal | Yes |
| Veeam Service Provider Console licenses exceeded | This alarm checks whether the number of managed Veeam backup agents exceeded the number of available licenses. | Internal | Yes |
| VM without backup | This alarm checks whether VMs managed with Veeam Backup & Replication have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| VM without replica | This alarm checks whether VMs managed with Veeam Backup & Replication have been replicated within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| VMs in the backup repository | This alarm checks whether the number of VMs stored in a backup repository exceeds the maximum allowed limit. | Backup repository | No |
| VMs stored in cloud repository | This alarm checks whether the number of VMs that a company stores in a cloud repository exceeds the maximum allowed limit. | Cloud repository | Yes |
| WAN accelerator connection state | This alarm checks the connection status between a Veeam backup server and WAN accelerator. | WAN accelerator | Yes |
| WAN accelerator version is out-of-date | This alarm checks whether the version of a WAN accelerator matches the version of Veeam Backup & Replication installed on a backup server. | WAN accelerator | Yes |
| Workstation agent backups stored in cloud repository | This alarm checks whether a company has exceeded the maximum allowed number of workstation agent backups stored in the cloud. | Cloud repository | Yes |


