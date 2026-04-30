---
title: "Obtaining Management Agent Setup File"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/obtain_agent_setup_file.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# Obtaining Management Agent Setup File


To deploy Veeam Service Provider Console management agent on machines hosting Veeam products, you must obtain the management agent setup file. To download the management agent setup file, you can use one of the following options:

* [Download the setup file in Veeam Service Provider Console](#download).

* [Create the setup file download link](#link).
* [Download the setup file using link in the cloud tenant welcome email](#email).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Company Owner, Company Administrator, Company Tenant, Location Administrator.

Downloading Management Agent Setup File in Veeam Service Provider Console

You can download the management agent setup file in Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. At the top of the computers list, click Download Management Agent and select OS type: Windows, Linux or macOS.

Alternatively, you can right-click the necessary computer and choose Download Management Agent.

1. In the Download Management Agent for Windows/Linux/Mac window, specify management agent settings:

* In the Cloud Tenant and Location lists, select cloud tenant account and company location to which you want to assign the management agent. Selected cloud tenant and location names will be added to the agent setup file name and the management agent will be preconfigured to connect to Veeam Service Provider Console with your company settings.

* In the Token expiry period field, specify the time period for which you want to verify the management agent. Management agents installed after the specified period expires will not be able to connect to Veeam Service Provider Console automatically. To verify the agent, you will have to contact your service provider. Management agents that are already connected to Veeam Service Provider Console will not be affected.

It is recommended to specify an expiry period of 6 months or less.

[![Download Management Agent](images/download_agent.webp)](images/download_agent.webp "Download Management Agent")

1. Click Download.

The setup file will be saved to the default download location on your computer.

Creating Management Agent Setup File Link in Veeam Service Provider Console

If you do not want to manually deploy management agent setup files on managed computers, you can create a download link for a preconfigured management agent.

To copy the management agent setup file link from Veeam Service Provider Console:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Managed Computers.
2. Open the Discovered Computers tab.
3. At the top of the computers list, click Download Management Agent and select OS type: Windows, Linux or macOS.

Alternatively, you can right-click the necessary computer and choose Download Management Agent.

1. In the Download Management Agent for Windows/Linux/Mac window, specify management agent settings:

* In the Cloud Tenant and Location lists, select cloud tenant account and company location to which you want to assign the management agent. Selected cloud tenant and location names will be added to the agent setup file name and the management agent will be preconfigured to connect to Veeam Service Provider Console with your company settings.

* In the Token expiry period field, specify the time period for which you want to verify the management agent. Management agents installed after the specified period expires will not be able to connect to Veeam Service Provider Console automatically. To verify the agent, you will have to contact your service provider. Management agents that are already connected to Veeam Service Provider Console will not be affected.

It is recommended to specify an expiry period of 6 months or less.

1. Click Create Download Link.

Veeam Service Provider Console will generate a download link for the management agent.

If you have changed the management agent settings after creating a download link, click New Link to generate a new download link.

1. Click Copy to copy the download link.

[![Copy Management Agent Link](images/copy_agent_link.webp)](images/copy_agent_link.webp "Copy Management Agent Link")

After creating a download link, you can use the link to download management agent setup file directly from remote computers.

Downloading Management Agent Setup File Using Link in Cloud Tenant Welcome Email

Company users can download the preconfigured management agent setup file using a link in the welcome email message sent to the Company Owner.

Note that management agent setup files provided in the default welcome email have an expiry period of 2 days.


