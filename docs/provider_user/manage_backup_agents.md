---
title: "Managing Veeam Backup Agents"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/manage_backup_agents.html"
last_updated: "8/26/2025"
product_version: "9.1.0.30636"
---

# Managing Veeam Backup Agents


Veeam Service Provider Console allows you to automate deployment and management of the Veeam Agent for Microsoft Windows, Veeam Agent for Linux and Veeam Agent for Mac software (or, in short, Veeam backup agents).

|  |
| --- |
| Note: |
| This section covers management of Veeam backup agents in Veeam Service Provider Console. To learn how to manage backup agents using Veeam Backup & Replication console, see [Veeam Agent Management Guide](https://helpcenter.veeam.com/docs/vbr/userguide/agents_introduction.html?ver=13). |

With Veeam Service Provider Console, you can install Veeam backup agents on remote computers that reside in managed company infrastructure, and perform various types of configuration and management operations, such as configuring backup job settings, starting and stopping backup jobs and so on.

To deploy and manage Veeam backup agents in Veeam Service Provider Console, keep to the following sequence of steps:

1. [Install Veeam backup agents](install_backup_agents.md).

Veeam Service Provider Console supports several methods for installing Veeam backup agents, including installation with discovery rules (for Veeam Agent for Microsoft Windows and Veeam Agent for Linux), installation using 3rd-party automation tools, and manual software installation.

1. [Configure Veeam backup agent job settings](configure_backup_agent_jobs.md).

To automate Veeam backup agent job configuration for multiple computers, create and assign backup policies. Alternatively, you can perform configuration of backup job settings manually, on a per-computer basis.

1. [Optional] [Enable Read-Only access mode](enable_read_only_mode.md).

To prevent end users from changing Veeam backup agent job settings and performing volume-level restore operations on Veeam Agent for Microsoft Windows, you can enable read-only access mode.

1. [Configure Veeam backup agent global settings](configure_backup_agent_settings.md).

Check and if necessary change Veeam backup agent global settings on managed computers.

1. [Manage Veeam backup agent jobs](manage_backup_agent_jobs.md).

To administer data protection operations in company infrastructure, you can start, stop, enable and disable Veeam backup agent jobs on managed computers. You can also monitor Veeam backup agent jobs that are managed by your Veeam Backup & Replication servers.

1. [Create backup reports](backup_reports.md).

To analyze the efficiency of data protection with Veeam backup agents, and make sure you can meet established RPO requirements for managed company infrastructure, you can configure and run backup reports.


