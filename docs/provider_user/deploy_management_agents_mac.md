---
title: "Deploying Mac Management Agents"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/deploy_management_agents_mac.html"
last_updated: "7/9/2024"
product_version: "9.1.0.30636"
---

# Deploying Mac Management Agents


Agent setup file for computers running macOS operating system contains both Veeam Service Provider Console management agent and Veeam Agent for Mac. Veeam Agent for Mac will be installed automatically after deployment of the management agent.

To install a management agent and Veeam Agent for Mac on a computer running macOS operating system:

1. Log on to the machine where you want to install the management agent and Veeam Agent for Mac.
2. Copy the agent setup file on a machine where you want to install the management agent and Veeam Agent for Mac.

Make sure that you have permission to execute the setup file.

1. Double-click the agent setup file to launch the Veeam Management Agent wizard.
2. Follow steps of the wizard.
3. At the Installation Type step of the wizard, click Install.

If Veeam Agent for Mac is already installed on the managed computer, click Customize and clear the Install Backup Agent check box.

1. To start the installation, provide credentials of an account with administrator permissions on the managed computer and click Install Software.
2. When installation completes, click Close.

The agent will be installed in the /Applications folder on the system disk.

Note that for Veeam Service Provider Console management agent to deploy Veeam Agent for Mac on the managed computer, you must allow access to the folder where the installation file resides.

|  |
| --- |
| Tip: |
| You can install Veeam Service Provider Console management agent and Veeam Agent for Mac using the command line interface. For details on installation command-line syntax, see section [Veeam Service Provider Console Management Agent for Mac](https://helpcenter.veeam.com/docs/vac/deployment/silent_install_agent_mac.html?ver=9.1) of the Deployment Guide. |

If you have downloaded the management agent setup file from Veeam Service Provider Console, it will connect to Veeam Service Provider Console automatically. Otherwise, you must configure the management agent manually.

Configuring Management Agent

To configure the management agent:

1. Use the following command:

|  |
| --- |
| sudo veeamconsoleconfig -g add <gateway>:<port> --validate\_cert <thumbprint> |

where:

* <gateway> — FQDN or IP address of a cloud gateway.

* <port> — the port on the cloud gateway that is used to transfer data to Veeam Service Provider Console.
* [optional] <thumbprint> — thumbprint of the security certificate that is installed on the Veeam Service Provider Console server.

|  |
| --- |
| Important! |
| It is strongly recommended to provide a certificate thumbprint for automated verification of the security certificate. Do not use the --validate\_cert command with -f argument. |

Management agent will connect to Veeam Service Provider Console server and verify the security certificate.

1. If you did not specify a certificate thumbprint, you will be asked to verify the security certificate.

After you verify the certificate, management agent will restart and apply connection settings automatically.

1. Wait for the agent to connect to Veeam Service Provider Console.

After you have configured the management agent, it is recommended to specify a custom tag for the managed computer. For details, see [Assigning Custom Tags to Veeam Backup Agents](assign_vba_tag.md#unix).


