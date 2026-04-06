---
title: "Installing Veeam Backup Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/install_backup_agents.html"
last_updated: "10/4/2024"
product_version: "9.1.0.30636"
---

# Installing Veeam Backup Agents


To manage Veeam backup agents in Veeam Service Provider Console, you must deploy two software components on managed computers:

* Veeam Service Provider Console management agent

This software component acts as a broker between Veeam backup agent and Veeam Service Provider Console. The management agent is responsible for transmitting commands from Veeam Service Provider Console to Veeam backup agent, performing management, software installation and configuration operations on a managed computer, collecting data from Veeam backup agent and communicating it back to Veeam Service Provider Console. For details on management agents, see [Managing Veeam Service Provider Console Agents](manage_vac_agents.md).

* Veeam backup agent

This software component is responsible for all types of data protection and restore operations on a managed computer.

You can use one of the following methods to deploy Veeam backup agent on computers in client and hosted infrastructures:

* [Install Veeam backup agents with discovery rules](install_agents_discovery.md). You can configure discovery rules to automatically install Veeam Service Provider Console management agents and Veeam backup agents on discovered computers. We recommend this method for the deployment of Veeam Agent for Microsoft Windows and Veeam Agent for Linux software.
* [Install Veeam Agent for Mac and management agent manually](deploy_management_agents_mac.md). You can use this method to install Veeam Service Provider Console management agent and Veeam Agent for Mac on selected computers. We recommend this method for the deployment of Veeam Agent for Mac software.
* [Install Veeam backup agents automatically](automate_discovery_installation.md). You can configure the automatic deployment of Veeam Agent for Microsoft Windows and Veeam Agent for Linux and automatic Veeam Agent for Mac policy assignment for management agents installed outside Veeam Service Provider Console.
* [Install Veeam backup agents manually](install_agents_manually.md). You can use this method to install Veeam backup agents on selected computers without running discovery rules.


