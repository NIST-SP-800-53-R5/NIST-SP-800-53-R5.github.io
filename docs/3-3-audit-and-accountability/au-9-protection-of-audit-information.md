---
layout: page
title: --  AU-9 PROTECTION OF AUDIT INFORMATION 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 3390 
---

## AU-9 PROTECTION OF AUDIT INFORMATION

<ins>Control</ins>:

* a. Protect audit information and audit logging tools from unauthorized access, modification, and deletion; and
* b. Alert [ _Assignment: organization-defined personnel or roles_ ] upon detection of unauthorized access, modification, or deletion of audit information.

<ins>Discussion</ins>: Audit information includes all information needed to successfully audit system activity, such as audit records, audit log settings, audit reports, and personally identifiable information. Audit logging tools are those programs and devices used to conduct system audit and logging activities. Protection of audit information focuses on technical protection and limits the ability to access and execute audit logging tools to authorized individuals. Physical protection of audit information is addressed by both media protection controls and physical and environmental protection controls.

<ins>Related Controls</ins>: AC-3, AC-6, AU-6, AU-11, AU-14, AU-15, MP-2, MP-4, PE-2, PE-3, PE-6, SA-8, SC-8, SI-4.

<ins>Control Enhancements</ins>:

* (1) PROTECTION OF AUDIT INFORMATION | HARDWARE WRITE-ONCE MEDIA<br>
**Write audit trails to hardware-enforced, write-once media.**

    <ins>Discussion</ins>: Writing audit trails to hardware-enforced, write-once media applies to the initial generation of audit trails (i.e., the collection of audit records that represents the information to be used for detection, analysis, and reporting purposes) and to the backup of those audit trails. Writing audit trails to hardware-enforced, write-once media does not apply to the initial generation of audit records prior to being written to an audit trail. Write-once, read-many (WORM) media includes Compact Disc-Recordable (CD-R), Blu-Ray Disc Recordable (BD-R), and Digital Versatile Disc-Recordable (DVD-R). In contrast, the use of switchable write-protection media, such as tape cartridges, Universal Serial Bus (USB) drives, Compact Disc Re-Writeable (CD-RW), and Digital Versatile Disc-Read Write (DVD-RW) results in write- protected but not write-once media.

    <ins>Related Controls</ins>: AU-4, AU-5.

* (2) PROTECTION OF AUDIT INFORMATION | STORE ON SEPARATE PHYSICAL SYSTEMS OR COMPONENTS<br>
**Store audit records [ _Assignment: organization-defined frequency_ ] in a repository that is part of a physically different system or system component than the system or component being audited.**

    <ins>Discussion</ins>: Storing audit records in a repository separate from the audited system or system component helps to ensure that a compromise of the system being audited does not also result in a compromise of the audit records. Storing audit records on separate physical systems or components also preserves the confidentiality and integrity of audit records and facilitates the management of audit records as an organization-wide activity. Storing audit records on separate systems or components applies to initial generation as well as backup or long-term storage of audit records.

    <ins>Related Controls</ins>: AU-4, AU-5.

* (3) PROTECTION OF AUDIT INFORMATION | CRYPTOGRAPHIC PROTECTION<br>
**Implement cryptographic mechanisms to protect the integrity of audit information and audit tools.**

    <ins>Discussion</ins>: Cryptographic mechanisms used for protecting the integrity of audit information include signed hash functions using asymmetric cryptography. This enables the distribution of the public key to verify the hash information while maintaining the confidentiality of the secret key used to generate the hash.

    <ins>Related Controls</ins>: AU-10, SC-12, SC-13.

* (4) PROTECTION OF AUDIT INFORMATION | ACCESS BY SUBSET OF PRIVILEGED USERS<br>
**Authorize access to management of audit logging functionality to only [ _Assignment: organization-defined subset of privileged users or roles_ ].**

    <ins>Discussion</ins>: Individuals or roles with privileged access to a system and who are also the subject of an audit by that system may affect the reliability of the audit information by inhibiting audit activities or modifying audit records. Requiring privileged access to be further defined between audit-related privileges and other privileges limits the number of users or roles with audit-related privileges.

    <ins>Related Controls</ins>: AC-5.

* (5) PROTECTION OF AUDIT INFORMATION | DUAL AUTHORIZATION<br>
**Enforce dual authorization for [ _Selection (one or more): movement; deletion_ ] of [ _Assignment: organization-defined audit information_ ].**

    <ins>Discussion</ins>: Organizations may choose different selection options for different types of audit information. Dual authorization mechanisms (also known as two-person control) require the approval of two authorized individuals to execute audit functions. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals. Organizations do not require dual authorization mechanisms when immediate responses are necessary to ensure public and environmental safety.

    <ins>Related Controls</ins>: AC-3.

* (6) PROTECTION OF AUDIT INFORMATION | READ-ONLY ACCESS<br>
**Authorize read-only access to audit information to [ _Assignment: organization-defined subset of privileged users or roles_ ].**

    <ins>Discussion</ins>: Restricting privileged user or role authorizations to read-only helps to limit the potential damage to organizations that could be initiated by such users or roles, such as deleting audit records to cover up malicious activity.

    <ins>Related Controls</ins>: None.

* (7) PROTECTION OF AUDIT INFORMATION | STORE ON COMPONENT WITH DIFFERENT OPERATING
SYSTEM<br>
**Store audit information on a component running a different operating system than the system or component being audited.**

    <ins>Discussion</ins>: Storing auditing information on a system component running a different operating system reduces the risk of a vulnerability specific to the system, resulting in a compromise of the audit records.

    <ins>Related controls</ins>: AU-4, AU-5, AU-11, SC-29.

<ins>References</ins>: [FIPS 140-3], [FIPS 180-4], [FIPS 202].

