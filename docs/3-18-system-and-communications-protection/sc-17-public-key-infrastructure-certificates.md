---
layout: page
title: -- SC-17 PUBLIC KEY INFRASTRUCTURE CERTIFICATES 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318170 
---

## SC-17 PUBLIC KEY INFRASTRUCTURE CERTIFICATES

<ins>Control</ins>:
   
* a. Issue public key certificates under an [ _Assignment: organization-defined certificate policy_ ] or obtain public key certificates from an approved service provider; and
* b. Include only approved trust anchors in trust stores or certificate stores managed by the organization.

<ins>Discussion</ins>: Public key infrastructure certificates are certificates with visibility external to organizational systems and certificates related to the internal operations of systems, such as application-specific time services. In cryptographic systems with a hierarchical structure, a trust anchor is an authoritative source (i.e., a certificate authority) for which trust is assumed and not derived. A root certificate for a PKI system is an example of a trust anchor. A trust store or certificate store maintains a list of trusted root certificates.
   
<ins>Related Controls</ins>: AU-10 , IA-5 , SC-12.

<ins>Control Enhancements</ins>: None.

<ins>References</ins>: [SP 800-32], [SP 800-57-1], [SP 800-57-2], [SP 800-57-3], [SP 800-63-3].
   
