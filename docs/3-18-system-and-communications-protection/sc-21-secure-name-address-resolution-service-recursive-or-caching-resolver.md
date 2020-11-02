---
layout: page
title: -- SC-21 SECURE NAME/ADDRESS RESOLUTION SERVICE (RECURSIVE OR CACHING RESOLVER) 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318210 
---

## SC-21 SECURE NAME/ADDRESS RESOLUTION SERVICE (RECURSIVE OR CACHING RESOLVER)

<ins>Control</ins>: Request and perform data origin authentication and data integrity verification on the name/address resolution responses the system receives from authoritative sources.

<ins>Discussion</ins>: Each client of name resolution services either performs this validation on its own or has authenticated channels to trusted validation providers. Systems that provide name and address resolution services for local clients include recursive resolving or caching domain name system (DNS) servers. DNS client resolvers either perform validation of DNSSEC signatures, or clients use authenticated channels to recursive resolvers that perform such validations. Systems that use technologies other than the DNS to map between host and service names and network addresses provide some other means to enable clients to verify the authenticity and integrity of response data.
   
<ins>Related Controls</ins>: SC-20 , SC-22.

<ins>Control Enhancements</ins>: None.
   
* (1) SECURE NAME/ADDRESS RESOLUTION SERVICE (RECURSIVE OR CACHING RESOLVER) / DATA ORIGIN AND INTEGRITY<br>
[Withdrawn: Incorporated into SC-21 .]

<ins>References</ins>: [SP 800-81-2].
