---
title: "Resetting Veeam ONE Installation ID"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/one_reset_id.html"
last_updated: "12/11/2025"
product_version: "9.1.0.30636"
---

# Resetting Veeam ONE Installation ID


In Veeam Service Provider Console, you can reset installation IDs for managed Veeam ONE servers. Resetting installation IDs may be required if you cloned several Veeam ONE servers from one deployment. Cloned Veeam ONE servers have the same installation IDs, which affects license usage statistics and reporting.

Resetting Veeam ONE Installation ID

To reset installation ID of managed Veeam ONE servers:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Discovery.
2. Open the ONE Servers tab.
3. Select the necessary Veeam ONE servers in the list.
4. At the top of the list, click Regenerate Installation ID.

Alternatively, you can right-click the necessary server and choose Regenerate Installation ID.

1. In the Regenerate Installation ID window, click Yes.

Veeam Service Provider Console will generate a unique installation IDs and reboot the computer on which the Veeam ONE server is installed.


