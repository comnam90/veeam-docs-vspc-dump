---
title: "Connecting Veeam ONE Servers"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/one_connect_servers.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Connecting Veeam ONE Servers


To allow Veeam Service Provider Console to communicate with a hosted Veeam ONE server, you must configure a connection to this server.

When you connect a hosted Veeam ONE server to Veeam Service Provider Console, Veeam Service Provider Console deploys its management agent on the Veeam ONE server. The management agent is responsible for transmitting commands from Veeam Service Provider Console to Veeam ONE server, performing management operations, collecting data from Veeam ONE and communicating it back to Veeam Service Provider Console.

Connecting Veeam ONE Servers

To configure a connection to the Veeam ONE server:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam ONE plugin tile.
4. In the menu on the left, click Servers.
5. At the top of the server list, click New.

Veeam Service Provider Console will launch the New Server wizard.

1. At the Name step of the wizard, specify the following settings:

1. In the DNS name or IP address of the server field, type FQDN or IP address of the computer where Veeam ONE Server component is deployed.
2. In the Description field, type server description or comments.

[![Specify Server Address](images/connect_one_server_name.webp)](images/connect_one_server_name.webp "Specify Server Address")

1. At the Connection Account step of the wizard, specify credentials of a user account with local Administrator privileges on the Veeam ONE server.

This account will be used to install a Veeam Service Provider Console management agent on the Veeam ONE server.

The user name must be specified in the DOMAIN\USERNAME format for domain accounts, or HOST\USERNAME format for local accounts.

[![Specify Connection Account Credentials](images/connect_one_server_credentials.webp)](images/connect_one_server_credentials.webp "Specify Connection Account Credentials")

1. At the Summary step of the wizard, review connection settings and click Finish.

[![Review Connection Settings](images/connect_one_server_review.webp)](images/connect_one_server_review.webp "Review Connection Settings")

1. Repeat steps 6–10 for all Veeam ONE servers that you want to add.

Checking Installation Results

To make sure that installation of management agents has completed successfully, complete the following steps:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam ONE plugin tile.
4. In the menu on the left, click Servers and find the necessary Veeam ONE server in the list.
5. Check the value in the Deployment Status column.

If installation was successful, the Deployment Status status must be Success.

1. Click a link in the Deployment Status column to display session details of the installation procedure.

If the server was connected successfully but the Deployment Status status is Error, click Clear Logs to update the status.

In some cases, after installation you may need to perform additional operations. For example, if the setup detects a pending computer reboot, the list of installation session details, will display a warning notifying that reboot is required. To complete the installation, you can initiate computer reboot in Veeam Service Provider Console. For details, see [Rebooting Remote Computers](reboot_remote_computers.md).


