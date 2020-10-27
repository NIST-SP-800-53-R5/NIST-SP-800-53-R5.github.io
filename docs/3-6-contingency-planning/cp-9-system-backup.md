---
layout: page
title: -- CP-9 SYSTEM BACKUP 
parent: . 3.6 CONTINGENCY PLANNING 
nav_order: 3690 
---

## CP-9 SYSTEM BACKUP

<ins>Control</ins>:

* a. Conduct backups of user-level information contained in [ _Assignment: organization-defined system components_ ] [ _Assignment: organization-defined frequency consistent with recovery time and recovery point objectives_ ];
* b. Conduct backups of system-level information contained in the system [ _Assignment: organization-defined frequency consistent with recovery time and recovery point objectives_ ];
* c. Conduct backups of system documentation, including security- and privacy-related documentation [ _Assignment: organization-defined frequency consistent with recovery time and recovery point objectives_ ]; and
* d. Protect the confidentiality, integrity, and availability of backup information.

<ins>Discussion</ins>: System-level information includes system state information, operating system software, middleware, application software, and licenses. User-level information includes information other than system-level information. Mechanisms employed to protect the integrity of system backups include digital signatures and cryptographic hashes. Protection of system backup information while in transit is addressed by MP-5 and SC-8. System backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information. Organizations may be subject to laws, executive orders, directives, regulations, or policies with requirements regarding specific categories of information (e.g., personal health information). Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such requirements.

<ins>Related Controls</ins>: CP-2, CP-6, CP-10, MP-4, MP-5, SC-8, SC-12, SC-13, SI-4, SI-13.

<ins>Control Enhancements</ins>:

* (1) SYSTEM BACKUP / TESTING FOR RELIABILITY AND INTEGRITY<br>
**Test backup information [ _Assignment: organization-defined frequency_ ] to verify media reliability and information integrity.**

    <ins>Discussion</ins>: Organizations need assurance that backup information can be reliably retrieved. Reliability pertains to the systems and system components where the backup information is stored, the operations used to retrieve the information, and the integrity of the information being retrieved. Independent and specialized tests can be used for each of the aspects of reliability. For example, decrypting and transporting (or transmitting) a random sample of backup files from the alternate storage or backup site and comparing the information to the same information at the primary processing site can provide such assurance.

    <ins>Related Controls</ins>: CP-4.

* (2) SYSTEM BACKUP / TEST RESTORATION USING SAMPLING<br>
**Use a sample of backup information in the restoration of selected system functions as part of contingency plan testing.**

    <ins>Discussion</ins>: Organizations need assurance that system functions can be restored correctly and can support established organizational missions. To ensure that the selected system functions are thoroughly exercised during contingency plan testing, a sample of backup information is retrieved to determine whether the functions are operating as intended. Organizations can determine the sample size for the functions and backup information based on the level of assurance needed.

    <ins>Related Controls</ins>: CP-4.

* (3) SYSTEM BACKUP / SEPARATE STORAGE FOR CRITICAL INFORMATION<br>
**Store backup copies of [ _Assignment: organization-defined critical system software and other security-related information_ ] in a separate facility or in a fire rated container that is not collocated with the operational system.**

    <ins>Discussion</ins>: Separate storage for critical information applies to all critical information regardless of the type of backup storage media. Critical system software includes operating systems, middleware, cryptographic key management systems, and intrusion detection systems. Security-related information includes inventories of system hardware, software, and firmware components. Alternate storage sites, including geographically distributed architectures, serve as separate storage facilities for organizations. Organizations may
provide separate storage by implementing automated backup processes at alternative storage sites (e.g., data centers). The General Services Administration (GSA) establishes standards and specifications for security and fire rated containers.

    <ins>Related Controls</ins>: CM-2, CM-6, CM-8.

* (4) SYSTEM BACKUP / PROTECTION FROM UNAUTHORIZED MODIFICATION<br>
[Withdrawn: Incorporated into CP-9.]

* (5) SYSTEM BACKUP / TRANSFER TO ALTERNATE STORAGE SITE<br>
**Transfer system backup information to the alternate storage site [ _Assignment: organization-defined time period and transfer rate consistent with the recovery time and recovery point objectives_ ].**

    <ins>Discussion</ins>: System backup information can be transferred to alternate storage sites either electronically or by the physical shipment of storage media.

    <ins>Related Controls</ins>: CP-7, MP-3, MP-4, MP-5.

* (6) SYSTEM BACKUP / REDUNDANT SECONDARY SYSTEM<br>
**Conduct system backup by maintaining a redundant secondary system that is not collocated with the primary system and that can be activated without loss of information or disruption to operations.**

    <ins>Discussion</ins>: The effect of system backup can be achieved by maintaining a redundant secondary system that mirrors the primary system, including the replication of information. If this type of redundancy is in place and there is sufficient geographic separation between the two systems, the secondary system can also serve as the alternate processing site.

    <ins>Related Controls</ins>: CP-7.

* (7) SYSTEM BACKUP / DUAL AUTHORIZATION<br>
**Enforce dual authorization for the deletion or destruction of [ _Assignment: organization-defined backup information_ ].**

    <ins>Discussion</ins>: Dual authorization ensures that deletion or destruction of backup information cannot occur unless two qualified individuals carry out the task. Individuals deleting or destroying backup information possess the skills or expertise to determine if the proposed deletion or destruction of information reflects organizational policies and procedures. Dual authorization may also be known as two-person control. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals.

    <ins>Related Controls</ins>: AC-3, AC-5, MP-2.

* (8) SYSTEM BACKUP / CRYPTOGRAPHIC PROTECTION<br>
**Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of [ _Assignment: organization-defined backup information_ ].**

    <ins>Discussion</ins>: The selection of cryptographic mechanisms is based on the need to protect the confidentiality and integrity of backup information. The strength of mechanisms selected is commensurate with the security category or classification of the information. Cryptographic protection applies to system backup information in storage at both primary and alternate locations. Organizations that implement cryptographic mechanisms to protect information at rest also consider cryptographic key management solutions.

    <ins>Related Controls</ins>: SC-12, SC-13, SC-28.

<ins>References</ins>: [FIPS 140-3], [FIPS 186-4], [SP 800-34], [SP 800-130], [SP 800-152].
