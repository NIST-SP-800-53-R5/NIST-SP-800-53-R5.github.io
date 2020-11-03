---
layout: page
title: -- SI-7 SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 31970 
---

## SI-7 SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY
 
<ins>Control</ins>:
   
* a. Employ integrity verification tools to detect unauthorized changes to the following software, firmware, and information: [ _Assignment: organization-defined software, firmware, and information_ ]; and
* b. Take the following actions when unauthorized changes to the software, firmware, and information are detected: [ _Assignment: organization-defined actions_ ].

<ins>Discussion</ins>: Unauthorized changes to software, firmware, and information can occur due to errors or malicious activity. Software includes operating systems (with key internal components, such as kernels or drivers), middleware, and applications. Firmware interfaces include Unified Extensible Firmware Interface (UEFI) and Basic Input/Output System (BIOS). Information includes personally identifiable information and metadata that contains security and privacy attributes associated with information. Integrity-checking mechanisms—including parity checks, cyclical redundancy checks, cryptographic hashes, and associated tools—can automatically monitor the integrity of systems and hosted applications.

<ins>Related Controls</ins>: AC-4, CM-3, CM-7, CM-8, MA-3, MA-4, RA-5, SA-8, SA-9, SA-10, SC-8, SC-12, SC-13, SC-28, SC-37, SI-3, SR-3, SR-4, SR-5, SR-6, SR-9, SR-10, SR-11.

<ins>Control Enhancements</ins>:
   
* (1) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / INTEGRITY CHECKS<br>
**Perform an integrity check of [ _Assignment: organization-defined software, firmware, and information_ ] [ _Selection (one or more): at startup; at [ Assignment: organization-defined transiti**onal states or security-relevant events ]; [ Assignment: organization-defined frequency ]_].**

    <ins>Discussion</ins>: Security-relevant events include the identification of new threats to which organizational systems are susceptible and the installation of new hardware, software, or firmware. Transitional states include system startup, restart, shutdown, and abort.

    <ins>Related Controls</ins>: None.
   
* (2) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / AUTOMATED NOTIFICATIONS OF INTEGRITY VIOLATIONS<br>
**Employ automated tools that provide notification to [ _Assignment: organization-defined personnel or roles_ ] upon discovering discrepancies during integrity verification.**
   
    <ins>Discussion</ins>: The employment of automated tools to report system and information integrity violations and to notify organizational personnel in a timely matter is essential to effective risk response. Personnel with an interest in system and information integrity violations include mission and business owners, system owners, senior agency information security official, senior agency official for privacy, system administrators, software developers, systems integrators, information security officers, and privacy officers.

    <ins>Related Controls</ins>: None.
   
* (3) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / CENTRALLY MANAGED INTEGRITY TOOLS<br>
**Employ centrally managed integrity verification tools.**

    <ins>Discussion</ins>: Centrally managed integrity verification tools provides greater consistency in the application of such tools and can facilitate more comprehensive coverage of integrity verification actions.

    <ins>Related Controls</ins>: AU-3 , SI-2 , SI-8.
   
* (4) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / TAMPER-EVIDENT PACKAGING<br>
[Withdrawn: Incorporated into SR-9 .]
   
* (5) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / AUTOMATED RESPONSE TO INTEGRITY VIOLATIONS<br>
**Automatically [ _Selection (one or more): shut the system down; restart the system; implement [ Assignment: organization-defined controls ]_] when integrity violations are discovered.**

    <ins>Discussion</ins>: Organizations may define different integrity-checking responses by type of information, specific information, or a combination of both. Types of information include firmware, software, and user data. Specific information includes boot firmware for certain types of machines. The automatic implementation of controls within organizational systems includes reversing the changes, halting the system, or triggering audit alerts when unauthorized modifications to critical security files occur.

    <ins>Related Controls</ins>: None.
   
* (6) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / CRYPTOGRAPHIC PROTECTION<br>
**Implement cryptographic mechanisms to detect unauthorized changes to software, firmware, and information.**

    <ins>Discussion</ins>: Cryptographic mechanisms used to protect integrity include digital signatures and the computation and application of signed hashes using asymmetric cryptography, protecting the confidentiality of the key used to generate the hash, and using the public key to verify the hash information. Organizations that employ cryptographic mechanisms also consider cryptographic key management solutions.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (7) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / INTEGRATION OF DETECTION AND RESPONSE<br>
**Incorporate the detection of the following unauthorized changes into the organizational incident response capability: [ _Assignment: organization-defined security-relevant changes to the system_ ].**

    <ins>Discussion</ins>: Integrating detection and response helps to ensure that detected events are tracked, monitored, corrected, and available for historical purposes. Maintaining historical records is important for being able to identify and discern adversary actions over an extended time period and for possible legal actions. Security-relevant changes include unauthorized changes to established configuration settings or the unauthorized elevation of system privileges.

    <ins>Related Controls</ins>: AU-2 , AU-6 , IR-4 , IR-5 , SI-4.
   
* (8) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / AUDITING CAPABILITY FOR SIGNIFICANT EVENTS<br>
**Upon detection of a potential integrity violation, provide the capability to audit the event and initiate the following actions: [ _Selection (one or more): generate an audit record; alert current user; alert [ Assignment: organization-defined personnel or roles ]; [ Assignment: organization-defined other actions ]_].**

    <ins>Discussion</ins>: Organizations select response actions based on types of software, specific software, or information for which there are potential integrity violations.

    <ins>Related Controls</ins>: AU-2 , AU-6 , AU-12.
   
* (9) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / VERIFY BOOT PROCESS<br>
**Verify the integrity of the boot process of the following system components: [ _Assignment: organization-defined system components_ ].**

    <ins>Discussion</ins>: Ensuring the integrity of boot processes is critical to starting system components in known, trustworthy states. Integrity verification mechanisms provide a level of assurance that only trusted code is executed during boot processes.

    <ins>Related Controls</ins>: SI-6.
   
* (10) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / PROTECTION OF BOOT FIRMWARE<br>
**Implement the following mechanisms to protect the integrity of boot firmware in [ _Assignment: organization-defined system components_ ]: [ _Assignment: organization-defined mechanisms_ ].**

    <ins>Discussion</ins>: Unauthorized modifications to boot firmware may indicate a sophisticated, targeted attack. These types of targeted attacks can result in a permanent denial of service or a persistent malicious code presence. These situations can occur if the firmware is corrupted or if the malicious code is embedded within the firmware. System components can protect the integrity of boot firmware in organizational systems by verifying the integrity and authenticity of all updates to the firmware prior to applying changes to the system component and preventing unauthorized processes from modifying the boot firmware.

    <ins>Related Controls</ins>: SI-6.
   
* (11) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / CONFINED ENVIRONMENTS WITH LIMITED PRIVILEGES<br>
[Withdrawn: Moved to CM-7(6).]
   
* (12) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / INTEGRITY VERIFICATION<br>
**Require that the integrity of the following user-installed software be verified prior to execution: [ _Assignment: organization-defined user-installed software_ ].**

    <ins>Discussion</ins>: Organizations verify the integrity of user-installed software prior to execution to reduce the likelihood of executing malicious code or programs that contains errors from unauthorized modifications. Organizations consider the practicality of approaches to verifying software integrity, including the availability of trustworthy checksums from software developers and vendors.

    <ins>Related Controls</ins>: CM-11.
   
* (13) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / CODE EXECUTION IN PROTECTED ENVIRONMENTS<br>[Withdrawn: Moved to CM-7(7).]

* (14) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / BINARY OR MACHINE EXECUTABLE CODE<br>
[Withdrawn: Moved to CM-7(8).]

* (15) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / CODE AUTHENTICATION<br>
**Implement cryptographic mechanisms to authenticate the following software or firmware components prior to installation: [ _Assignment: organization-defined software or firmware components_ ].**

    <ins>Discussion</ins>: Cryptographic authentication includes verifying that software or firmware components have been digitally signed using certificates recognized and approved by organizations. Code signing is an effective method to protect against malicious code. Organizations that employ cryptographic mechanisms also consider cryptographic key management solutions.

    <ins>Related Controls</ins>: CM-5 , SC-12 , SC-13.
   
* (16) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / TIME LIMIT ON PROCESS EXECUTION WITHOUT SUPERVISION<br>
**Prohibit processes from executing without supervision for more than [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: Placing a time limit on process execution without supervision is intended to apply to processes for which typical or normal execution periods can be determined and situations in which organizations exceed such periods. Supervision includes timers on operating systems, automated responses, and manual oversight and response when system process anomalies occur.

    <ins>Related Controls</ins>: None.
   
* (17) SOFTWARE, FIRMWARE, AND INFORMATION INTEGRITY / RUNTIME APPLICATION SELF-PROTECTION<br>
**Implement [ _Assignment: organization-defined controls_ ] for application self-protection at runtime.**

    <ins>Discussion</ins>: Runtime application self-protection employs runtime instrumentation to detect and block the exploitation of software vulnerabilities by taking advantage of information from the software in execution. Runtime exploit prevention differs from traditional perimeter-based protections such as guards and firewalls which can only detect and block attacks by using network information without contextual awareness. Runtime application self-protection technology can reduce the susceptibility of software to attacks by monitoring its inputs and blocking those inputs that could allow attacks. It can also help protect the runtime environment from unwanted changes and tampering. When a threat is detected, runtime application self-protection technology can prevent exploitation and take other actions (e.g., sending a warning message to the user, terminating the user's session, terminating the application, or sending an alert to organizational personnel). Runtime application self-protection solutions can be deployed in either a monitor or protection mode.

    <ins>Related Controls</ins>: SI-16.

<ins>References</ins>: [OMB A-130], [FIPS 140-3], [FIPS 180-4], [FIPS 186-4], [FIPS 202], [SP 800-70], [SP 800-147].
   
