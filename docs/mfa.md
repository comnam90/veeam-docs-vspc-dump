---
title: "Configuring Multi-Factor Authentication"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/mfa.html"
last_updated: "8/25/2025"
product_version: "9.1.0.30636"
---

# Configuring Multi-Factor Authentication


You can configure multi-factor authentication (MFA) for additional security of user accounts. In Veeam Service Provider Console, this authentication method is based on the [TOTP algorithm](https://tools.ietf.org/html/rfc6238) and requires the installation of an authenticator application on a trusted device, for example, smartphone. Veeam Service Provider Console supports all applications that use TOTP mechanism, however we recommend [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2).

|  |
| --- |
| Important! |
| If you configure MFA for an account that is used for integration with 3rd party applications, that integration will stop working. To avoid that, first configure an API key, as described in the [Configuring API Keys](api_keys.md) section.  Time difference between the trusted device and the machine on which the Veeam Service Provider Console Web UI component is installed must not be more than one minute. |

To enable and disable MFA for your own account, modify your user profile as described in the [Filling User Profile](fill_user_profile.md#mfa_config) section.

A user with Portal Administrator role can enable MFA for other Administrator Portal users.


