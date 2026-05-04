---
title: "Setting Master Agent for Discovery"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/set_master_agent.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Setting Master Agent for Discovery


A Veeam Service Provider Console management agent can act as a client agent or as a master agent.

* Client management agent is used to interact with Veeam backup agent, Veeam Backup & Replication, Veeam ONE or Veeam Backup for Microsoft 365 on a computer.
* Master management agent is used to perform discovery of computers in the managed infrastructure, and automate installation and update of Veeam backup agents.

For details, see [Installing Veeam Backup Agents with Discovery Rules (Recommended)](install_agents_discovery.md) and [Upgrading Veeam Backup Agents](update_backup_agents.md).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Location Administrator.

Checking Management Agent Role

You can check what role is currently assigned to a management agent:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. [For management agents deployed with a discovery rule] Do the following:

1. In the Rule list at the top, select the necessary discovery rule.
2. To limit the scope of discovered computers, use the location filters at the top left corner of the Veeam Service Provider Console window.

For example, this can be required if you want to find a computer that runs a master agent in a specific company location.

1. On the right of the computers list header, click the ellipsis and choose to display the Agent Role column.
2. Check the value in the Agent Role column.

For a client management agent, the value is set to Client. For a master agent, the value is set to Master.

1. [For management agents deployed outside Veeam Service Provider Console] Do the following:

1. In the Rule list at the top, select External Discovery.
2. To limit the scope of discovered computers, use the location filters at the top left corner of the Veeam Service Provider Console window.

For example, this can be required if you want to find a computer that runs a master agent in a specific company location.

1. On the right of the computers list header, click the ellipsis and choose to display the Agent Role column.
2. Check the value in the Agent Role column.

For a client management agent, the value is set to Client. For a master agent, the value is set to Master.

Setting New Master Agent

You can assign the role of a master agent to a management agent. Thus, you can change a master agent for a discovery rule: the role of a master agent will be moved from one management agent to another one. Note that when you move the master agent role from one management agent to another, both management agents must belong to the same discovery rule scope.

To set a new master agent for a discovery rule:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. In the Rule list, select the necessary discovery rule.
4. Click Filter. In the Management agent status section, select the Healthy check box only. Click Apply.

The list of discovered computers will display computers with management agents installed and in healthy state.

1. Select the necessary computer in the list.
2. At the top of the list, click Management Agent and choose Set as Master.

Alternatively, you can right-click the necessary management agent, choose Management Agent and select Set as Master.

1. In the list of discovered computers, make sure that the Agent Role value for the selected computer changed to Master.


