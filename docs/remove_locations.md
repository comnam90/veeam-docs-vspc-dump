---
title: "Removing Locations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/remove_locations.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Removing Locations


If you no longer need a location, you can remove it. The cloud repository storage quota of the removed location will be added to the quota of the Remote location.

|  |
| --- |
| Note: |
| * You cannot remove the Remote and Hosted locations. * You cannot remove a location if this location includes managed Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE, Veeam Backup for Microsoft 365 servers or Veeam backup agents. Before you remove such location, move managed machines to a new location. For details, see [Setting Locations](set_location_quotas.md). * You cannot remove a location if this location has associated company users, except the Company Owner. Before you remove such location, modify settings of portal users to remove from the visibility scope a location you plan to remove. For details, see [Modifying Company Users](modify_users.md). |

Required Privileges

To perform the task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Removing Locations

To remove location:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary company in the list.
3. Do either of the following:

* At the top of the list, click Manage and select Locations.
* Right-click the company, choose Manage and select Locations.

* Click a link in the Locations column.

1. In the Manage Locations window, select the necessary location.
2. Click Remove.


