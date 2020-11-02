---
layout: page
title: -- SC-20 SECURE NAME/ADDRESS RESOLUTION SERVICE (AUTHORITATIVE SOURCE) 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318200 
---

## SC-20 SECURE NAME/ADDRESS RESOLUTION SERVICE (AUTHORITATIVE SOURCE)

<ins>Control</ins>:

* a. Provide additional data origin authentication and integrity verification artifacts along with the authoritative name resolution data the system returns in response to external name/address resolution queries; and
* b. Provide the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.

<ins>Discussion</ins>: Providing authoritative source information enables external clients, including remote Internet clients, to obtain origin authentication and integrity verification assurances for the host/service name to network address resolution information obtained through the service. Systems that provide name and address resolution services include domain name system (DNS) servers. Additional artifacts include DNS Security Extensions (DNSSEC) digital signatures and cryptographic keys. Authoritative data includes DNS resource records. The means for indicating the security status of child zones include the use of delegation signer resource records in the DNS. Systems that use technologies other than the DNS to map between host and service names and network addresses provide other means to assure the authenticity and integrity of response data.

<ins>Related Controls</ins>: AU-10 , SC-8 , SC-12 , SC-13 , SC-21 , SC-22.

<ins>Control Enhancements</ins>:
   
* (1) SECURE NAME/ADDRESS RESOLUTION SERVICE (AUTHORITATIVE SOURCE) / CHILD SUBSPACES<br>
[Withdrawn: Incorporated into SC-20 .]
   
* (2) SECURE NAME/ADDRESS RESOLUTION SERVICE (AUTHORITATIVE SOURCE) / DATA ORIGIN AND INTEGRITY<br>
**Provide data origin and integrity protection artifacts for internal name/address resolution queries.**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3], [FIPS 186-4], [SP 800-81-2].
