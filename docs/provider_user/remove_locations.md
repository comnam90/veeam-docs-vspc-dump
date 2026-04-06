---
title: "Removing Locations"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/remove_locations.html"
last_updated: "10/25/2024"
product_version: "9.1.0.30636"
---

# Removing Locations


If you no longer need a location, you can remove it. The cloud repository storage quota of the removed location will be added to the quota of the Remote location.

|  |
| --- |
| Note: |
| * You cannot remove the Remote and Hosted locations. * You cannot remove a location if this location includes managed Veeam Backup & Replication, Veeam Backup Enterprise Manager, Veeam ONE, Veeam Backup for Microsoft 365 servers or Veeam backup agents. Before you remove such a location, move managed machines to a new location. For details, see [Setting Locations](set_location_quotas.md). * You cannot remove a location if this location has associated portal users, except the Company Owner. Before you remove such a location, modify settings of portal users to remove from the visibility scope a location you plan to remove. For details, see [Modifying Portal Users](modify_users.md). |

Required Privileges

To perform the task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

Removing Locations

To remove a location:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Locations.
3. Select the necessary location in the list.
4. At the top of the location list, click Remove.

Alternatively, you can right-click the necessary location and choose Remove.


