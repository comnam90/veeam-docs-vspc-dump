---
title: "Alarms"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/appendix_alarms.html"
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
| Backup proxy connection state | This alarm checks the connection status between a Veeam backup server and backup proxy. | Backup proxy | Yes |
| Backup proxy version is out-of-date | This alarm checks whether the version of a backup proxy matches the version of Veeam Backup & Replication installed on a backup server. | Backup proxy | Yes |
| Backup repository connection state | This alarm checks the connection status between a Veeam backup server and backup repository. | Backup repository | Yes |
| Backup repository version is out-of-date | This alarm checks whether the version of a backup repository matches the version of Veeam Backup & Replication installed on a backup server. | Backup repository | Yes |
| Backup server agents quota | This alarm checks whether a company has exceeded the maximum allowed number of managed Veeam backup agents running in Server mode. | Company | Yes |
| Backup server connection state | This alarm checks whether the Veeam Backup Service is running on a backup server. | Backup server | Yes |
| Backup server license exceeded | This alarm checks whether the Veeam Backup & Replication product license has been exceeded. | Backup server | Yes |
| Backup server license expiration | This alarm checks whether the Veeam Backup & Replication product license has expired. | Backup server | Yes |
| Backup server support contract expiration | This alarm checks whether the Veeam Backup & Replication support contract has expired. | Backup server | Yes |
| Backup workstation agents quota | This alarm checks whether a company has exceeded the maximum allowed number of managed Veeam backup agents running in Workstation mode. | Company | Yes |
| CDP policy compliance | This alarm checks whether SLA for workloads protected with CDP policies has dropped below the configured threshold. | Job | No |
| Cloud backup health check session state | This alarm checks whether a health check session of a Veeam Backup for Public Clouds policy failed or finished with a warning. | Job | Yes |
| Cloud database without backup | This alarm checks whether cloud databases have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud database without snapshot | This alarm checks whether snapshots for cloud databases have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud database without replica snapshot | This alarm checks whether replica snapshots for cloud databases have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud file share without backup | This alarm checks whether cloud file shares have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud file share without replica snapshot | This alarm checks whether replica snapshots for cloud file shares have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud policy archive session state | This alarm checks whether a public cloud archive policy session failed or finished with a warning. | Job | Yes |
| Cloud policy backup session state | This alarm checks whether a public cloud backup policy session failed or finished with a warning. | Job | Yes |
| Cloud policy replica snapshot session state | This alarm checks whether a public cloud replica snapshot session failed or finished with a warning. | Job | Yes |
| Cloud policy snapshot session state | This alarm checks whether a public cloud snapshot session failed or finished with a warning. | Job | Yes |
| Cloud VM without backup | This alarm checks whether cloud VMs have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud VM without replica snapshot | This alarm checks whether replica snapshots for cloud VMs have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Cloud VM without snapshot | This alarm checks whether snapshots for cloud VMs have been created within the defined RPO (Recovery Point Objective) interval. | Backup appliance | Yes |
| Company cloud host memory quota | This alarm tracks whether the total amount of configured memory for cloud replicas has breached the configured threshold. | Company | Yes |
| Company cloud host storage quota | This alarm tracks whether storage quota assigned to a company as a part of the hardware plan has been exceeded. | Company | Yes |
| Company cloud storage quota | This alarm checks whether a company is running out of space on a cloud repository. | Company | Yes |
| Company data download quota | This alarm checks whether a company is running out of the data transfer out quota on cloud repositories. | Company | No |
| Company location cloud storage quota | This alarm checks whether a location is running out of space on a cloud repository. | Location | No |
| Computer without backup | This alarm checks whether computers running Veeam Backup Agents have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup agent | Yes |
| Computer without backup (managed by backup server) | This alarm checks whether computers running Veeam Backup Agents managed with Veeam Backup & Replication have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| Discovery rule state | This alarm checks whether a discovery rule failed. | Discovery rule | Yes |
| Failover Plan session state | This alarm checks whether one or more VMs in a failover plan failed to start. | VM failover plan | Yes |
| File-level recovery session state | This alarm checks whether a file-level recovery session failed or finished with a warning. | Backup agent | Yes |
| Hosted backup repository storage quota | This alarm checks whether the size of company backups exceeds the storage quota configured for a hosted backup repository. | Company | Yes |
| Immediate backup copy job state | This alarm checks whether a backup copy job session failed or finished with a warning. | Job | Yes |
| Job session state | This alarm checks whether a job session failed or finished with a warning. | Job | Yes |
| Job state | This alarm checks whether a job was in a disabled state for more than an allowed time period. | Job | Yes |
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
| Protected users quota | This alarm checks whether your company has exceeded the max allowed number of users stored in a backup repository. | Company | Yes |
| Remote backup repository storage quota | This alarm checks whether the size of company backups exceeds the storage quota configured for the remote backup repository. | Company | Yes |
| Repository free space | This alarm checks whether a backup repository is running out of space. | Backup repository | Yes |
| Scale-out backup repository offload session state | This alarm checks whether a scale-out backup repository offload, download, archiving, or retrieval data transfer session failed or finished with a warning. | Job | Yes |
| Server agent backups stored in cloud repository | This alarm checks whether the number of server agent backups stored in a cloud repository exceeds the maximum allowed limit. | Cloud repository | Yes |
| SureBackup job session state | This alarm checks whether one or more verification checks specified in the SureBackup job failed. | VM job (SureBackup) | Yes |
| Veeam Backup & Replication version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam Backup & Replication or Veeam Cloud Connect server version and the server requires upgrade. | Backup server | Yes |
| User cloud storage quota | This alarm tracks whether a user is running out of space on a cloud repository. | User | Yes |
| Veeam ONE license expiration | This alarm checks whether the Veeam ONE product license has expired. | Veeam ONE server | Yes |
| Veeam ONE server connection state | This alarm checks the connection status between Veeam Service Provider Console and Veeam ONE server. | Veeam ONE server | Yes |
| Veeam ONE server license exceeded | This alarm checks whether the Veeam ONE product license was exceeded. | Veeam ONE server | Yes |
| Veeam ONE support contract expiration | This alarm checks whether the Veeam ONE prepaid support contract has expired. | Veeam ONE server | Yes |
| Veeam ONE version is out-of-date | This alarm checks whether Veeam Service Provider Console no longer supports Veeam ONE server version and the server requires upgrade. | Veeam ONE server | Yes |
| VM without backup | This alarm checks whether VMs managed with Veeam Backup & Replication have been backed up within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| VM without replica | This alarm checks whether VMs managed with Veeam Backup & Replication have been replicated within the defined RPO (Recovery Point Objective) interval. | Backup server | Yes |
| VMs in the backup repository | This alarm checks whether the number of VMs stored in a backup repository exceeds the maximum allowed limit. | Backup repository | No |
| VMs stored in cloud repository | This alarm checks whether the number of VMs stored in a cloud repository exceeds the maximum allowed limit. | Cloud repository | Yes |
| WAN accelerator connection state | This alarm checks the connection status between a Veeam backup server and WAN accelerator. | WAN accelerator | Yes |
| WAN accelerator version is out-of-date | This alarm checks whether the version of a WAN accelerator matches the version of Veeam Backup & Replication installed on a backup server. | WAN accelerator | Yes |
| Workstation agent backups stored in cloud repository | This alarm checks whether the number of workstation agent backups stored in a cloud repository exceeds the maximum allowed limit. | Cloud repository | Yes |


