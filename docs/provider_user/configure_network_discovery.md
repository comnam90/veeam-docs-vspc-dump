---
title: "Configuring Network-Based Discovery Rules"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/configure_network_discovery.html"
last_updated: "8/11/2025"
product_version: "9.1.0.30636"
---

# Configuring Network-Based Discovery Rules


Network-based discovery rules allow you to discover computers based on a range of IP addresses you specify. This method is recommended for small environments, with no Active Directory domains.

Prerequisites

Before you configure a network-based discovery rule:

* Deploy a master agent on a machine in the company infrastructure.

For details, see [Deploying Management Agents Manually](deploy_management_agents.md).

* Make sure you have an account with local Administrator permissions on all computers that you want to discover.

This prerequisite is not required if you have specified a discovery account in the master agent configuration settings. For details, see [Deploying Windows Management Agents](deploy_management_agents_win.md).

* Make sure that remote computers are powered on and configured to allow discovery: the Remote Scheduled Tasks Management (RPC and RPC-EPMAP) firewall rules must allow inbound traffic.
* On remote computers that run a Windows desktop OS, the Windows Management Instrumentation (WMI-In) firewall rule must be configured to allow inbound traffic.
* If you plan to install Veeam backup agents as part of the discovery procedure, make sure that remote computers are configured to allow installation: the File and Printer Sharing (SMB-In) firewall rule must allow inbound traffic.

* If you plan to assign a backup policy as part of the discovery procedure, create a new backup policy or check and if necessary customize one of the predefined policies.

For details, see [Configuring Backup Policies](configure_backup_policies.md).

Configuring Network-Based Discovery Rule

To configure a network-based discovery rule:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Rules.
2. On the Rules tab, click New and select Windows.

Veeam Service Provider Console will launch the New Windows Discovery Rule wizard.

1. At the Rule Name step of the wizard, specify a discovery rule name.

[![Specify Discovery Rule Name](images/discovery_rule_name.webp)](images/discovery_rule_name.webp "Specify Discovery Rule Name")

1. At the Locations step of the wizard, click a link in the Master Agent column and select a management agent that will be used as the master agent for discovery in each company location.

By default, discovery is performed in all company locations where you deployed a master agent. If you choose to perform discovery in multiple locations, after you complete the wizard steps, Veeam Service Provider Console will create a separate discovery rule for each location. If you do not want to perform discovery in some company locations, clear the check boxes next to these locations.

For details on working with company locations, see [Managing Locations](manage_locations.md).

[![Choose Master Agent](images/discovery_rule_agent_sp.webp)](images/discovery_rule_agent_sp.webp "Choose Master Agent")

1. At the Discovery Method step of the wizard, select Network-based discovery.

[![Choose Discovery Method](images/discovery_rule_method_network.webp)](images/discovery_rule_method_network.webp "Choose Discovery Method")

1. At the Network Discovery step of the wizard, specify one or more networks and IP ranges that must be scanned to discover computers:

1. Click Add.

Veeam Service Provider Console will open the Add Network IP Range window.

1. In Network field, type an arbitrary name of the network that must be scanned.
2. In the IP range fields, type a range of IP addresses that must be scanned in the specified network.
3. Click OK.
4. Repeat steps a-d for each new IP range you want to include in the rule.
5. In the Exclusion mask field, specify a mask for names of computers that must be excluded from discovery.

The mask can contain the asterisk (\*) that stands for zero or more characters. You can specify multiple masks separated with commas.

[![Specify IP Range](images/discovery_rule_ip_range.webp)](images/discovery_rule_ip_range.webp "Specify IP Range")

1. At the Access Account step of the wizard, specify credentials of an account that the master agent will use to connect to computers within the discovery scope. The account must have local Administrator permissions on all discovered computers.

If you have specified a discovery account in the master agent configuration settings, select the Use credentials specified in the master management agent configuration check box. For details on specifying master agent configuration settings, see [Deploying Windows Management Agents](deploy_management_agents_win.md).

Credentials specified in the master agent configuration take precedence over credentials specified in the discovery rule. For discovery, the master agent will use an account specified in its configuration settings. In case this account is not valid or not set, the master agent will use an account specified in the discovery rule.

[![Specify Discovery Account](images/discovery_rule_account.webp)](images/discovery_rule_account.webp "Specify Discovery Account")

1. At the Discovery Filters step of the wizard, choose what filters you want to enable for discovery.

* To filter computers by OS type, select By OS type in the list and click Edit. In the Operating System window, select the type of OS that must run on discovered computers (Server operating system, Client operating system). Click OK.
* To filter computers by application, select By application in the list and click Edit. In the Application window, select applications that must run on discovered computers (Microsoft Exchange Server, Microsoft SQL Server, Microsoft Active Directory, Microsoft SharePoint, Oracle Database, Other Applications). Click OK.
* To filter computers by platform, select By platform in the list and click Edit. In the Platform window, select platforms on which discovered computers must run (Virtual infrastructure, Physical computers, Microsoft Azure, Amazon Web Services, Google Cloud, Other). Click OK.
* If you want to perform discovery among accessible computers only, select the Do not show inaccessible computers check box.

|  |
| --- |
| Note: |
| Different types of filter conditions are joined using Boolean AND operator. For example, if you enable filters Server operating system, Microsoft SQL Server and Virtual infrastructure, the list of discovered computers will include only VMs that run Windows Server OS and Microsoft SQL Server. |

[![Choose Discovery Filters](images/discovery_rule_filters.webp)](images/discovery_rule_filters.webp "Choose Discovery Filters")

1. At the Email Notification step of the wizard, you can enable notifications about discovery results by email.

1. Select the Send notifications check box and specify a schedule according to which email notifications must be sent.
2. In the To field, specify an email address at which the email notification must be sent.
3. In the Subject field, specify the subject of the notification.
4. Select the Send notification email after the first run check box if a notification about discovery results must be sent after the first run of the discovery rule, regardless of the specified schedule.

[![Specify Notification Settings](images/discovery_rule_email.webp)](images/discovery_rule_email.webp "Specify Notification Settings")

1. At the Backup Agent Deployment step of the wizard, specify whether you want to install Veeam backup agents on discovered computers:

1. If you do not want to install Veeam backup agents as part of the discovery process, leave the Discover remote computer without installing backup agent option selected.
2. If after discovery Veeam backup agents must be installed automatically, select the Discover remote computer, install backup agent and assign the selected backup policy option.

From the Backup policy to apply list, choose a backup policy that must be assigned immediately after installation. To view the selected policy details, click the Show link. If you do not want to assign any backup policy after installation, choose No policy from the list.

If you do not have the necessary backup policy configured yet, you can click the Create New link to create a new policy, without exiting the New Rule wizard. For details on backup policies, see [Configuring Backup Policies](configure_backup_policies.md).

1. By default, the read-only access mode is enabled for all Veeam backup agents installed as part of discovery. To disable the read-only access mode for Veeam backup agents on discovered computers, set the Read-only UI access for the backup agent toggle to Off.

For details on the read-only access mode for Veeam backup agents, see [Enabling Read-Only Access Mode](enable_read_only_mode.md).

1. To push global settings for Veeam backup agents, click Configure and specify default global settings for Veeam backup agents. For details on the global settings for Veeam backup agents, see [Configuring Global Settings for Veeam Agent for Microsoft Windows](configure_backup_agent_settings.md).

[![Review Discovery Settings](images/discovery_rule_vaw.webp)](images/discovery_rule_vaw.webp "Review Discovery Settings")

1. At the Schedule step of the wizard, specify schedule according to which discovery must be performed:

1. Select the Run this rule automatically check box, if you want to enable scheduling for the discovery rule.
2. Define scheduling settings:

* To run discovery at specific time daily, on defined week days or with specific periodicity, select the Daily at option. Use the fields on the right to configure the necessary schedule.
* To run discovery once a month on specific days, select the Monthly at option. Use the fields on the right to configure the necessary schedule.
* To run discovery repeatedly throughout a day with a specific time interval, select the Periodically every option. In the field on the right, select the necessary time unit: Days, Hours or Minutes.

* To run discovery continuously, select the Periodically every option and choose Continuously from the list on the right. A new discovery session will start as soon as the previous discovery session finishes.

1. From the Time zone drop-down list, select the time zone in which daily and monthly schedule must be run.

[![Configure Discovery Schedule](images/discovery_rule_schedule_nw.webp)](images/discovery_rule_schedule_nw.webp "Configure Discovery Schedule")

1. At the Summary step of the wizard, review discovery rule settings and click Finish.

To start discovery after you save the rule, in the pop-up window, click Yes.

[![Review Discovery Settings](images/discovery_rule_review.webp)](images/discovery_rule_review.webp "Review Discovery Settings")


