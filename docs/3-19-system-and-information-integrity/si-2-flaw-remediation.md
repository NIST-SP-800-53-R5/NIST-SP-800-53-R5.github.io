---
layout: page
title: -- SI-2 FLAW REMEDIATION 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 31920 
---

## SI-2 FLAW REMEDIATION

<ins>Control</ins>:
* a. Identify, report, and correct system flaws;
* b. Test software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
* c. Install security-relevant software and firmware updates within [ _Assignment: organization-defined time period_ ] of the release of the updates; and
* d. Incorporate flaw remediation into the organizational configuration management process.

<ins>Discussion</ins>: The need to remediate system flaws applies to all types of software and firmware. Organizations identify systems affected by software flaws, including potential vulnerabilities resulting from those flaws, and report this information to designated organizational personnel with information security and privacy responsibilities. Security-relevant updates include patches, service packs, and malicious code signatures. Organizations also address flaws discovered during assessments, continuous monitoring, incident response activities, and system error handling. By incorporating flaw remediation into configuration management processes, required remediation actions can be tracked and verified.

Organization-defined time periods for updating security-relevant software and firmware may vary based on a variety of risk factors, including the security category of the system, the criticality of the update (i.e., severity of the vulnerability related to the discovered flaw), the organizational risk tolerance, the mission supported by the system, or the threat environment. Some types of flaw remediation may require more testing than other types. Organizations determine the type of testing needed for the specific type of flaw remediation activity under consideration and the types of changes that are to be configuration-managed. In some situations, organizations may determine that the testing of software or firmware updates is not necessary or practical, such as when implementing simple malicious code signature updates. In testing decisions, organizations consider whether security-relevant software or firmware updates are obtained from authorized sources with appropriate digital signatures.

<ins>Related Controls</ins>: CA-5 , CM-3 , CM-4 , CM-5 , CM-6 , CM-8 , MA-2 , RA-5 , SA-8 , SA-10 , SA-11 , SI-3 , SI-5 , SI-7 , SI-11.

<ins>Control Enhancements</ins>:
   
* (1) FLAW REMEDIATION / CENTRAL MANAGEMENT<br>
[Withdrawn: Incorporated into PL-9 .]
   
* (2) FLAW REMEDIATION / AUTOMATED FLAW REMEDIATION STATUS<br>
**Determine if system components have applicable security-relevant software and firmware updates installed using [ _Assignment: organization-defined automated mechanisms_ ] [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: Automated mechanisms can track and determine the status of known flaws for system components.

    <ins>Related Controls</ins>: CA-7 , SI-4.
   
* (3) FLAW REMEDIATION / TIME TO REMEDIATE FLAWS AND BENCHMARKS FOR CORRECTIVE ACTIONS<br>
    * **(a) Measure the time between flaw identification and flaw remediation; and**
    * **(b) Establish the following benchmarks for taking corrective actions: [ _Assignment: organization-defined benchmarks_ ].**

    <ins>Discussion</ins>: Organizations determine the time it takes on average to correct system flaws after such flaws have been identified and subsequently establish organizational benchmarks (i.e., time frames) for taking corrective actions. Benchmarks can be established by the type of flaw or the severity of the potential vulnerability if the flaw can be exploited.

    <ins>Related Controls</ins>: None.
   
* (4) FLAW REMEDIATION / AUTOMATED PATCH MANAGEMENT TOOLS<br>
**Employ automated patch management tools to facilitate flaw remediation to the following system components: [ _Assignment: organization-defined system components_ ].**

    <ins>Discussion</ins>: Using automated tools to support patch management helps to ensure the timeliness and completeness of system patching operations.

    <ins>Related Controls</ins>: None.
   
* (5) FLAW REMEDIATION / AUTOMATIC SOFTWARE AND FIRMWARE UPDATES<br>
**Install [ _Assignment: organization-defined security-relevant software and firmware updates_ ] automatically to [ _Assignment: organization-defined system components_ ].**

    <ins>Discussion</ins>: Due to system integrity and availability concerns, organizations consider the methodology used to carry out automatic updates. Organizations balance the need to ensure that the updates are installed as soon as possible with the need to maintain configuration management and control with any mission or operational impacts that automatic updates might impose.

    <ins>Related Controls</ins>: None.
   
* (6) FLAW REMEDIATION / REMOVAL OF PREVIOUS VERSIONS OF SOFTWARE AND FIRMWARE<br>
**Remove previous versions of [ _Assignment: organization-defined software and firmware components_ ] after updated versions have been installed.**

    <ins>Discussion</ins>: Previous versions of software or firmware components that are not removed from the system after updates have been installed may be exploited by adversaries. Some products may automatically remove previous versions of software and firmware from the system.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [FIPS 140-3], [FIPS 186-4], [SP 800-39], [SP 800-40], [SP 800-128], [IR 7788].
