---
title: "Setting Locations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/set_location_quotas.html"
last_updated: "10/27/2025"
product_version: "9.1.0.30636"
---

# Setting Locations


You can set locations for client machines running Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE, Veeam Backup for Microsoft 365 and Veeam backup agents. By default, all client Veeam backup agents, Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE and Veeam Backup for Microsoft 365 servers reside in the Remote location. By setting a new location, you 'move' a managed machine to a new logical group. Note that you cannot set location for hosted machines and you cannot move client machines to the Hosted location.

You can also set locations for company users to control the scope of data that must be available to these users in the Veeam Service Provider Console Client Portal. A user working with the Client Portal can only work with details of managed machines that are included in the scope of a location, or locations, to which this user is subscribed.

Required Privileges

To perform the task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Setting Locations for Veeam Backup & Replication Servers

To set a location for one or more Veeam Backup & Replication or Veeam Backup Enterprise Manager servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Servers tab.
3. Select the necessary backup servers in the list.
4. At the top of the list, click Server Actions and select Set Location.

Alternatively, you can right-click the necessary backup server, choose Server Actions and select Set Location.

1. In the Set Location window, choose a location to which selected backup servers must be moved.
2. Click OK.

Veeam Service Provider Console will display a message notifying that the location was successfully set to the selected server. Click OK to close the window.

Setting Locations for Client Computers

To set a location for one or more managed client computers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Discovered Computers tab and navigate to Computers.
3. Select the necessary computers in the list.
4. At the top of the list, click Management Agent and select Set Location.

Alternatively, you can right-click the necessary computer, choose Management Agent and select Set Location.

1. In the Set Location window, choose a location to which selected computers must be moved.
2. Click OK.

Veeam Service Provider Console will display a message notifying that the location was successfully set to the selected computer. Click OK to close the window.

Setting Locations for Client Veeam Backup Agents

To set a location for one or more managed client Veeam backup agents:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the Backup Agents tab.
3. Select the necessary agents in the list.
4. At the top of the list, click Backup Agent and select Set Location.

Alternatively, you can right-click the necessary backup agent, choose Backup Agent and select Set Location.

1. In the Set Location window, choose a location to which selected Veeam backup agents must be moved.
2. Click OK.

Veeam Service Provider Console will display a message notifying that the location was successfully set to the selected Veeam backup agent. Click OK to close the window.

Setting Locations for Company Users

To restrict the scope of data that must be available to company users in Veeam Service Provider Console, you can choose locations for these users. You can set locations for Location Administrators and Location Users.

To set a location for one or more company users:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Roles & Users.
3. [For Portal Administrator, Site Administrator] Open the Managed Companies tab and navigate to Local Users.
4. Select the necessary company user in the list and click Edit.

Alternatively, you can right-click the necessary company user and choose Edit.

Veeam Service Provider Console will launch the Edit User wizard.

1. At the Locations step of the wizard, choose a location to which the selected user must have access. Click Apply.
2. Click Finish.


