---
title: "Configuring Single Sign-On Authentication"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/sso.html"
last_updated: "8/15/2025"
product_version: "9.1.0.30636"
---

# Configuring Single Sign-On Authentication


Veeam Service Provider Console supports single sign-on (SSO) authentication based on the [SAML 2.0 protocol](http://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html). Organizations that use a single sign-on service in their infrastructure can extend single sign-on capabilities to Veeam Service Provider Console. Once a user of the organization is logged in to the single sign-on service, the user can access Veeam Service Provider Console without the need to provide credentials.

SAML authentication scenario in Veeam Service Provider Console comprises the following parties:

* User that logs in to the Veeam Service Provider Console portal.
* Service provider (SP) — an application accessed by the user (Veeam Service Provider Console portal).
* Identity provider (IdP) — an external service (hosted on premises or in the public cloud) that facilitates SSO. The IdP keeps user identity data in a user store. Upon requests from the SP, the IdP issues SAML authentication assertions, that is, identifies the user and provides the SP with necessary information about the user.

You can enable SSO authentication for the following user roles:

* Portal Administrator
* Portal Operator
* Read-only User
* Company Owner
* Company Administrator
* Company Tenant
* Location Administrator
* Location User
* Company Invoice Auditor
* Service Provider Global Administrator
* Service Provider Administrator
* Service Provider Operator
* Service Provider User
* Service Provider Invoice Auditor

For users of companies managed by resellers, SSO authentication is configured on the reseller side.

How It Works

In Veeam Service Provider Console, SSO authentication is performed in the following way:

1. The user clicks Log in with SSO on the authorization page.
2. Veeam Service Provider Console redirects a SAML authentication request to the identity provider.
3. The identity provider redirects the user to the URL of the single sign-on webpage.
4. The user specifies the credentials of their account on the single sign-on webpage.
5. The identity provider issues a SAML assertion and redirects it to Veeam Service Provider Console in the SAML response. The SAML assertion contains an organization name and a user email address.
6. Veeam Service Provider Console assigns or creates a user identity according to an applicable mapping rule.
7. The user gains access to the website.

|  |
| --- |
| Important! |
| If you have configured SSO authorization, enabled multi-factor authentication will be ignored when the user logs in with SSO.  Note that Veeam Service Provider Console supports only HTTP Redirect Binding. |

Configuring SSO

You can configure SSO authentication for the Administrator Portal users and users of managed companies. To do that, you must perform the following operations:

1. [Add identity provider](sso_idp.md#add_idp)
2. [Configure mapping rules](sso_rules.md#create_rule)


