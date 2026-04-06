---
title: "How to Deploy Windows Management Agents with GPO"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/deploy_management_agents_gpo.html"
last_updated: "11/8/2023"
product_version: "9.1.0.30636"
---

# How to Deploy Windows Management Agents with GPO


This topic describes how you can deploy the Veeam Service Provider Console management agent setup file to remote computers using GPO.

You must create an MST file with custom configuration parameters and use this MST file to deploy the Veeam Service Provider Console management agents on remote computers. The management agents will use parameters specified in the MST file to connect to a cloud gateway on the service provider side.

Required Details

Obtain the following data from the service provider:

* Port on the cloud gateway used to transfer backup data to and from cloud repositories
* Thumbprint of a certificate that is installed on the Veeam Service Provider Console and Veeam Cloud Connect servers

Step 1. Unpack Management Agent Setup Files

Unpack the content of the management agent setup file:

1. Obtain the necessary version of the Veeam Service Provider Console management agent setup file from your service provider.

1. Copy the unpacked files to a network share.

The network share must be accessible from all remote computers on which you want to deploy the management agent.

Make sure you set at least Read permissions on the files.

Step 2. Create MST Configuration File

Create an MST configuration file with installation parameters that point to the necessary cloud gateway:

1. In the directory with the setup file, open the management agent setup file for edit with Orca.

For details on Orca, see [Windows Dev Center](https://msdn.microsoft.com/en-us/library/windows/desktop/aa370557%28v%3Dvs.85%29.aspx).

1. In the menu, choose Transform > New Transform.
2. In the Tables pane, click Property.
3. Add the following properties to the table:

* ACCEPT\_THIRDPARTY\_LICENSES — specifies if you want to accept the terms of the license agreement for the 3rd party components.

Specify 1 if you want to accept the terms and proceed with installation.

* ACCEPT\_EULA — specifies if you want to accept the terms of the Veeam license agreement.

Specify 1 if you want to accept the terms and proceed with installation.

* ACCEPT\_LICENSING\_POLICY — specifies if you want to accept the terms of the Veeam licensing policy.

Specify 1 if you want to accept the terms and proceed with installation.

* ACCEPT\_REQUIRED\_SOFTWARE — specifies if you want to accept the terms of the required software license agreement.

Specify 1 if you want to accept the terms and proceed with installation.

* VAC\_CERT\_THUMBPRINT — thumbprint of a certificate that is installed on the Veeam Service Provider Console server, and used to secure traffic between the service provider and clients.

The thumbprint is used to verify the authenticity of the certificate. Although this property is optional, it is recommended that you specify it.

1. If your service provider has changed the default port number when deploying the cloud gateway, locate the CC\_GATEWAY\_PORT property and change the port value.

1. In the menu, choose Transform > Generate Transform.
2. Save the MST file with configuration details.
3. Close Orca.
4. Copy the MST to a network share.

The network share must be accessible from all remote computers on which you want to deploy the management agent.

Make sure you set at least Read permissions on the file.

[![Edit MST File](images/create_mst.webp)](images/create_mst.webp "Edit MST File")

Step 3. Create Group Policies

Create a Group Policy that will install and configure the management agent on remote computers:

1. Log on to a domain controller.
2. Open the Group Policy Management Console.
3. Right-click the OU which includes computers on which management agents must be deployed, and choose to create a new Group Policy Object.
4. Right-click the Group Policy Object and choose Edit.
5. In the left pane of the Group Policy Management Editor, expand Computer Configuration > Policies > Software Settings.
6. Right-click Software Installation and select New > Package.
7. In the Open window, point to the management agent setup file located on the network share.
8. In the Deploy Software window, choose the Advanced deployment method.
9. Open the Modifications tab, click Add and choose the MST file located on the network share.
10. Click OK.
11. In the left pane of the Group Policy Management Editor, expand Computer Configuration > Policies > Administrative Templates > System > Logon.
12. Right-click the Always wait for the network at computer startup and logon policy setting and choose Edit.
13. In the policy setting window, select Enabled and click OK.
14. Close the Group Policy Management Editor.

[![Create Group Policy](images/create_group_policy.webp)](images/create_group_policy.webp "Create Group Policy")

Step 4. Apply Group Policies to Remote Computers

Apply the created Group Policy to remote computers.


