---
layout: page
title: --  AU-16 CROSS-ORGANIZATIONAL AUDIT LOGGING 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 33160 
---

## AU-16 CROSS-ORGANIZATIONAL AUDIT LOGGING

<ins>Control</ins>: Employ [ _Assignment: organization-defined methods_ ] for coordinating [ _Assignment: organization-defined audit information_ ] among external organizations when audit information is transmitted across organizational boundaries.

<ins>Discussion<ins>: When organizations use systems or services of external organizations, the audit logging capability necessitates a coordinated, cross-organization approach. For example, maintaining the identity of individuals who request specific services across organizational boundaries may often be difficult, and doing so may prove to have significant performance and privacy ramifications. Therefore, it is often the case that cross-organizational audit logging simply captures the identity of individuals who issue requests at the initial system, and subsequent systems record that the requests originated from authorized individuals. Organizations consider including processes for coordinating audit information requirements and protection of audit information in information exchange agreements.

<ins>Related Controls</ins>: AU-3, AU-6, AU-7, CA-3, PT-7.

<ins>Control Enhancements</ins>:

* (1) CROSS-ORGANIZATIONAL AUDIT LOGGING | IDENTITY PRESERVATION<br>
**Preserve the identity of individuals in cross-organizational audit trails.**

    <ins>Discussion</ins>: Identity preservation is applied when there is a need to be able to trace actions that are performed across organizational boundaries to a specific individual.

    <ins>Related Controls</ins>: IA-2, IA -4, IA -5, IA -8.

* (2) CROSS-ORGANIZATIONAL AUDIT LOGGING | SHARING OF AUDIT INFORMATION<br>
**Provide cross-organizational audit information to [ _Assignment: organization-defined organizations_ ] based on [ _Assignment: organization-defined cross-organizational sharing agreements_ ].**

    <ins>Discussion</ins>: Due to the distributed nature of the audit information, cross-organization sharing of audit information may be essential for effective analysis of the auditing being performed. For example, the audit records of one organization may not provide sufficient information to determine the appropriate or inappropriate use of organizational information resources by individuals in other organizations. In some instances, only individuals’ home organizations have the appropriate knowledge to make such determinations, thus requiring the sharing of audit information among organizations.

    <ins>Related Controls</ins>: IR-4, SI-4.

* (3) CROSS-ORGANIZATIONAL AUDITING | DISASSOCIABILITY<br>
**Implement [ _Assignment: organization-defined measures_ ] to disassociate individuals from audit information transmitted across organizational boundaries.**

    <ins>Discussion<ins>: Preserving identities in audit trails could have privacy ramifications, such as enabling the tracking and profiling of individuals, but may not be operationally necessary. These risks could be further amplified when transmitting information across organizational boundaries. Implementing privacy-enhancing cryptographic techniques can disassociate individuals from audit information and reduce privacy risk while maintaining accountability.

    <ins>Related Controls<ins>: None.

<ins>References<ins>: None.


