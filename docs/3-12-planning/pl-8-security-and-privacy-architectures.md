---
layout: page
title: -- PL-8 SECURITY AND PRIVACY ARCHITECTURES 
parent: . 3.12 PLANNING 
nav_order: 31280 
---

## PL-8 SECURITY AND PRIVACY ARCHITECTURES
   
<ins>Control</ins>:

* a. Develop security and privacy architectures for the system that:
    * 1 . Describe the requirements and approach to be taken for protecting the confidentiality, integrity, and availability of organizational information;
    * 2 . Describe the requirements and approach to be taken for processing personally identifiable information to minimize privacy risk to individuals;
    * 3 . Describe how the architectures are integrated into and support the enterprise architecture; and
    * 4 . Describe any assumptions about, and dependencies on, external systems and services;
* b. Review and update the architectures [ _Assignment: organization-defined frequency_ ] to reflect changes in the enterprise architecture; and
* c. Reflect planned architecture changes in security and privacy plans, Concept of Operations (CONOPS), criticality analysis, organizational procedures, and procurements and acquisitions.

<ins>Discussion</ins>:  The security and privacy architectures at the system level are consistent with the organization-wide security and privacy architectures described in PM-7, which are integral to and developed as part of the enterprise architecture. The architectures include an architectural description, the allocation of security and privacy functionality (including controls), security- and privacy-related information for external interfaces, information being exchanged across the interfaces, and the protection mechanisms associated with each interface. The architectures can also include other information, such as user roles and the access privileges assigned to each role; security and privacy requirements; types of information processed, stored, and transmitted by the system; supply chain risk management requirements; restoration priorities of information and system services; and other protection needs.

[SP 800-160-1] provides guidance on the use of security architectures as part of the system development life cycle process. [OMB M-19-03] requires the use of the systems security engineering concepts described in [SP 800-160-1] for high value assets. Security and privacy architectures are reviewed and updated throughout the system development life cycle, from analysis of alternatives through review of the proposed architecture in the RFP responses to the design reviews before and during implementation (e.g., during preliminary design reviews and critical design reviews).

In today’s modern computing architectures, it is becoming less common for organizations to control all information resources. There may be key dependencies on external information services and service providers. Describing such dependencies in the security and privacy architectures is necessary for developing a comprehensive mission and business protection strategy. Establishing, developing, documenting, and maintaining under configuration control a baseline configuration for organizational systems is critical to implementing and maintaining effective architectures. The development of the architectures is coordinated with the senior agency information security officer and the senior agency official for privacy to ensure that the controls needed to support security and privacy requirements are identified and effectively implemented. In many circumstances, there may be no distinction between the security and privacy architecture for a system. In other circumstances, security objectives may be adequately satisfied, but privacy objectives may only be partially satisfied by the security requirements. In these cases, consideration of the privacy requirements needed to achieve satisfaction will result in a distinct privacy architecture. The documentation, however, may simply reflect the combined architectures.

PL-8 is primarily directed at organizations to ensure that architectures are developed for the system and, moreover, that the architectures are integrated with or tightly coupled to the enterprise architecture. In contrast, SA-17 is primarily directed at the external information technology product and system developers and integrators. SA-17, which is complementary to PL-8, is selected when organizations outsource the development of systems or components to external entities and when there is a need to demonstrate consistency with the organization’s enterprise architecture and security and privacy architectures.

<ins>Related Controls</ins>: CM-2, CM-6, PL-2, PL-7, PL-9, PM-5, PM-7, RA-9, SA-3, SA-5, SA-8, SA-17, SC-7.
   
<ins>Control Enhancements</ins>:
   
* (1) SECURITY AND PRIVACY ARCHITECTURES / DEFENSE IN DEPTH<br>
**Design the security and privacy architectures for the system using a defense-in-depth approach that:**
    * **(a) Allocates [ _Assignment: organization-defined controls_ ] to [ _Assignment: organization-defined locations and architectural layers_ ]; and**
    * **(b) Ensures that the allocated controls operate in a coordinated and mutually reinforcing manner.**

    <ins>Discussion</ins>: Organizations strategically allocate security and privacy controls in the security and privacy architectures so that adversaries must overcome multiple controls to achieve their objective. Requiring adversaries to defeat multiple controls makes it more difficult to attack information resources by increasing the work factor of the adversary; it also increases the likelihood of detection. The coordination of allocated controls is essential to ensure that an attack that involves one control does not create adverse, unintended consequences by interfering with other controls. Unintended consequences can include system lockout and cascading alarms. The placement of controls in systems and organizations is an important activity that requires thoughtful analysis. The value of organizational assets is an important consideration in providing additional layering. Defense-in-depth architectural approaches include modularity and layering (see SA-8(3)), separation of system and user functionality (see SC-2), and security function isolation (see SC-3).
   
    <ins>Related Controls</ins>: SC-2, SC-3, SC-29, SC-36.
   
* (2) SECURITY AND PRIVACY ARCHITECTURES / SUPPLIER DIVERSITY<br>
**Require that [ _Assignment: organization-defined controls_ ] allocated to [ _Assignment: organization-defined locations and architectural layers_ ] are obtained from different suppliers.**

    <ins>Discussion</ins>: Information technology products have different strengths and weaknesses. Providing a broad spectrum of products complements the individual offerings. For example, vendors offering malicious code protection typically update their products at different times, often developing solutions for known viruses, Trojans, or worms based on their priorities and development schedules. By deploying different products at different locations, there is an increased likelihood that at least one of the products will detect the malicious code. With respect to privacy, vendors may offer products that track personally identifiable information in systems. Products may use different tracking methods. Using multiple products may result in more assurance that personally identifiable information is inventoried.

    <ins>Related Controls</ins>: SC-29, SR-3.

<ins>References</ins>: [OMB A-130], [SP 800-160-1], [SP 800-160-2].
