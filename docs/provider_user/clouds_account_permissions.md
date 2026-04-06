---
title: "Managing Account Permissions"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/clouds_account_permissions.html"
last_updated: "8/20/2025"
product_version: "9.1.0.30636"
---

# Managing Account Permissions


If you modified the account permissions and did not grant the missing permissions during account editing, you can grant permissions in Veeam Service Provider Console plugin:

Granting Account Permissions

To grant the necessary permissions to a Veeam Backup for Public Clouds account:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Accounts and navigate to Public Clouds.
5. Select the necessary account in the list.
6. At the top of the list, click Check Permissions.

Alternatively, you can right-click the necessary account and choose Check Permissions.

Veeam Service Provider Console will open the Permissions Check window.

1. [For Veeam Backup for Amazon Web Services and Veeam Backup for Microsoft Azure appliances] Click Export Missing Permissions.

The JSON file with required permissions will be saved to the default download location on your computer.

1. Grant the missing permissions:

* For Veeam Backup for Microsoft Azure appliance:

1. Create a custom role in Microsoft Azure using the file downloaded at step 8.

For details, see [Microsoft Docs](https://learn.microsoft.com/en-us/azure/role-based-access-control/custom-roles-portal#start-from-json).

1. Assign the created role to the Azure AD Application associated with the service account.

For details, see [Microsoft Docs](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal?tabs=current).

* [For Veeam Backup for Amazon Web Services appliance] Grant the missing permissions to the IAM role using the AWS Management Console.

For details, see [AWS Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_manage-attach-detach.html).

* [For Veeam Backup for Google Cloud appliance] Do one of the following:

* To grant all missing permissions to the account, click Grant.

You will be asked to authenticate to your Google Cloud account to confirm granting permissions.

* To run a script for granting permissions, click Download Script.

The TXT file with script will be saved to the default download location on your computer. To grant permissions to the account, run the script in Google Cloud Shell.

1. To make sure that the missing permissions have been granted successfully, click Recheck.

Viewing Account Permissions

To view details on the service account permissions:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the Veeam Backup for Public Clouds plugin tile.
4. In the menu on the left, click Accounts and navigate to Public Clouds.
5. Select the necessary account in the list.

To narrow down the list of accounts, you can apply the following filters:

* Account Name — search the list of accounts by server name.
* Platform — limit the list of accounts by platform (All, Amazon Web Services, Microsoft Azure, Google Cloud).

1. At the top of the list, click View Permissions.

Alternatively, you can right-click the necessary account and choose View Permissions.

Veeam Service Provider Console will open the Permissions window with details on permissions assigned to the account.


