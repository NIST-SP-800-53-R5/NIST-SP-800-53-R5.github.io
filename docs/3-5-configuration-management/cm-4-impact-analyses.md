---
layout: page
title: -- CM-4 IMPACT ANALYSES 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3540 
---

## CM-4 IMPACT ANALYSES

<ins>Control</ins>: Analyze changes to the system to determine potential security and privacy impacts prior to change implementation.

<ins>Discussion</ins>: Organizational personnel with security or privacy responsibilities conduct impact analyses. Individuals conducting impact analyses possess the necessary skills and technical expertise to analyze the changes to systems as well as the security or privacy ramifications. Impact analyses include reviewing security and privacy plans, policies, and procedures to understand control requirements; reviewing system design documentation and operational procedures to understand control implementation and how specific system changes might affect the controls; reviewing the impact of changes on organizational supply chain partners with stakeholders; and determining how potential changes to a system create new risks to the privacy of individuals and the ability of implemented controls to mitigate those risks. Impact analyses also include risk assessments to understand the impact of the changes and determine if additional controls are required.

<ins>Related Controls</ins>: CA-7, CM-3, CM-8, CM-9, MA-2, RA-3, RA-5, RA-8, SA-5, SA-8, SA-10, SI-2.

<ins>Control Enhancements</ins>:

* (1) IMPACT ANALYSES | SEPARATE TEST ENVIRONMENTS<br>
**Analyze changes to the system in a separate test environment before implementation in an operational environment, looking for security and privacy impacts due to flaws, weaknesses, incompatibility, or intentional malice.**

    <ins>Discussion</ins>: A separate test environment requires an environment that is physically or logically separate and distinct from the operational environment. The separation is sufficient to ensure that activities in the test environment do not impact activities in the operational environment and that information in the operational environment is not inadvertently transmitted to the test environment. Separate environments can be achieved by physical or logical means. If physically separate test environments are not implemented, organizations determine the strength of mechanism required when implementing logical separation.

    <ins>Related Controls</ins>: SA-11, SC-7.

* (2) IMPACT ANALYSES | VERIFICATION OF CONTROLS<br>
**After system changes, verify that the impacted controls are implemented correctly, operating as intended, and producing the desired outcome with regard to meeting the security and privacy requirements for the system.**

    <ins>Discussion</ins>: Implementation in this context refers to installing changed code in the operational system that may have an impact on security or privacy controls.

    <ins>Related Controls</ins>: SA-11, SC-3, SI-6.

<ins>References</ins>: [SP 800-128].
