---
layout: page
title: -- SC-28 PROTECTION OF INFORMATION AT REST 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318280 
---

## SC-28 PROTECTION OF INFORMATION AT REST

<ins>Control</ins>: Protect the [ _Selection (one or more): confidentiality; integrity_ ] of the following information at rest: [ _Assignment: organization-defined information at rest_ ].

<ins>Discussion</ins>: Information at rest refers to the state of information when it is not in process or in transit and is located on system components. Such components include internal or external hard disk drives, storage area network devices, or databases. However, the focus of protecting information at rest is not on the type of storage device or frequency of access but rather on the state of the information. Information at rest addresses the confidentiality and integrity of information and covers user information and system information. System-related information that requires protection includes configurations or rule sets for firewalls, intrusion detection and prevention systems, filtering routers, and authentication information. Organizations may employ different mechanisms to achieve confidentiality and integrity protections, including the use of cryptographic mechanisms and file share scanning. Integrity protection can be achieved, for example, by implementing write-once-read-many (WORM) technologies. When adequate protection of information at rest cannot otherwise be achieved, organizations may employ other controls, including frequent scanning to identify malicious code at rest and secure offline storage in lieu of online storage.

<ins>Related Controls</ins>: AC-3 , AC-4 , AC-6 , AC-19 , CA-7 , CM-3 , CM-5 , CM-6 , CP-9 , MP-4 , MP-5 , PE-3 , SC-8 , SC-12 , SC-13 , SC-34 , SI-3 , SI-7 , SI-16.

<ins>Control Enhancements</ins>:
   
* (1) PROTECTION OF INFORMATION AT REST / CRYPTOGRAPHIC PROTECTION<br>
**Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of the following information at rest on [ _Assignment: organization-defined system components or media_ ]: [ _Assignment: organization-defined information_ ].**

    <ins>Discussion</ins>: The selection of cryptographic mechanisms is based on the need to protect the confidentiality and integrity of organizational information. The strength of mechanism is commensurate with the security category or classification of the information. Organizations have the flexibility to encrypt information on system components or media or encrypt data structures, including files, records, or fields.
   
    <ins>Related Controls</ins>: AC-19 , SC-12 , SC-13.

* (2) PROTECTION OF INFORMATION AT REST / OFFLINE STORAGE<br>
**Remove the following information from online storage and store offline in a secure location: [ _Assignment: organization-defined information_ ].**

    <ins>Discussion</ins>: Removing organizational information from online storage to offline storage eliminates the possibility of individuals gaining unauthorized access to the information through a network. Therefore, organizations may choose to move information to offline storage in lieu of protecting such information in online storage.

    <ins>Related Controls</ins>: None.
   
* (3) PROTECTION OF INFORMATION AT REST / CRYPTOGRAPHIC KEYS<br>
**Provide protected storage for cryptographic keys [ _Selection: [ Assignment: organization-defined safeguards ]; hardware-protected key store_ ].**

    <ins>Discussion</ins>: A Trusted Platform Module (TPM) is an example of a hardware-protected data store that can be used to protect cryptographic keys.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
   
<ins>References</ins>: [OMB A-130], [SP 800-56A], [SP 800-56B], [SP 800-56C], [SP 800-57-1], [SP 800-57-2 ], [SP 800-57-3], [SP 800-111], [SP 800-124].
