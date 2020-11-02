---
layout: page
title: -- SA-15 DEVELOPMENT PROCESS, STANDARDS, AND TOOLS 
parent: . 3.17 SYSTEM AND SERVICES ACQUISITION 
nav_order: 317150 
---

## SA-15 DEVELOPMENT PROCESS, STANDARDS, AND TOOLS

<ins>Control</ins>:

* a. Require the developer of the system, system component, or system service to follow a documented development process that:
    * 1 . Explicitly addresses security and privacy requirements;
    * 2 . Identifies the standards and tools used in the development process;
    * 3 . Documents the specific tool options and tool configurations used in the development process; and
    * 4 . Documents, manages, and ensures the integrity of changes to the process and/or tools used in development; and
* b. Review the development process, standards, tools, tool options, and tool configurations [ _Assignment: organization-defined frequency_ ] to determine if the process, standards, tools, tool options and tool configurations selected and employed can satisfy the following security and privacy requirements: [ _Assignment: organization-defined security and privacy requirements_ ].

    <ins>Discussion</ins>: Development tools include programming languages and computer-aided design systems. Reviews of development processes include the use of maturity models to determine the potential effectiveness of such processes. Maintaining the integrity of changes to tools and processes facilitates effective supply chain risk assessment and mitigation. Such integrity requires configuration control throughout the system development life cycle to track authorized changes and prevent unauthorized changes.

    <ins>Related Controls</ins>: MA-6 , SA-3 , SA-4 , SA-8 , SA-10 , SA-11 , SR-3 , SR-4 , SR-5 , SR-6 , SR-9.
    
    <ins>Control Enhancements</ins>:
   
* (1) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / QUALITY METRICS<br>
**Require the developer of the system, system component, or system service to:**
    * **(a) Define quality metrics at the beginning of the development process; and**
    * **(b) Provide evidence of meeting the quality metrics [ _Selection (one or more): [ Assignment: organization-defined frequency ] ; [ Assignment: organization-defined program review milestones ] ; upon deliver_y ].**

    <ins>Discussion</ins>: Organizations use quality metrics to establish acceptable levels of system quality. Metrics can include quality gates, which are collections of completion criteria or sufficiency standards that represent the satisfactory execution of specific phases of the system development project. For example, a quality gate may require the elimination of all compiler warnings or a determination that such warnings have no impact on the effectiveness of required security or privacy capabilities. During the execution phases of development projects, quality gates provide clear, unambiguous indications of progress. Other metrics apply to the entire development project. Metrics can include defining the severity thresholds of vulnerabilities in accordance with organizational risk tolerance, such as requiring no known vulnerabilities in the delivered system with a Common Vulnerability Scoring System (CVSS) severity of medium or high.

    <ins>Related Controls</ins>: None.
   
* (2) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / SECURITY AND PRIVACY TRACKING TOOLS<br>
**Require the developer of the system, system component, or system service to select and employ security and privacy tracking tools for use during the development process.**

    <ins>Discussion</ins>: System development teams select and deploy security and privacy tracking tools, including vulnerability or work item tracking systems that facilitate assignment, sorting, filtering, and tracking of completed work items or tasks associated with development processes.

    <ins>Related Controls</ins>: SA-11.
   
* (3) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / CRITICALITY ANALYSIS<br>
**Require the developer of the system, system component, or system service to perform a criticality analysis:**
    * **(a) At the following decision points in the system development life cycle: [ _Assignment: organization-defined decision points in the system development life cycle_ ]; and**
    * **(b) At the following level of rigor: [ _Assignment: organization-defined breadth and depth of criticality analysis_ ].**

    <ins>Discussion</ins>: Criticality analysis performed by the developer provides input to the criticality analysis performed by organizations. Developer input is essential to organizational criticality analysis because organizations may not have access to detailed design documentation for system components that are developed as commercial off-the-shelf products. Such design documentation includes functional specifications, high-level designs, low-level designs, source code, and hardware schematics. Criticality analysis is important for organizational systems that are designated as high value assets. High value assets can be moderate- or high-impact systems due to heightened adversarial interest or potential adverse effects on the federal enterprise. Developer input is especially important when organizations conduct supply chain criticality analyses.

    <ins>Related Controls</ins>: RA-9.
   
* (4) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / THREAT MODELING AND VULNERABILITY
ANALYSIS<br>
[Withdrawn: Incorporated into SA-11(2).]
   
* (5) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / ATTACK SURFACE REDUCTION<br>
**Require the developer of the system, system component, or system service to reduce attack surfaces to [ _Assignment: organization-defined thresholds_ ].**

    <ins>Discussion</ins>: Attack surface reduction is closely aligned with threat and vulnerability analyses and system architecture and design. Attack surface reduction is a means of reducing risk to organizations by giving attackers less opportunity to exploit weaknesses or deficiencies (i.e., potential vulnerabilities) within systems, system components, and system services. Attack surface reduction includes implementing the concept of layered defenses, applying the principles of least privilege and least functionality, applying secure software development practices, deprecating unsafe functions, reducing entry points available to unauthorized users, reducing the amount of code that executes, and eliminating application programming interfaces (APIs) that are vulnerable to attacks.

    <ins>Related Controls</ins>: AC-6 , CM-7 , RA-3 , SA-11.
   
* (6) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / CONTINUOUS IMPROVEMENT<br>
**Require the developer of the system, system component, or system service to implement an explicit process to continuously improve the development process.**

    <ins>Discussion</ins>: Developers of systems, system components, and system services consider the effectiveness and efficiency of their development processes for meeting quality objectives and addressing the security and privacy capabilities in current threat environments.

    <ins>Related Controls</ins>: None.
   
* (7) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / AUTOMATED VULNERABILITY ANALYSIS<br>
**Require the developer of the system, system component, or system service [ _Assignment: organization-defined frequency_ ] to:**
    * **(a) Perform an automated vulnerability analysis using [ _Assignment: organization-defined tools_ ];**
    * **(b) Determine the exploitation potential for discovered vulnerabilities;**
    * **(c) Determine potential risk mitigations for delivered vulnerabilities; and**
    * **(d) Deliver the outputs of the tools and results of the analysis to [ _Assignment: organization-defined personnel or roles_ ].**

    <ins>Discussion</ins>: Automated tools can be more effective at analyzing exploitable weaknesses or deficiencies in large and complex systems, prioritizing vulnerabilities by severity, and providing recommendations for risk mitigations.

    <ins>Related Controls</ins>: RA-5 , SA-11.
   
* (8) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / REUSE OF THREAT AND VULNERABILITY INFORMATION<br>
**Require the developer of the system, system component, or system service to use threat modeling and vulnerability analyses from similar systems, components, or services to inform the current development process.**

    <ins>Discussion</ins>: Analysis of vulnerabilities found in similar software applications can inform potential design and implementation issues for systems under development. Similar systems or system components may exist within developer organizations. Vulnerability information is available from a variety of public and private sector sources, including the NIST National Vulnerability Database.

    <ins>Related Controls</ins>: None.
   
* (9) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / USE OF LIVE DATA<br>
[Withdrawn: Incorporated into SA-3(2).]
   
* (10) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / INCIDENT RESPONSE PLAN<br>
**Require the developer of the system, system component, or system service to provide, implement, and test an incident response plan.**

    <ins>Discussion</ins>: The incident response plan provided by developers may provide information not readily available to organizations and be incorporated into organizational incident response plans. Developer information may also be extremely helpful, such as when organizations respond to vulnerabilities in commercial off-the-shelf products.

    <ins>Related Controls</ins>: IR-8.
   
* (11) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / ARCHIVE SYSTEM OR COMPONENT<br>
**Require the developer of the system or system component to archive the system or component to be released or delivered together with the corresponding evidence supporting the final security and privacy review.**

    <ins>Discussion</ins>: Archiving system or system components requires the developer to retain key development artifacts, including hardware specifications, source code, object code, and relevant documentation from the development process that can provide a readily available configuration baseline for system and component upgrades or modifications.

    <ins>Related Controls</ins>: CM-2.
   
* (12) DEVELOPMENT PROCESS, STANDARDS, AND TOOLS / MINIMIZE PERSONALLY IDENTIFIABLE INFORMATION<br>
**Require the developer of the system or system component to minimize the use of personally identifiable information in development and test environments.**

    <ins>Discussion</ins>: Organizations can minimize the risk to an individual’s privacy by using techniques such as de-identification or synthetic data. Limiting the use of personally identifiable information in development and test environments helps reduce the level of privacy risk created by a system.
   
    <ins>Related Controls</ins>: PM-25 , SA-3 , SA-8.

<ins>References</ins>: [SP 800-160-1], [IR 8179].
