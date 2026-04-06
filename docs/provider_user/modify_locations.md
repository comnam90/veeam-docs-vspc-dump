---
title: "Modifying Locations"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/modify_locations.html"
last_updated: "7/4/2024"
product_version: "9.1.0.30636"
---

# Modifying Locations


You can modify settings of previously created locations.

Required Privileges

To perform the task, a user must have one of the following roles assigned: Company Owner, Company Administrator.

Modifying Location Settings

To modify location settings:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Locations.
3. Select the necessary location in the list.
4. At the top of the location list, click Edit.

Alternatively, you can right-click the necessary location and choose Edit.

1. Modify location settings as described in [Creating Locations](create_locations.md).
2. Click OK.

|  |
| --- |
| Note: |
| * You cannot change cloud repository storage quota for the Remote location. Quota for this location is managed by Veeam Service Provider Console. * If you change the cloud repository storage quota, the quota of the Remote location will be updated as well. If the cloud repository storage quota is increased, the quota of the Remote location will be decreased by the increase amount, and if the cloud repository storage quota is decreased, the quota of the Remote location will be increased. |


