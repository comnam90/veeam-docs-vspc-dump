---
title: "Modifying Locations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/modify_locations.html"
last_updated: "4/15/2024"
product_version: "9.1.0.30636"
---

# Modifying Locations


You can modify created company locations to differentiate backup services and cloud resources consumed by offices or business units in your client companies.

Required Privileges

To perform the task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Modifying Location Settings

You can modify settings of previously created locations:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary company in the list.
3. Do either of the following:

* At the top of the list, click Manage and select Locations.
* Right-click the company, choose Manage and select Locations.
* Click a link in the Locations column.

1. In the Manage Locations window, select the necessary location.
2. Click Edit.
3. Modify location settings as described in [Creating Locations](create_locations.md).
4. Click OK.

|  |
| --- |
| Note: |
| If you change the cloud repository storage quota, the quota of the Remote location will be updated as well. If the cloud repository storage quota is increased, the quota of the Remote location will be decreased by the same amount, and if the cloud repository storage quota is decreased, the quota of the Remote location will be increased. |


