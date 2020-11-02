---
layout: page
title: -- SC-8 TRANSMISSION CONFIDENTIALITY AND INTEGRITY 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31880 
---

## SC-8 TRANSMISSION CONFIDENTIALITY AND INTEGRITY

<ins>Control</ins>: Protect the [ _Selection (one or more): confidentiality; integrity_ ] of transmitted information.

<ins>Discussion</ins>: Protecting the confidentiality and integrity of transmitted information applies to internal and external networks as well as any system components that can transmit information, including servers, notebook computers, desktop computers, mobile devices, printers, copiers, scanners, facsimile machines, and radios. Unprotected communication paths are exposed to the possibility of interception and modification. Protecting the confidentiality and integrity of information can be accomplished by physical or logical means. Physical protection can be achieved by using protected distribution systems. A protected distribution system is a wireline or fiber-optics telecommunications system that includes terminals and adequate electromagnetic, acoustical, electrical, and physical controls to permit its use for the unencrypted transmission of classified information. Logical protection can be achieved by employing encryption techniques.

Organizations that rely on commercial providers who offer transmission services as commodity services rather than as fully dedicated services may find it difficult to obtain the necessary assurances regarding the implementation of needed controls for transmission confidentiality and integrity. In such situations, organizations determine what types of confidentiality or integrity services are available in standard, commercial telecommunications service packages. If it is not feasible to obtain the necessary controls and assurances of control effectiveness through appropriate contracting vehicles, organizations can implement appropriate compensating controls.

<ins>Related Controls</ins>: AC-17, AC-18, AU-10, IA-3, IA-8, IA-9, MA-4, PE-4, SA-4, SA-8, SC-7, SC-16, SC- 20, SC-23, SC-28.

<ins>Control Enhancements</ins>:
   
* (1) TRANSMISSION CONFIDENTIALITY AND INTEGRITY / CRYPTOGRAPHIC PROTECTION<br>
**Implement cryptographic mechanisms to [ _Selection (one or more): prevent unauthorized disclosure of information; detect changes to information_ ] during transmission.**

    <ins>Discussion</ins>: Encryption protects information from unauthorized disclosure and modification during transmission. Cryptographic mechanisms that protect the confidentiality and integrity of information during transmission include TLS and IPSec. Cryptographic mechanisms used to protect information integrity include cryptographic hash functions that have applications in digital signatures, checksums, and message authentication codes.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (2) TRANSMISSION CONFIDENTIALITY AND INTEGRITY / PRE-AND POST-TRANSMISSION HANDLING<br>
**Maintain the [ _Selection (one or more): confidentiality; integrity_ ] of information during preparation for transmission and during reception.**

    <ins>Discussion</ins>: Information can be unintentionally or maliciously disclosed or modified during preparation for transmission or during reception, including during aggregation, at protocol transformation points, and during packing and unpacking. Such unauthorized disclosures or modifications compromise the confidentiality or integrity of the information.

    <ins>Related Controls</ins>: None.
   
* (3) TRANSMISSION CONFIDENTIALITY AND INTEGRITY / CRYPTOGRAPHIC PROTECTION FOR MESSAGE EXTERNALS
**Implement cryptographic mechanisms to protect message externals unless otherwise protected by [ _Assignment: organization-defined alternative physical controls_ ].**

    <ins>Discussion</ins>: Cryptographic protection for message externals addresses protection from the unauthorized disclosure of information. Message externals include message headers and routing information. Cryptographic protection prevents the exploitation of message externals and applies to internal and external networks or links that may be visible to individuals who are not authorized users. Header and routing information is sometimes transmitted in clear text (i.e., unencrypted) because the information is not identified by organizations as having significant value or because encrypting the information can result in lower network performance or higher costs. Alternative physical controls include protected distribution systems.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (4) TRANSMISSION CONFIDENTIALITY AND INTEGRITY / CONCEAL OR RANDOMIZE COMMUNICATIONS<br>
**Implement cryptographic mechanisms to conceal or randomize communication patterns unless otherwise protected by [ _Assignment: organization-defined alternative physical controls_ ].**

    <ins>Discussion</ins>: Concealing or randomizing communication patterns addresses protection from unauthorized disclosure of information. Communication patterns include frequency, periods, predictability, and amount. Changes to communications patterns can reveal information with intelligence value, especially when combined with other available information related to the mission and business functions of the organization. Concealing or randomizing communications prevents the derivation of intelligence based on communications patterns and applies to both internal and external networks or links that may be visible to individuals who are not authorized users. Encrypting the links and transmitting in continuous, fixed, or random patterns prevents the derivation of intelligence from the system communications patterns. Alternative physical controls include protected distribution systems.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (5) TRANSMISSION CONFIDENTIALITY AND INTEGRITY / PROTECTED DISTRIBUTION SYSTEM<br>
**Implement [ _Assignment: organization-defined protected distribution system_ ] to [ _Selection (one or more): prevent unauthorized disclosure of information; detect changes to information_ ] during transmission.**

    <ins>Discussion</ins>: The purpose of a protected distribution system is to deter, detect, and/or make difficult physical access to the communication lines that carry national security information.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3 ], [FIPS 197], [SP 800-52], [SP 800-77], [SP 800-81-2], [SP 800-113], [SP 800-177], [IR 8023].
