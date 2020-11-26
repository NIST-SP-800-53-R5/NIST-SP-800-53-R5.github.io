---
layout: page
title: -- RA-3 RISK ASSESSMENT 
parent: . 3.16 RISK ASSESSMENT
nav_order: 31630
---

## RA-3 RISK ASSESSMENT

<ins>Control</ins>:
* a. Conduct a risk assessment, including:
    * 1 . Identifying threats to and vulnerabilities in the system;
    * 2 . Determining the likelihood and magnitude of harm from unauthorized access, use, disclosure, disruption, modification, or destruction of the system, the information it processes, stores, or transmits, and any related information; and
    * 3 . Determining the likelihood and impact of adverse effects on individuals arising from the processing of personally identifiable information;
* b. Integrate risk assessment results and risk management decisions from the organization and mission or business process perspectives with system-level risk assessments;
* c. Document risk assessment results in [ _Selection: security and privacy plans; risk assessment report; [ Assignment: organization-defined document ]_ ];
* d. Review risk assessment results [ _Assignment: organization-defined frequency_ ];
* e. Disseminate risk assessment results to [ _Assignment: organization-defined personnel or roles_ ]; and
* f. Update the risk assessment [ _Assignment: organization-defined frequency_ ] or when there are significant changes to the system, its environment of operation, or other conditions that may impact the security or privacy state of the system.

<ins>Discussion</ins>: Risk assessments consider threats, vulnerabilities, likelihood, and impact to organizational operations and assets, individuals, other organizations, and the Nation. Risk assessments also consider risk from external parties, including contractors who operate systems on behalf of the organization, individuals who access organizational systems, service providers, and outsourcing entities.

Organizations can conduct risk assessments at all three levels in the risk management hierarchy (i.e., organization level, mission/business process level, or information system level) and at any stage in the system development life cycle. Risk assessments can also be conducted at various steps in the Risk Management Framework, including preparation, categorization, control selection, control implementation, control assessment, authorization, and control monitoring. Risk assessment is an ongoing activity carried out throughout the system development life cycle.

Risk assessments can also address information related to the system, including system design, the intended use of the system, testing results, and supply chain-related information or artifacts. Risk assessments can play an important role in control selection processes, particularly during the application of tailoring guidance and in the earliest phases of capability determination.

<ins>Related Controls</ins>: CA-3, CA-6, CM-4, CM-13, CP-6, CP-7, IA-8, MA-5, PE-3, PE-8, PE-18, PL-2, PL- 10, PL-11, PM-8, PM-9, PM-28, PT-7, RA-2, RA-5, RA-7, SA-8, SA-9, SC-38, SI-12.

<ins>Control Enhancements</ins>:
   
* (1) RISK ASSESSMENT / SUPPLY CHAIN RISK ASSESSMENT<br>
    * **(a) Assess supply chain risks associated with [ _Assignment: organization-defined systems, system components, and system services_ ]; and**
    * **(b) Update the supply chain risk assessment [ _Assignment: organization-defined frequency_ ], when there are significant changes to the relevant supply chain, or when changes to the system, environments of operation, or other conditions may necessitate a change in the supply chain.**

    <ins>Discussion</ins>: Supply chain-related events include disruption, use of defective components, insertion of counterfeits, theft, malicious development practices, improper delivery practices, and insertion of malicious code. These events can have a significant impact on the confidentiality, integrity, or availability of a system and its information and, therefore, can also adversely impact organizational operations (including mission, functions, image, or reputation), organizational assets, individuals, other organizations, and the Nation. The supply chain-related events may be unintentional or malicious and can occur at any point during the system life cycle. An analysis of supply chain risk can help an organization identify systems or components for which additional supply chain risk mitigations are required.

    <ins>Related Controls</ins>: RA-2, RA-9, PM-17, PM-30, SR-2.
   
* (2) RISK ASSESSMENT / USE OF ALL-SOURCE INTELLIGENCE<br>
**Use all-source intelligence to assist in the analysis of risk.**

    <ins>Discussion</ins>: Organizations employ all-source intelligence to inform engineering, acquisition, and risk management decisions. All-source intelligence consists of information derived from all available sources, including publicly available or open-source information, measurement and signature intelligence, human intelligence, signals intelligence, and imagery intelligence. All-source intelligence is used to analyze the risk of vulnerabilities (both intentional and unintentional) from development, manufacturing, and delivery processes, people, and the environment. The risk analysis may be performed on suppliers at multiple tiers in the supply chain sufficient to manage risks. Organizations may develop agreements to share all-source intelligence information or resulting decisions with other organizations, as appropriate.

    <ins>Related Controls</ins>: None.
   
* (3) RISK ASSESSMENT / DYNAMIC THREAT AWARENESS<br>
**Determine the current cyber threat environment on an ongoing basis using [ _Assignment: organization-defined means_ ].**

    <ins>Discussion</ins>: The threat awareness information that is gathered feeds into the organization’s information security operations to ensure that procedures are updated in response to the changing threat environment. For example, at higher threat levels, organizations may change the privilege or authentication thresholds required to perform certain operations.

    <ins>Related Controls</ins>: AT-2.
   
* (4) RISK ASSESSMENT / PREDICTIVE CYBER ANALYTICS<br>
**Employ the following advanced automation and analytics capabilities to predict and identify risks to [ _Assignment: organization-defined systems or system components_ ]:[ _Assignment: organization-defined advanced automation and analytics capabilities_ ].**

    <ins>Discussion</ins>: A properly resourced Security Operations Center (SOC) or Computer Incident Response Team (CIRT) may be overwhelmed by the volume of information generated by the proliferation of security tools and appliances unless it employs advanced automation and analytics to analyze the data. Advanced automation and analytics capabilities are typically supported by artificial intelligence concepts, including machine learning. Examples include Automated Threat Discovery and Response (which includes broad-based collection, context-based analysis, and adaptive response capabilities), automated workflow operations, and machine assisted decision tools. Note, however, that sophisticated adversaries may be able to extract information related to analytic parameters and retrain the machine learning to classify malicious activity as benign. Accordingly, machine learning is augmented by human monitoring to ensure that sophisticated adversaries are not able to conceal their activities.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [SP 800-30], [SP 800-39], [SP 800-161], [IR 8023], [IR 8062], [IR 8272].
