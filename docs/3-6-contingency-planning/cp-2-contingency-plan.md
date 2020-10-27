---
layout: page
title: -- CP-2 CONTINGENCY PLAN 
parent: . 3.6 CONTINGENCY PLANNING 
nav_order: 3620 
---

## CP-2 CONTINGENCY PLAN

<ins>Control</ins>:

* a. Develop a contingency plan for the system that:
    * 1 . Identifies essential mission and business functions and associated contingency requirements;
    * 2 . Provides recovery objectives, restoration priorities, and metrics;
    * 3 . Addresses contingency roles, responsibilities, assigned individuals with contact information;
    * 4 . Addresses maintaining essential mission and business functions despite a system disruption, compromise, or failure;
    * 5 . Addresses eventual, full system restoration without deterioration of the controls originally planned and implemented;
    * 6 . Addresses the sharing of contingency information; and
    * 7 . Is reviewed and approved by [ _Assignment: organization-defined personnel or roles_ ];
* b. Distribute copies of the contingency plan to [ _Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements_ ];
* c. Coordinate contingency planning activities with incident handling activities;
* d. Review the contingency plan for the system [ _Assignment: organization-defined frequency_ ];
* e. Update the contingency plan to address changes to the organization, system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;
* f. Communicate contingency plan changes to [ _Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements_ ];
* g. Incorporate lessons learned from contingency plan testing, training, or actual contingency
activities into contingency testing and training; and
* h. Protect the contingency plan from unauthorized disclosure and modification.

<ins>Discussion</ins>: Contingency planning for systems is part of an overall program for achieving continuity of operations for organizational mission and business functions. Contingency planning addresses system restoration and implementation of alternative mission or business processes when systems are compromised or breached. Contingency planning is considered throughout the system development life cycle and is a fundamental part of the system design. Systems can be designed for redundancy, to provide backup capabilities, and for resilience. Contingency plans reflect the degree of restoration required for organizational systems since not all systems need to fully recover to achieve the level of continuity of operations desired. System recovery objectives reflect applicable laws, executive orders, directives, regulations, policies, standards, guidelines, organizational risk tolerance, and system impact level.

Actions addressed in contingency plans include orderly system degradation, system shutdown, fallback to a manual mode, alternate information flows, and operating in modes reserved for when systems are under attack. By coordinating contingency planning with incident handling activities, organizations ensure that the necessary planning activities are in place and activated in the event of an incident. Organizations consider whether continuity of operations during an incident conflicts with the capability to automatically disable the system, as specified in IR-4(5). Incident response planning is part of contingency planning for organizations and is addressed in the IR (Incident Response) family.

<ins>Related Controls</ins>: CP-3, CP-4, CP-6, CP-7, CP-8, CP-9, CP-10, CP-11, CP-13, IR-4, IR-6, IR-8, IR-9, MA-6, MP-2, MP-4, MP-5, PL-2, PM-8, PM-11, SA-15, SA-20, SC-7, SC-23, SI-12.

<ins>Control Enhancements</ins>:

* (1) CONTINGENCY PLAN / COORDINATE WITH RELATED PLANS<br>
**Coordinate contingency plan development with organizational elements responsible for related plans.**

    <ins>Discussion</ins>: Plans that are related to contingency plans include Business Continuity Plans, Disaster Recovery Plans, Critical Infrastructure Plans, Continuity of Operations Plans, Crisis Communications Plans, Insider Threat Implementation Plans, Data Breach Response Plans, Cyber Incident Response Plans, Breach Response Plans, and Occupant Emergency Plans.

    <ins>Related Controls</ins>: None.

* (2) CONTINGENCY PLAN / CAPACITY PLANNING<br>
**Conduct capacity planning so that necessary capacity for information processing, telecommunications, and environmental support exists during contingency operations.**

    <ins>Discussion</ins>: Capacity planning is needed because different threats can result in a reduction of the available processing, telecommunications, and support services intended to support essential mission and business functions. Organizations anticipate degraded operations during contingency operations and factor the degradation into capacity planning. For capacity planning, environmental support refers to any environmental factor for which the organization determines that it needs to provide support in a contingency situation, even if in a degraded state. Such determinations are based on an organizational assessment of risk, system categorization (impact level), and organizational risk tolerance.

    <ins>Related Controls</ins>: PE-11, PE-12, PE-13, PE-14, PE-18, SC-5.

* (3) CONTINGENCY PLAN / RESUME MISSION AND BUSINESS FUNCTIONS<br>
**Plan for the resumption of [ _Selection: all; essential_ ] mission and business functions within [ _Assignment: organization-defined time period_ ] of contingency plan activation.**

    <ins>Discussion</ins>: Organizations may choose to conduct contingency planning activities to resume mission and business functions as part of business continuity planning or as part of business impact analyses. Organizations prioritize the resumption of mission and business functions. The time period for resuming mission and business functions may be dependent on the severity and extent of the disruptions to the system and its supporting infrastructure.

    <ins>Related Controls</ins>: None.

* (4) CONTINGENCY PLAN / RESUME ALL MISSION AND BUSINESS FUNCTIONS<br>
[Withdrawn: Incorporated into CP-2(3).]

* (5) CONTINGENCY PLAN / CONTINUE MISSION AND BUSINESS FUNCTIONS<br>
**Plan for the continuance of [ _Selection: all; essential_ ] mission and business functions with minimal or no loss of operational continuity and sustains that continuity until full system restoration at primary processing and/or storage sites.**

    <ins>Discussion</ins>: Organizations may choose to conduct the contingency planning activities to continue mission and business functions as part of business continuity planning or business impact analyses. Primary processing and/or storage sites defined by organizations as part of contingency planning may change depending on the circumstances associated with the contingency.

    <ins>Related Controls</ins>: None.

* (6) CONTINGENCY PLAN / ALTERNATE PROCESSING AND STORAGE SITES<br>
**Plan for the transfer of [ _Selection: all; essential_ ] mission and business functions to alternate processing and/or storage sites with minimal or no loss of operational continuity and sustain that continuity through system restoration to primary processing and/or storage sites.**

    <ins>Discussion</ins>: Organizations may choose to conduct contingency planning activities for alternate processing and storage sites as part of business continuity planning or business impact analyses. Primary processing and/or storage sites defined by organizations as part of contingency planning may change depending on the circumstances associated with the contingency.

    <ins>Related Controls</ins>: None.

* (7) CONTINGENCY PLAN / COORDINATE WITH EXTERNAL SERVICE PROVIDERS<br>
**Coordinate the contingency plan with the contingency plans of external service providers to ensure that contingency requirements can be satisfied.**

    <ins>Discussion</ins>: When the capability of an organization to carry out its mission and business functions is dependent on external service providers, developing a comprehensive and timely contingency plan may become more challenging. When mission and business functions are dependent on external service providers, organizations coordinate contingency planning activities with the external entities to ensure that the individual plans reflect the overall contingency needs of the organization.

    <ins>Related Controls</ins>: SA-9.

* (8) CONTINGENCY PLAN / IDENTIFY CRITICAL ASSETS<br>
**Identify critical system assets supporting [ _Selection: all; essential_ ] mission and business functions.**

    <ins>Discussion</ins>: Organizations may choose to identify critical assets as part of criticality analysis, business continuity planning, or business impact analyses. Organizations identify critical system assets so that additional controls can be employed (beyond the controls routinely implemented) to help ensure that organizational mission and business functions can continue to be conducted during contingency operations. The identification of critical information assets also facilitates the prioritization of organizational resources. Critical system assets include technical and operational aspects. Technical aspects include system components, information technology services, information technology products, and mechanisms. Operational aspects include procedures (i.e., manually executed operations) and personnel (i.e., individuals operating technical controls and/or executing manual procedures). Organizational program protection plans can assist in identifying critical assets. If critical assets are resident within or supported by external service providers, organizations consider implementing CP-2(7) as a control enhancement.

    <ins>Related Controls</ins>: CM-8, RA-9.

<ins>References</ins>: [SP 800-34], [IR 8179].
