---
title: "Resetting Company Security Token"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/reset_company_security_token.html"
last_updated: "6/4/2025"
product_version: "9.1.0.30636"
---

# Resetting Company Security Token


You can reset the security token used to connect new company management agents to Veeam Service Provider Console. After you reset the security token, previously downloaded management agents will not be able to connect to Veeam Service Provider Console. Management agents that are already connected to Veeam Service Provider Console will not be affected.

If you have downloaded setup files for management agents assigned to the company but did not install the management agents before resetting the security token, the setup files will become invalid. Agents installed from these setup files will have the Unverified connection status. You will have to verify the agent manually by setting company to the agent. For details, see [Setting Company to Management Agents](set_company.md).

To install company management agents that will connect to Veeam Service Provider Console automatically, you will have to obtain new management agents setup files. For details, see [Obtaining Management Agent Setup File](obtain_agent_setup_file.md).

Required Privileges

To perform this task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Resetting Company Security Token

To reset company security token:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary companies in the list.
3. At the top of the list, click Manage > Reset Security Token.

Alternatively, you can right-click the necessary company, choose Manage and select Reset Security Token.

1. In the confirmation window, click Yes.


