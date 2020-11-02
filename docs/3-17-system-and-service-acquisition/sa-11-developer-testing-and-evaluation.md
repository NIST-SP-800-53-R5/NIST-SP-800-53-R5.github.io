---
layout: page
title: -- SA-11 DEVELOPER TESTING AND EVALUATION 
parent: . 3.17 SYSTEM AND SERVICES ACQUISITION 
nav_order: 317110 
---

## SA-11 DEVELOPER TESTING AND EVALUATION

<ins>Control</ins>: Require the developer of the system, system component, or system service, at all post-design stages of the system development life cycle, to:
* a. Develop and implement a plan for ongoing security and privacy assessments;
* b. Perform [ _Selection (one or more): unit; integration; system; regression_ ] testing/evaluation [ _Assignment: organization-defined frequency_ ] at [ _Assignment: organization-defined depth and coverage_ ];
* c. Produce evidence of the execution of the assessment plan and the results of the testing and evaluation;
* d. Implement a verifiable flaw remediation process; and
* e. Correct flaws identified during testing and evaluation.
 
<ins>Discussion</ins>: Developmental testing and evaluation confirms that the required controls are implemented correctly, operating as intended, enforcing the desired security and privacy policies, and meeting established security and privacy requirements. Security properties of systems and the privacy of individuals may be affected by the interconnection of system components or changes to those components. The interconnections or changes—including upgrading or replacing applications, operating systems, and firmware—may adversely affect previously implemented controls. Ongoing assessment during development allows for additional types of testing and evaluation that developers can conduct to reduce or eliminate potential flaws. Testing custom software applications may require approaches such as manual code review, security architecture review, and penetration testing, as well as and static analysis, dynamic analysis, binary analysis, or a hybrid of the three analysis approaches.

Developers can use the analysis approaches, along with security instrumentation and fuzzing, in a variety of tools and in source code reviews. The security and privacy assessment plans include the specific activities that developers plan to carry out, including the types of analyses, testing, evaluation, and reviews of software and firmware components; the degree of rigor to be applied; the frequency of the ongoing testing and evaluation; and the types of artifacts produced during those processes. The depth of testing and evaluation refers to the rigor and level of detail associated with the assessment process. The coverage of testing and evaluation refers to the scope (i.e., number and type) of the artifacts included in the assessment process. Contracts specify the acceptance criteria for security and privacy assessment plans, flaw remediation processes, and the evidence that the plans and processes have been diligently applied. Methods for reviewing and protecting assessment plans, evidence, and documentation are commensurate with the security category or classification level of the system. Contracts may specify protection requirements for documentation.
   
<ins>Related Controls</ins>: CA-2 , CA-7 , CM-4 , SA-3 , SA-4 , SA-5 , SA-8 , SA-15 , SA-17 , SI-2 , SR-5 , SR-6 , SR-7.

<ins>Control Enhancements</ins>:

* (1) DEVELOPER TESTING AND EVALUATION / STATIC CODE ANALYSIS<br>
**Require the developer of the system, system component, or system service to employ static code analysis tools to identify common flaws and document the results of the analysis.**

    <ins>Discussion</ins>: Static code analysis provides a technology and methodology for security reviews and includes checking for weaknesses in the code as well as for the incorporation of libraries or other included code with known vulnerabilities or that are out-of-date and not supported. Static code analysis can be used to identify vulnerabilities and enforce secure coding practices. It is most effective when used early in the development process, when each code change can automatically be scanned for potential weaknesses. Static code analysis can provide clear remediation guidance and identify defects for developers to fix. Evidence of the correct implementation of static analysis can include aggregate defect density for critical defect types, evidence that defects were inspected by developers or security professionals, and evidence that defects were remediated. A high density of ignored findings, commonly referred to as false positives, indicates a potential problem with the analysis process or the analysis tool. In such cases, organizations weigh the validity of the evidence against evidence from other sources.

    <ins>Related Controls</ins>: None.
   
* (2) DEVELOPER TESTING AND EVALUATION / THREAT MODELING AND VULNERABILITY ANALYSES<br>
**Require the developer of the system, system component, or system service to perform threat modeling and vulnerability analyses during development and the subsequent testing and evaluation of the system, component, or service that:**
    * **(a) Uses the following contextual information: [ _Assignment: organization-defined information concerning impact, environment of operations, known or assumed threats, and acceptable risk levels_ ];**
    * **(b) Employs the following tools and methods: [ _Assignment: organization-defined tools and methods_ ];**
    * **(c) Conducts the modeling and analyses at the following level of rigor: [ _Assignment: organization-defined breadth and depth of modeling and analyses_ ]; and**
    * **(d) Produces evidence that meets the following acceptance criteria: [ _Assignment: organization-defined acceptance criteria_ ].**

    <ins>Discussion</ins>: Systems, system components, and system services may deviate significantly from the functional and design specifications created during the requirements and design stages of the system development life cycle. Therefore, updates to threat modeling and vulnerability analyses of those systems, system components, and system services during development and prior to delivery are critical to the effective operation of those systems, components, and services. Threat modeling and vulnerability analyses at this stage of the system development life cycle ensure that design and implementation changes have been accounted for and that vulnerabilities created because of those changes have been reviewed and mitigated.

    <ins>Related Controls</ins>: PM-15 , RA-3 , RA-5.
   
* (3) DEVELOPER TESTING AND EVALUATION / INDEPENDENT VERIFICATION OF ASSESSMENT PLANS AND EVIDENCE<br>
    * **(a) Require an independent agent satisfying [ _Assignment: organization-defined independence criteria_ ] to verify the correct implementation of the developer security and privacy assessment plans and the evidence produced during testing and evaluation; and**
    * **(b) Verify that the independent agent is provided with sufficient information to complete the verification process or granted the authority to obtain such information.**

    <ins>Discussion</ins>: Independent agents have the qualifications—including the expertise, skills, training, certifications, and experience—to verify the correct implementation of developer security and privacy assessment plans.

    <ins>Related Controls</ins>: AT-3 , RA-5.
   
* (4) DEVELOPER TESTING AND EVALUATION / MANUAL CODE REVIEWS<br>
**Require the developer of the system, system component, or system service to perform a manual code review of [ _Assignment: organization-defined specific code_ ] using the following processes, procedures, and/or techniques: [ _Assignment: organization-defined processes, procedures, and/or techniques_ ].**

    <ins>Discussion</ins>: Manual code reviews are usually reserved for the critical software and firmware components of systems. Manual code reviews are effective at identifying weaknesses that require knowledge of the application’s requirements or context that, in most cases, is unavailable to automated analytic tools and techniques, such as static and dynamic analysis. The benefits of manual code review include the ability to verify access control matrices against application controls and review detailed aspects of cryptographic implementations and controls.

    <ins>Related Controls</ins>: None.
   
* (5) DEVELOPER TESTING AND EVALUATION / PENETRATION TESTING<br>
**Require the developer of the system, system component, or system service to perform penetration testing:**
    * **(a) At the following level of rigor: [ Assignment: organization-defined breadth and depth of testing ]; and**
    * **(b) Under the following constraints: [ Assignment: organization-defined constraints ].**

    <ins>Discussion</ins>: Penetration testing is an assessment methodology in which assessors, using all available information technology product or system documentation and working under specific constraints, attempt to circumvent the implemented security and privacy features of information technology products and systems. Useful information for assessors who conduct penetration testing includes product and system design specifications, source code, and administrator and operator manuals. Penetration testing can include white-box, gray-box, or black-box testing with analyses performed by skilled professionals who simulate adversary actions. The objective of penetration testing is to discover vulnerabilities in systems, system components, and services that result from implementation errors, configuration faults, or other operational weaknesses or deficiencies. Penetration tests can be performed in conjunction with automated and manual code reviews to provide a greater level of analysis than would ordinarily be possible. When user session information and other personally identifiable information is captured or recorded during penetration testing, such information is handled appropriately to protect privacy.
   
    <ins>Related Controls</ins>: CA-8 , PM-14 , PM-25 , PT-2 , SA-3 , SI-2 , SI-6.

* (6) DEVELOPER TESTING AND EVALUATION / ATTACK SURFACE REVIEWS<br>
**Require the developer of the system, system component, or system service to perform attack surface reviews.**

    <ins>Discussion</ins>: Attack surfaces of systems and system components are exposed areas that make those systems more vulnerable to attacks. Attack surfaces include any accessible areas where weaknesses or deficiencies in the hardware, software, and firmware components provide opportunities for adversaries to exploit vulnerabilities. Attack surface reviews ensure that developers analyze the design and implementation changes to systems and mitigate attack vectors generated as a result of the changes. The correction of identified flaws includes deprecation of unsafe functions.

    <ins>Related Controls</ins>: SA-15.
   
* (7) DEVELOPER TESTING AND EVALUATION / VERIFY SCOPE OF TESTING AND EVALUATION<br>
**Require the developer of the system, system component, or system service to verify that the scope of testing and evaluation provides complete coverage of the required controls at the following level of rigor: [ _Assignment: organization-defined breadth and depth of testing and evaluation_ ].**

    <ins>Discussion</ins>: Verifying that testing and evaluation provides complete coverage of required controls can be accomplished by a variety of analytic techniques ranging from informal to formal. Each of these techniques provides an increasing level of assurance that corresponds to the degree of formality of the analysis. Rigorously demonstrating control coverage at the highest levels of assurance can be achieved using formal modeling and analysis techniques, including correlation between control implementation and corresponding test cases.

    <ins>Related Controls</ins>: SA-15.
   
* (8) DEVELOPER TESTING AND EVALUATION / DYNAMIC CODE ANALYSIS<br>
**Require the developer of the system, system component, or system service to employ dynamic code analysis tools to identify common flaws and document the results of the analysis.**

    <ins>Discussion</ins>: Dynamic code analysis provides runtime verification of software programs using tools capable of monitoring programs for memory corruption, user privilege issues, and other potential security problems. Dynamic code analysis employs runtime tools to ensure that security functionality performs in the way it was designed. A type of dynamic analysis, known as fuzz testing, induces program failures by deliberately introducing malformed or random data into software programs. Fuzz testing strategies are derived from the intended use of applications and the functional and design specifications for the applications. To understand the scope of dynamic code analysis and the assurance provided, organizations may also consider conducting code coverage analysis (i.e., checking the degree to which the code has been tested using metrics such as percent of subroutines tested or percent of program statements called during execution of the test suite) and/or concordance analysis (i.e., checking for words that are out of place in software code, such as non-English language words or derogatory terms).

    <ins>Related Controls</ins>: None.
   
* (9) DEVELOPER TESTING AND EVALUATION / INTERACTIVE APPLICATION SECURITY TESTING<br>
**Require the developer of the system, system component, or system service to employ interactive application security testing tools to identify flaws and document the results.**

    <ins>Discussion</ins>: Interactive (also known as instrumentation-based) application security testing is a method of detecting vulnerabilities by observing applications as they run during testing. The use of instrumentation relies on direct measurements of the actual running applications and uses access to the code, user interaction, libraries, frameworks, backend connections, and configurations to directly measure control effectiveness. When combined with analysis techniques, interactive application security testing can identify a broad range of potential vulnerabilities and confirm control effectiveness. Instrumentation-based testing works in real time and can be used continuously throughout the system development life cycle.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [ISO 15408-3], [SP 800-30], [SP 800-53A], [SP 800-154], [SP 800-160-1].
   

