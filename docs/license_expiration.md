---
title: "License Expiration"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/license_expiration.html"
last_updated: "1/4/2024"
product_version: "9.1.0.30636"
---

# License Expiration


Veeam Service Provider Console license period is set in accordance with the chosen licensing program. When this period is over, you must update the license.

To ensure a smooth license update and provide sufficient time to install a new license file, Veeam Service Provider Console offers a grace period after the license expiration date. During the grace period, Veeam Service Provider Console keeps working in a full-version mode. The license status during this period appears as Expired (<number> days of grace period remaining).

The duration of the grace period depends on the license type:

License Expiration

| License Type | Grace Period |
| Rental | 60 days |
| Subscription | 30 days |
| NFR | 30 days |
| Evaluation | No grace period |

You must update the license before the end of the grace period. If you do not update the license, after the grace period access to Veeam Service Provider Console will be disabled for all types of portal users.

For details on Veeam Service Provider Console license update, see [Updating Veeam Service Provider Console License](update_vac_license.md).


