---
layout: page
title: -- SC-12 CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318120 
---

## SC-12 CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT

<ins>Control</ins>: Establish and manage cryptographic keys when cryptography is employed within the system in accordance with the following key management requirements: [ _Assignment: organization-defined requirements for key generation, distribution, storage, access, and_
_destruction_ ].

<ins>Discussion</ins>: Cryptographic key management and establishment can be performed using manual procedures or automated mechanisms with supporting manual procedures. Organizations define key management requirements in accordance with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines and specify appropriate options, parameters, and levels. Organizations manage trust stores to ensure that only approved trust anchors are part of such trust stores. This includes certificates with visibility external to organizational systems and certificates related to the internal operations of systems. [NIST CMVP] and [NIST CAVP] provide additional information on validated cryptographic modules and algorithms that can be used in cryptographic key management and establishment.

<ins>Related Controls</ins>: AC-17, AU-9, AU-10, CM-3, IA-3, IA-7, SA-4, SA-8, SA-9, SC-8, SC-11, SC-12, SC- 13, SC-17, SC-20, SC-37, SC-40, SI-3, SI-7.

<ins>Control Enhancements</ins>:
   
* (1) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / AVAILABILITY<br>
**Maintain availability of information in the event of the loss of cryptographic keys by users.**

    <ins>Discussion</ins>: Escrowing of encryption keys is a common practice for ensuring availability in the event of key loss. A forgotten passphrase is an example of losing a cryptographic key.

    <ins>Related Controls</ins>: None.
   
* (2) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / SYMMETRIC KEYS<br>
**Produce, control, and distribute symmetric cryptographic keys using [ _Selection: NIST FIPS-validated; NSA-approved_ ] key management technology and processes.**

    <ins>Discussion</ins>: [SP 800-56A], [SP 800-56B], and [SP 800-56C] provide guidance on cryptographic key establishment schemes and key derivation methods. [SP 800-57-1], [SP 800-57-2], and [SP 800-57-3] provide guidance on cryptographic key management.

    <ins>Related Controls</ins>: None.
   
* (3) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / ASYMMETRIC KEYS<br>
**Produce, control, and distribute asymmetric cryptographic keys using [ _Selection: NSA-approved key management technology and processes; prepositioned keying material; DoD-approved or DoD-issued Medium Assurance PKI certificates; DoD-approved or DoD-issued Medium Hardware Assurance PKI certificates and hardware security tokens that protect the user’s private key; certificates issued in accordance with organization-defined requirements_ ].**

    <ins>Discussion</ins>: [SP 800-56A], [SP 800-56B], and [SP 800-56C] provide guidance on cryptographic key establishment schemes and key derivation methods. [SP 800-57-1], [SP 800-57-2], and [SP 800-57-3] provide guidance on cryptographic key management.

    <ins>Related Controls</ins>: None.
   
* (4) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / PKI CERTIFICATES<br>
[Withdrawn: Incorporated into SC-12 (3).]
   
* (5) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / PKI CERTIFICATES / HARDWARE TOKENS<br>
[Withdrawn: Incorporated into SC-12 (3).]
   
* (6) CRYPTOGRAPHIC KEY ESTABLISHMENT AND MANAGEMENT / PHYSICAL CONTROL OF KEYS<br>
**Maintain physical control of cryptographic keys when stored information is encrypted by external service providers.**

    <ins>Discussion</ins>: For organizations that use external service providers (e.g., cloud service or data center providers), physical control of cryptographic keys provides additional assurance that information stored by such external providers is not subject to unauthorized disclosure or modification.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3], [SP 800-56A], [SP 800-56B], [SP 800-56C], [SP 800-57-1], [SP 800-57-2], [SP 800-57-3], [SP 800-63-3], [IR 7956], [IR 7966].
