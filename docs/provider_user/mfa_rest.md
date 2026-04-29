---
title: "Enabling and Disabling MFA using REST API"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/mfa_rest.html"
last_updated: "4/27/2026"
product_version: "9.2.0.33215"
---

# Enabling and Disabling MFA using REST API


You can enable or disable MFA using Veeam Service Provider Console REST API. For details on REST API in Veeam Service Provider Console, see [REST API Reference](https://helpcenter.veeam.com/docs/vac/rest/about_rest.html).

To access Veeam Service Provider Console REST API, you can use any client application. This guide covers procedures performed in Swagger UI, a built-in tool for evaluation and testing.

Before You Begin

To configure MFA for a user, you must install an authenticator application or any other TOTP code generator.

Enabling MFA

To enable MFA for a user account using Swagger UI:

1. In the internet browser address bar, enter the Veeam Service Provider Console REST API URL in the following format: https://<hostname>:<port>/api.
2. On the landing page, click SwaggerUI.
3. Authorize as described in section [Getting Authorization Tokens](https://helpcenter.veeam.com/references/vac/9.2/rest/tag/SectionOverview#section/Evaluation-with-Swagger-UI/Getting-Authorization-Tokens) of the REST API Reference.
4. Under the Accounts collection, expand the GET /users resource and click Try it out.
5. In the filter parameter field, type the following: [{"property":"userName","operation":"equals","value":"<User name>"}], where <User name> is the name of a user for whom you want to enable MFA.
6. Click Execute.

The server will return a response which you can find in the Response body section. The response contains resource representation of a user.

1. Under the Accounts collection, expand the PATCH /users/{userUid} resource and click Try it out.
2. In the Parameters section, specify the following parameters:

* userUid — user UID that you received as the instanceUID property value at step 6.
* body — the following JSON Patch operation:

|  |
| --- |
| [   {     "op": "replace",     "path": "mfaPolicyStatus",     "value": "enabled",   }  ] |

1. Click Execute.

If the request is processed successfully, the server will return a response with the 200 OK response code.

On the next authorization session, the user must configure MFA on the Multi-Factor Authentication step of the Edit User wizard as described in the [Modifying User Profile](modify_user_profile.md) section.

Disabling MFA

To allow users to disable MFA for their account using Swagger UI:

1. In the internet browser address bar, enter the Veeam Service Provider Console REST API URL in the following format: https://<hostname>:<port>/api.
2. On the landing page, click SwaggerUI.
3. Authorize as described in section [Getting Authorization Tokens](https://helpcenter.veeam.com/docs/vac/rest/authorization_example_v3.html) of the REST API Reference.
4. Under the Accounts collection, expand the GET /users resource and click Try it out.
5. In the filter parameter field, type the following: [{"property":"userName","operation":"equals","value":"<User name>"}], where <User name> is the name of a user for whom you want to disable MFA.
6. Click Execute.

The server will return a response which you can find in the Response body section. The response contains resource representation of a user.

1. Under the Accounts collection, expand the PATCH /users/{userUid} resource and click Try it out.
2. In the Parameters section, specify the following parameters:

* userUid — user UID that you received as the instanceUID property value at step 6.
* body — the following JSON Patch operation:

|  |
| --- |
| [   {     "op": "replace",     "path": "mfaPolicyStatus",     "value": "disabled",   }  ] |

1. Click Execute.

If the request is processed successfully, the server will return a response with the 200 OK response code.

On the next authorization session, the user can disable MFA on the Multi-Factor Authentication step of the Edit User wizard or create a new MFA access configuration as described in the [Modifying User Profile](modify_user_profile.md) section.

|  |
| --- |
| Tip: |
| You can also perform this operation to reset user MFA access. |

|  |
| --- |
| Note: |
| Allowing a single user to disable MFA does not cancel policy or organization settings that enforce MFA for this user. |


