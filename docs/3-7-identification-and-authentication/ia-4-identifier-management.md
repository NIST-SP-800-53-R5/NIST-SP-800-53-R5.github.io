---
layout: page
title: -- IA-4 IDENTIFIER MANAGEMENT 
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 3740 
---

## IA-4 IDENTIFIER MANAGEMENT

<ins>Control</ins>: Manage system identifiers by:
* a. Receiving authorization from [ _Assignment: organization-defined personnel or roles_ ] to assign an individual, group, role, service, or device identifier;
* b. Selecting an identifier that identifies an individual, group, role, service, or device;
* c. Assigning the identifier to the intended individual, group, role, service, or device; and
* d. Preventing reuse of identifiers for [ _Assignment: organization-defined time period_ ].

<ins>Discussion</ins>: Common device identifiers include Media Access Control (MAC) addresses, Internet Protocol (IP) addresses, or device-unique token identifiers. The management of individual identifiers is not applicable to shared system accounts. Typically, individual identifiers are the usernames of the system accounts assigned to those individuals. In such instances, the account management activities of AC-2 use account names provided by IA-4. Identifier management also addresses individual identifiers not necessarily associated with system accounts. Preventing the reuse of identifiers implies preventing the assignment of previously used individual, group, role, service, or device identifiers to different individuals, groups, roles, services, or devices.

<ins>Related Controls</ins>: AC-5, IA-2, IA-3, IA-5, IA-8, IA-9, IA-12, MA-4, PE-2, PE-3, PE-4, PL-4, PM-12, PS- 3, PS-4, PS-5, SC-37.

<ins>Control Enhancements</ins>:

(1) IDENTIFIER MANAGEMENT / PROHIBIT ACCOUNT IDENTIFIERS AS PUBLIC IDENTIFIERS<br>
**Prohibit the use of system account identifiers that are the same as public identifiers for individual accounts.**

    <ins>Discussion</ins>: Prohibiting account identifiers as public identifiers applies to any publicly disclosed account identifier used for communication such as, electronic mail and instant messaging. Prohibiting the use of systems account identifiers that are the same as some public identifier, such as the individual identifier section of an electronic mail address, makes it more difficult for adversaries to guess user identifiers. Prohibiting account identifiers as public identifiers without the implementation of other supporting controls only complicates guessing of identifiers. Additional protections are required for authenticators and credentials to protect the account.

    <ins>Related Controls</ins>: AT-2, PT-7.

* (2) IDENTIFIER MANAGEMENT / SUPERVISOR AUTHORIZATION<br>
[Withdrawn: Incorporated into IA -12(1).]

* (3) IDENTIFIER MANAGEMENT / MULTIPLE FORMS OF CERTIFICATION<br>
[Withdrawn: Incorporated into IA -12(2).]

* (4) IDENTIFIER MANAGEMENT / IDENTIFY USER STATUS<br>
**Manage individual identifiers by uniquely identifying each individual as [ _Assignment: organization-defined characteristic identifying individual status_ ].**

    <ins>Discussion</ins>: Characteristics that identify the status of individuals include contractors, foreign nationals, and non-organizational users. Identifying the status of individuals by these characteristics provides additional information about the people with whom organizational personnel are communicating. For example, it might be useful for a government employee to know that one of the individuals on an email message is a contractor.

    <ins>Related Controls</ins>: None.

* (5) IDENTIFIER MANAGEMENT / DYNAMIC MANAGEMENT<br>
**Manage individual identifiers dynamically in accordance with [ _Assignment: organization-defined dynamic identifier policy_ ].**

    <ins>Discussion</ins>: In contrast to conventional approaches to identification that presume static accounts for preregistered users, many distributed systems establish identifiers at runtime for entities that were previously unknown. When identifiers are established at runtime for previously unknown entities, organizations can anticipate and provision for the dynamic establishment of identifiers. Pre-established trust relationships and mechanisms with appropriate authorities to validate credentials and related identifiers are essential.

    <ins>Related Controls</ins>: AC-16.

* (6) IDENTIFIER MANAGEMENT / CROSS-ORGANIZATION MANAGEMENT<br>
**Coordinate with the following external organizations for cross-organization management of identifiers: [ _Assignment: organization-defined external organizations_ ].**

    <ins>Discussion</ins>: Cross-organization identifier management provides the capability to identify individuals, groups, roles, or devices when conducting cross-organization activities involving the processing, storage, or transmission of information.

    <ins>Related Controls</ins>: AU-16, IA-2, IA-5.

* (7) IDENTIFIER MANAGEMENT / IN-PERSON REGISTRATION<br>
[Withdrawn: Incorporated into IA -12(4).]

* (8) IDENTIFIER MANAGEMENT / PAIRWISE PSEUDONYMOUS IDENTIFIERS<br>
**Generate pairwise pseudonymous identifiers.**

    <ins>Discussion</ins>: A pairwise pseudonymous identifier is an opaque unguessable subscriber identifier generated by an identity provider for use at a specific individual relying party. Generating distinct pairwise pseudonymous identifiers with no identifying information about a subscriber discourages subscriber activity tracking and profiling beyond the operational requirements established by an organization. The pairwise pseudonymous identifiers are unique to each relying party except in situations where relying parties can show a demonstrable relationship justifying an operational need for correlation, or all parties consent to being correlated in such a manner.
    
    <ins>Related Controls</ins>: IA-5.

* (9) IDENTIFIER MANAGEMENT / ATTRIBUTE MAINTENANCE AND PROTECTION<br>
**Maintain the attributes for each uniquely identified individual, device, or service in [ _Assignment: organization-defined protected central storage_ ].**

    <ins>Discussion</ins>: For each of the entities covered in IA-2, IA-3, IA-8, and IA-9, it is important to maintain the attributes for each authenticated entity on an ongoing basis in a central (protected) store.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 201-2], [SP 800-63-3], [SP 800-73-4], [SP 800-76-2], [SP 800-78-4].

