---
title: "Creating Locations"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/create_locations.html"
last_updated: "7/7/2025"
product_version: "9.1.0.30636"
---

# Creating Locations


You can create new company locations to differentiate backup services and cloud resources consumed by offices or business units in your client companies.

Required Privileges

To perform the task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator.

Creating Locations

To create a new company location:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Companies.
2. Select the necessary company in the list.
3. Do either of the following:

* At the top of the list, click Manage and select Locations.
* Right-click the company, choose Manage and select Locations.
* Click a link in the Locations column.

1. In the Manage Locations window, click Add.
2. In the Add Location window, specify the following settings:

1. In the Name field, specify a location name.
2. In the Cloud repository storage quota field, specify the maximum amount of cloud repository space that must be available for this location. This amount cannot be greater that the total cloud repository storage quota for the company.

The specified cloud repository storage quota is used as a threshold for the Summary dashboard and for the Company cloud storage quota alarm. It does not limit the actual amount of data that can be uploaded from the location to cloud repositories.

1. Click OK.

[![Create Location](images/create_location.webp)](images/create_location.webp "Create Location")

When you create a new location, the cloud repository storage quota of the Remote location is decreased by the amount of the cloud repository storage quota set for the new location.

What to Do Next

After you create new locations, you can define what machines and what users will be associated with the new location. For details, see [Setting Locations](set_location_quotas.md).


