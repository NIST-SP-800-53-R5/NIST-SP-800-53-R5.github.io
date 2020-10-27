---
layout: page
title: -- CM-5 ACCESS RESTRICTIONS FOR CHANGE 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3550 
---

## CM-5 ACCESS RESTRICTIONS FOR CHANGE

<ins>Control</ins>: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the system.

<ins>Discussion</ins>: Changes to the hardware, software, or firmware components of systems or the operational procedures related to the system can potentially have significant effects on the security of the systems or individuals’ privacy. Therefore, organizations permit only qualified and authorized individuals to access systems for purposes of initiating changes. Access restrictions include physical and logical access controls (see AC-3 and PE-3), software libraries, workflow automation, media libraries, abstract layers (i.e., changes implemented into external interfaces rather than directly into systems), and change windows (i.e., changes occur only during specified times).

<ins>Related Controls</ins>: AC-3, AC-5, AC-6, CM-9, PE-3, SC-28, SC-34, SC-37, SI-2, SI-10.

<ins>Control Enhancements</ins>:

* (1) ACCESS RESTRICTIONS FOR CHANGE / AUTOMATED ACCESS ENFORCEMENT AND AUDIT RECORDS<br>
    * **(a) Enforce access restrictions using [ _Assignment: organization-defined automated mechanisms_ ]; and**
    * **(b) Automatically generate audit records of the enforcement actions.**

    <ins>Discussion</ins>: Organizations log system accesses associated with applying configuration changes to ensure that configuration change control is implemented and to support after- the-fact actions should organizations discover any unauthorized changes.

    <ins>Related Controls</ins>: AU-2, AU-6, AU-7, AU-12, CM-6, CM-11, SI-12.

* (2) ACCESS RESTRICTIONS FOR CHANGE / REVIEW SYSTEM CHANGES<br>
[Withdrawn: Incorporated into CM-3(7).]

* (3) ACCESS RESTRICTIONS FOR CHANGE / SIGNED COMPONENTS<br>
[Withdrawn: Moved to CM-14.]

* (4) ACCESS RESTRICTIONS FOR CHANGE / DUAL AUTHORIZATION<br>
**Enforce dual authorization for implementing changes to [ _Assignment: organization-defined system components and system-level information_ ].**

    <ins>Discussion</ins>: Organizations employ dual authorization to help ensure that any changes to selected system components and information cannot occur unless two qualified individuals approve and implement such changes. The two individuals possess the skills and expertise to determine if the proposed changes are correct implementations of approved changes. The individuals are also accountable for the changes. Dual authorization may also be known as two-person control. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals. System-level information includes operational procedures.

    <ins>Related Controls</ins>: AC-2, AC-5, CM-3.

* (5) ACCESS RESTRICTIONS FOR CHANGE / PRIVILEGE LIMITATION FOR PRODUCTION AND OPERATION<br>
    * **(a) Limit privileges to change system components and system-related information within a production or operational environment; and**
    * **(b) Review and reevaluate privileges [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: In many organizations, systems support multiple mission and business functions. Limiting privileges to change system components with respect to operational systems is necessary because changes to a system component may have far-reaching effects on mission and business processes supported by the system. The relationships between systems and mission/business processes are, in some cases, unknown to developers. System-related information includes operational procedures.

    <ins>Related Controls</ins>: AC-2.

* (6) ACCESS RESTRICTIONS FOR CHANGE / LIMIT LIBRARY PRIVILEGES<br>
**Limit privileges to change software resident within software libraries.**

    <ins>Discussion</ins>: Software libraries include privileged programs.

    <ins>Related Controls</ins>: AC-2.

* (7) ACCESS RESTRICTIONS FOR CHANGE / AUTOMATIC IMPLEMENTATION OF SECURITY SAFEGUARDS<br>
[Withdrawn: Incorporated into SI-7.]

<ins>References</ins>: [FIPS 140-3]; [FIPS 186- 4 ]
