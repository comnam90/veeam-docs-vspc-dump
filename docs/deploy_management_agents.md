---
title: "Deploying Management Agents Manually"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/deploy_management_agents.html"
last_updated: "11/21/2025"
product_version: "9.1.0.30636"
---

# Deploying Management Agents Manually


You can deploy Veeam Service Provider Console management agents on managed computers manually. This method does not require you to perform preliminary discovery of computers in Veeam Service Provider Console.

Prerequisites

Before you install management agents, check the following prerequisites:

* Obtain the management agent setup file.

For details, see [Obtaining Management Agent Setup File](obtain_agent_setup_file.md).

* [For Microsoft Windows computers] Make sure you have an account with local Administrator permissions on all managed computers.
* [For Linux and macOS computers] Make sure you have the root account or any user account with super user privileges on all managed computers.
* If you plan to use the management agent as a master agent for discovery:

* Make sure that the machine that will host the master agent has access to the Internet, and network access to all computers that you want to discover in the managed infrastructures.
* [For Microsoft Windows computers] If you plan to discover computers using an Active Directory discovery method, make sure the machine that will host the master agent is part of a domain within which computers will be discovered.
* [For Microsoft Windows computers] Make sure you have an account with local Administrator permissions on all computers that you want to discover.
* [For Linux computers] Make sure you have the root account or any user account with super user privileges on all computers that you want to discover.

In This Section

* [Deploying Windows Management Agents](deploy_management_agents_win.md)
* [Deploying Linux Management Agents](deploy_management_agents_lin.md)
* [Deploying Mac Management Agents](deploy_management_agents_mac.md)


