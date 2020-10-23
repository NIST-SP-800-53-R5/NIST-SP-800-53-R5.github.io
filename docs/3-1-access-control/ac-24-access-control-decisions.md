---
layout: default
title:  -- AC-24 ACCESS CONTROL DECISIONS 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15240
---

## AC-24 ACCESS CONTROL DECISIONS

<ins>Control</ins>: [ _Selection: Establish procedures; Implement mechanisms_ ] to ensure [ _Assignment: organization-defined access control decisions_ ] are applied to each access request prior to access enforcement.

<ins>Discussion</ins>: Access control decisions (also known as authorization decisions) occur when authorization information is applied to specific accesses. In contrast, access enforcement occurs when systems enforce access control decisions. While it is common to have access control decisions and access enforcement implemented by the same entity, it is not required, and it is not always an optimal implementation choice. For some architectures and distributed systems, different entities may make access control decisions and enforce access.

<ins>Related Controls</ins>: AC-2, AC-3.

<ins>Control Enhancements</ins>:
* (1) ACCESS CONTROL DECISIONS / TRANSMIT ACCESS AUTHORIZATION INFORMATION<br>
**Transmit [ _Assignment: organization-defined access authorization information_ ] using [ _Assignment: organization-defined controls_ ] to [ _Assignment: organization-defined systems_ ] that enforce access control decisions.**

    <ins>Discussion</ins>: Authorization processes and access control decisions may occur in separate parts of systems or in separate systems. In such instances, authorization information is transmitted securely (e.g., using cryptographic mechanisms) so that timely access control decisions can be enforced at the appropriate locations. To support the access control decisions, it may be necessary to transmit as part of the access authorization information supporting security and privacy attributes. This is because in distributed systems, there are various access control decisions that need to be made, and different entities make these decisions in a serial fashion, each requiring those attributes to make the decisions. Protecting access authorization information ensures that such information cannot be altered, spoofed, or compromised during transmission.

    <ins>Related Controls</ins>: AU-10.

* (2) ACCESS CONTROL DECISIONS / NO USER OR PROCESS IDENTITY<br>
**Enforce access control decisions based on [ Assignment: organization-defined security or privacy attributes ] that do not include the identity of the user or process acting on behalf of the user.**

    <ins>Discussion</ins>: In certain situations, it is important that access control decisions can be made without information regarding the identity of the users issuing the requests. These are generally instances where preserving individual privacy is of paramount importance. In other situations, user identification information is simply not needed for access control decisions, and especially in the case of distributed systems, transmitting such information with the needed degree of assurance may be very expensive or difficult to accomplish. MAC, RBAC, ABAC, and label-based control policies, for example, might not include user identity as an attribute.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [SP 800-162], [SP 800-178].
