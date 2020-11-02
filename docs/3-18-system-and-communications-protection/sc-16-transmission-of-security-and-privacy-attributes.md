---
layout: page
title: -- SC-16 TRANSMISSION OF SECURITY AND PRIVACY ATTRIBUTES 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318160 
---

## SC-16 TRANSMISSION OF SECURITY AND PRIVACY ATTRIBUTES

<ins>Control</ins>: Associate [ _Assignment: organization-defined security and privacy attributes_ ] with information exchanged between systems and between system components.
   
<ins>Discussion</ins>: Security and privacy attributes can be explicitly or implicitly associated with the information contained in organizational systems or system components. Attributes are abstractions that represent the basic properties or characteristics of an entity with respect to protecting information or the management of personally identifiable information. Attributes are typically associated with internal data structures, including records, buffers, and files within the system. Security and privacy attributes are used to implement access control and information flow control policies; reflect special dissemination, management, or distribution instructions, including permitted uses of personally identifiable information; or support other aspects of the information security and privacy policies. Privacy attributes may be used independently or in conjunction with security attributes.

<ins>Related Controls</ins>: AC-3 , AC-4 , AC-16.

<ins>Control Enhancements</ins>:

* (1) TRANSMISSION OF SECURITY AND PRIVACY ATTRIBUTES / INTEGRITY VERIFICATION<br>
**Verify the integrity of transmitted security and privacy attributes.**

    <ins>Discussion</ins>: Part of verifying the integrity of transmitted information is ensuring that security and privacy attributes that are associated with such information have not been modified in an unauthorized manner. Unauthorized modification of security or privacy attributes can result in a loss of integrity for transmitted information.

    <ins>Related Controls</ins>: AU-10 , SC-8.
   
* (2) TRANSMISSION OF SECURITY AND PRIVACY ATTRIBUTES / ANTI-SPOOFING MECHANISMS<br>
**Implement anti-spoofing mechanisms to prevent adversaries from falsifying the security attributes indicating the successful application of the security process.**

    <ins>Discussion</ins>: Some attack vectors operate by altering the security attributes of an information system to intentionally and maliciously implement an insufficient level of security within the system. The alteration of attributes leads organizations to believe that a greater number of security functions are in place and operational than have actually been implemented.

    <ins>Related Controls</ins>: SI-3 , SI-4 , SI-7.
   
* (3) TRANSMISSION OF SECURITY AND PRIVACY ATTRIBUTES / CRYPTOGRAPHIC BINDING<br>
**Implement [ _Assignment: organization-defined mechanisms or techniques_ ] to bind security and privacy attributes to transmitted information.**

    <ins>Discussion</ins>: Cryptographic mechanisms and techniques can provide strong security and privacy attribute binding to transmitted information to help ensure the integrity of such information.

    <ins>Related Controls</ins>: AC-16 , SC-12 , SC-13.

<ins>References</ins>: [OMB A-130 ].
