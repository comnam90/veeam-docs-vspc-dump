---
title: "Connecting to Existing Veeam Backup for Microsoft Azure Appliances"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/clouds_connect_azure.html"
last_updated: "11/14/2025"
product_version: "9.1.0.30636"
---

# Connecting to Existing Veeam Backup for Microsoft Azure Appliances


To connect Veeam Service Provider Console to an existing Veeam Backup for Microsoft Azure appliance:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances.
5. At the top of the list, click New and select Microsoft Azure.

Veeam Service Provider Console will open the New Azure Appliance wizard.

1. At the Deployment Mode step of the wizard, specify Veeam Cloud Connect site on which you want to register the appliance and select Connect to an existing appliance.

[![Select Deployment Mode](images/connect_azure_mode.webp)](images/connect_azure_mode.webp "Select Deployment Mode")

1. At the Account step of the wizard, specify Microsoft Azure account settings:

1. In the Account list, select a Microsoft Azure account that will be used for appliance configuration.

If you want to add a new account, click New. Veeam Service Provider Console will open the New Microsoft Azure Account wizard. For details, see [Adding Microsoft Azure Accounts](clouds_azure_accounts.md).

1. In the Destination section, select Microsoft Azure subscription and datacenter where the appliance resides.

[![Specify AWS Account](images/connect_azure_account.webp)](images/connect_azure_account.webp "Specify AWS Account")

1. At the Virtual Machine step of the wizard, select the virtual machine on which Veeam Backup for Microsoft Azure appliance is deployed:

1. Click Select.
2. In the Available Virtual Machines window, select the necessary VM and click Apply.
3. In the Description field, specify VM description.

[![Select EC2 Instance](images/connect_azure_vm.webp)](images/connect_azure_vm.webp "Select EC2 Instance")

1. At the Connection Type step of the wizard, choose whether the appliance is connected directly to the internet or located in a private network:

1. If the appliance is connected directly to the internet, and you want the Veeam Cloud Connect server to be connected to the appliance also through the internet, select Direct connection. In this case, Veeam Cloud Connect server will detect the IP address of the Veeam Backup for Microsoft Azure appliance automatically.
2. If the appliance is located in a private network and the Veeam Cloud Connect server is located in the same private network, or you want Veeam Cloud Connect server to connect to the appliance over Veeam PN, select Private network.

In the Address field, specify the private IP or DNS name of the Veeam Backup for Microsoft Azure appliance.

[![Specify Connection Type](images/connect_azure_network.webp)](images/connect_azure_network.webp "Specify Connection Type")

1. At the Guest OS step of the wizard, select account of a user that has administrative privileges on the Veeam Backup for Microsoft Azure appliance(Service Provider Administrator account).

Note that the accounts list includes only accounts created in Veeam Service Provider Console. For details on creating guest OS accounts, see [Adding Guest OS Accounts](clouds_guest_accounts.md).

To create a new Service Provider Administrator account, click New. In the New Account window, specify account credentials and click Apply.

[![Specify Guest OS Credentials](images/connect_azure_credentials.webp)](images/connect_azure_credentials.webp "Specify Guest OS Credentials")

1. If the certificate installed on the Veeam Backup for Microsoft Azure appliance is not trusted, Veeam Service Provider Console will display a warning.

* To view detailed information about the certificate, click View.
* Click Connect to trust the certificate.

After the appliance is deployed, you will have to verify the certificate manually. For details, see [Verifying Appliances](clouds_verify_certificate.md).

* If you do not trust the certificate, click No. In this case, you will not be able to connect to the appliance.

1. At the Summary step of the wizard, review the appliance settings and click Finish.

Checking Deployment Results

To make sure that appliance deployment has completed successfully, complete the following steps:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Appliances and find the necessary appliance in the list.
5. Check the value in the Deployment Status column.

If deployment was successful, the Deployment Status status must be Success.

1. Click a link in the Deployment Status column to display session details of the deployment procedure.

If the appliance was connected successfully but the Deployment Status status is Error, click Clear Logs to update the status.


