---
title: "Certificate Validation Errors"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/appendix_errors.html"
last_updated: "11/21/2023"
product_version: "9.1.0.30636"
---

# Certificate Validation Errors


This section lists errors of security certificate validation on the Veeam Service Provider Console management agent:

* ID 600: NotTimeValid

A required certificate is not within its validity period when verifying against the current system clock or the timestamp in the signed file. Renew the expired certificate.

* ID 601: Revoked

The certificate is revoked by the Certification Authority. This could happen because the private key was compromised.

* ID 602: NotSignatureValid

The signature of the certificate cannot be verified.

* ID 603: NotValidForUsage

The certificate is not valid for the requested usage. Cannot authenticate the server with the current certificate.

* ID 604: UntrustedRoot

A certificate chain processed, but terminated in a root certificate which is not trusted by the trust provider. This could happen because your service provider is using a self-signed certificate.

* ID 605: RevocationStatusUnknown

The revocation function was unable to check revocation for the certificate. Check if you have access to a certificate revocation list distribution point. For details, see [this Digicert article](https://www.digicert.com/kb/util/utility-test-ocsp-and-crl-access-from-a-server.htm).

* ID 606: Cyclic

One of the certificates in the chain was issued by a certification authority that the original certificate had certified.

* ID 607: InvalidExtension

One of the certificates has an extension that is not valid.

* ID 608: InvalidPolicyConstraints

The certificate or one of the certificates in the certificate chain has a policy constraints extension, and one of the issued certificates has a disallowed policy mapping extension or does not have a required issuance policies extension.

* ID 609: InvalidBasicConstraints

The certificate or one of the certificates in the certificate chain has a basic constraints extension, and either the certificate cannot be used to issue other certificates, or the chain path length has been exceeded.

* ID 610: InvalidNameConstraints

The certificate or one of the certificates in the certificate chain has a name constraints extension that is not valid.

* ID 611: HasNotSupportedNameConstraint

The certificate or one of the certificates in the certificate chain has a name constraints extension that contains unsupported fields. The minimum and maximum fields are not supported. Thus minimum must always be zero and maximum must always be absent. Only UPN is supported for an Other Name. The following alternative name choices are not supported:

* X400 Address
* EDI Party Name
* Registered Id

* ID 612: HasNotDefinedNameConstraint

The certificate or one of the certificates in the certificate chain has a name constraints extension and a name constraint is missing for one of the name choices in the end certificate.

* ID 613: HasNotPermittedNameConstraint

The certificate or one of the certificates in the certificate chain has a name constraints extension, and there is not a permitted name constraint for one of the name choices in the end certificate.

* ID 614: HasExcludedNameConstraint

The certificate or one of the certificates in the certificate chain has a name constraints extension, and one of the name choices in the end certificate is explicitly excluded.

* ID 615: PartialChain

A certificate chain could not be built to a trusted root authority.

* ID 616: CtlNotTimeValid

A required certificate is not within its validity period when verifying against the current system clock or the timestamp in the signed file.

* ID 617: CtlNotSignatureValid

The signature of the certificate cannot be verified.

* ID 618: CtlNotValidForUsage

The certificate is not valid for the requested usage.

* ID 619: HasWeakSignature

A signature algorithm or public key length does not meet the system's minimum required strength.

* ID 620: OfflineRevocation

The revocation function was unable to check revocation because the revocation server was offline. Check if you have access to a certificate revocation list distribution point. For details, see [this Digicert article](https://www.digicert.com/kb/util/utility-test-ocsp-and-crl-access-from-a-server.htm).

* ID 621: NoIssuanceChainPolicy

The certificate has invalid policy.

* ID 622: ExplicitDistrust

The certificate was explicitly marked as untrusted by the user.

* ID 623: HasNotSupportedCriticalExtension

The certificate contains an unknown extension that is marked Critical.

* ID 624: RemoteCertificateNotAvailable

The certificate is damaged or inaccessible.

* ID 625: RemoteCertificateNameMismatch

FQDN in the certificate does not match server FQDN. Check that you specified the server address correctly.

* ID 626: RemoteCertificateChainErrors

An error occurred while checking certificate chain.

* ID 627: NotTimeNested

Specifies that the CA (certificate authority) certificate and the issued certificate have validity periods that are not nested. For example, the CA cert can be valid from January 1 to December 1 and the issued certificate from January 2 to December 2, which means the validity periods are not nested.


