---
title: "Revoking License Keys"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/pulse_revoke_license.html"
last_updated: "7/31/2025"
product_version: "9.1.0.30636"
---

# Revoking License Keys


You can revoke previously assigned license keys.

When you revoke a license key, the license in VCSP Pulse becomes inactive and plugin creates a license key template for the deleted license. The product from which you revoke a license key will be switched to Community edition (for Veeam Backup & Replication and Veeam ONE). Revoked Veeam Cloud Connect and Veeam Backup for Microsoft 365 license keys will not be removed from products. After you revoke a license key, you can assign the created license key template to another company or delete it.

|  |
| --- |
| Note: |
| You cannot revoke license keys with Multi-Customer Usage usage type. |

Revoking License Keys

To revoke license keys:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Catalog.
3. Click the VCSP Pulse plugin tile.
4. In the menu on the left, click License Keys.

Veeam Service Provider Console will display a list of all license keys managed in VCSP Pulse.

1. Select the necessary license keys.

To display all assigned license keys, in the Assignment Status section on the filter bar select Assigned.

1. At the top of the list, click License Actions and select Revoke.

Alternatively, you can right-click the necessary license key, choose License Actions and select Revoke.

1. In the displayed window, click Revoke to confirm the operation.


