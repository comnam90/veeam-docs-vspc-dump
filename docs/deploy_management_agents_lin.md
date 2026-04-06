---
title: "Deploying Linux Management Agents"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/deploy_management_agents_lin.html"
last_updated: "11/21/2025"
product_version: "9.1.0.30636"
---

# Deploying Linux Management Agents


To install a management agent on a managed computer running Linux operating system:

1. Log on to the machine where you want to install the management agent.
2. Copy the agent setup file on a machine where you want to install the management agent.

Make sure that you have permission to execute the setup file.

1. Install the agent with the following command:

|  |
| --- |
| sudo <...>/’LinuxAgentPackages.<company\_name>\_<location\_name>.sh’ |

or

|  |
| --- |
| sudo sh <...>/’LinuxAgentPackages.<company\_name>\_<location\_name>.sh’ |

or

|  |
| --- |
| sudo bash <...>/’LinuxAgentPackages.<company\_name>\_<location\_name>.sh’ |

where:

* <...> — path to the directory where you have saved the setup file.

* <company\_name> — name of the company to which the management agent is assigned.
* <location\_name> — name of the location to which the management agent is assigned.

If you have downloaded an agent not assigned to any company, the setup file name will be LinuxAgentPackages.sh.

If you have downloaded the management agent setup file from Veeam Service Provider Console and the management agent is assigned to a company, it will connect to Veeam Service Provider Console automatically. Otherwise, you must configure the agent manually.

After installation, Veeam Service Provider Console management agent will operate under the new veeam-usr-vspc-agent user.

Configuring Management Agent

To configure a management agent:

1. Use the following command:

|  |
| --- |
| sudo veeamconsoleconfig -g add <gateway>:<port> --validate\_cert <thumbprint> |

where:

* <gateway> — FQDN or IP address of a cloud gateway.

For hosted management agents, specify FQDN or IP address of Veeam Service Provider Console portal.

* <port> — the port  that is used to transfer data to Veeam Service Provider Console.
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

|  |
| --- |
| Tip: |
| To see all available actions for managing the agent, use the following command: veeamconsoleconfig -h. |


