---
layout: default
title: CHAPTER ONE, INTRODUCTION 
nav_order: 100
---

**CHAPTER ONE**

# INTRODUCTION
{: .no_toc }

1. TOC
{:toc}

THE NEED TO PROTECT INFORMATION, SYSTEMS, ORGANIZATIONS, AND INDIVIDUALS

Modern information systems<sup>(1)</sup> can include a variety of computing platforms (e.g., industrial control systems, general purpose computing systems, cyber-physical systems, super computers, weapons systems, communications systems, environmental control systems, medical devices, embedded devices, sensors, and mobile devices such as smart phones and tablets). These platforms all share a common foundation—computers with complex hardware, software and firmware providing a capability that supports the essential mission and business functions of organizations. <sup>(2)</sup>

Security controls are the safeguards or countermeasures employed within a system or an organization to protect the confidentiality, integrity, and availability of the system and its information and to manage information security<sup>(3)</sup> risk. Privacy controls are the administrative, technical, and physical safeguards employed within a system or an organization to manage privacy risks and to ensure compliance with applicable privacy requirements.<sup>(4)</sup> Security and privacy controls are selected and implemented to satisfy security and privacy requirements levied on a system or organization. Security and privacy requirements are derived from applicable laws, executive orders, directives, regulations, policies, standards, and mission needs to ensure the confidentiality, integrity, and availability of information processed, stored, or transmitted and to manage risks to individual privacy.

The selection, design, and implementation of security and privacy controls<sup>(5)</sup> are important tasks that have significant implications for the operations<sup>(6)</sup> and assets of organizations as well as the welfare of individuals and the Nation. Organizations should answer several key questions when addressing information security and privacy controls:

- What security and privacy controls are needed to satisfy security and privacy requirements and to adequately manage mission/business risks or risks to individuals?
- Have the selected controls been implemented or is there a plan in place to do so?
- What is the required level of assurance (i.e., grounds for confidence) that the selected controls, as designed and implemented, are effective?<sup>(7)</sup>

****

<sup>(1)</sup> An _information system_ is a discrete set of information resources organized for the collection, processing, maintenance, use, sharing, dissemination, or disposition of information [OMB A-130].<br>
<sup>(2)</sup> The term _organization_ describes an entity of any size, complexity, or positioning within an organizational structure (e.g., a federal agency or, as appropriate, any of its operational elements).<br>
<sup>(3)</sup> The two terms _information security_ and _security_ are used synonymously in this publication.<br>
<sup>(4)</sup> [OMB A-130] defines _security_ and _privacy controls_.<br>
<sup>(5)</sup> Controls provide safeguards and countermeasures in systems security and privacy engineering processes to reduce risk during the system development life cycle.<br>
<sup>(6)</sup> Organizational operations include mission, functions, image, and reputation.<br>
<sup>(7)</sup> Security and privacy control effectiveness addresses the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the designated security and privacy requirements.<br>

***

The answers to these questions are not given in isolation but rather in the context of a risk management process for the organization that identifies, assesses, responds to, and monitors security and privacy risks arising from its information and systems on an ongoing basis.<sup>(8)</sup> The security and privacy controls in this publication are recommended for use by organizations to satisfy their information security and privacy requirements. The control catalog can be viewed as a toolbox containing a collection of safeguards, countermeasures, techniques, and processes to respond to security and privacy risks. The controls are employed as part of a well-defined risk management process that supports organizational information security and privacy programs. In turn, those information security and privacy programs lay the foundation for the success of the mission and business functions of the organization.

It is important that responsible officials understand the security and privacy risks that could adversely affect organizational operations and assets, individuals, other organizations, and the Nation.<sup>(9)</sup> These officials must also understand the current status of their security and privacy programs and the controls planned or in place to protect information, information systems, and organizations in order to make informed judgments and investments that respond to identified risks in an acceptable manner. The objective is to manage these risks through the selection and implementation of security and privacy controls.

## 1.1 PURPOSE AND APPLICABILITY

This publication establishes controls for systems and organizations. The controls can be implemented within any organization or system that processes, stores, or transmits information. The use of these controls is mandatory for federal information systems<sup>(10)</sup> in accordance with Office of Management and Budget (OMB) Circular A-130 [OMB A-130] and the provisions of the Federal Information Security Modernization Act<sup>(11)</sup> [FISMA], which requires the implementation of minimum controls to protect federal information and information systems.<sup>(12)</sup> This publication, along with other supporting NIST publications, is designed to help organizations identify the security and privacy controls needed to manage risk and to satisfy the security and privacy requirements in FISMA, the Privacy Act of 1974 [PRIVACT], OMB policies (e.g., [OMB A-130]), and designated Federal Information Processing Standards (FIPS), among others. It accomplishes this objective by providing a comprehensive and flexible catalog of security and privacy controls to meet current and future protection needs based on changing threats, vulnerabilities, requirements, and technologies. The publication also improves communication among organizations by providing a common lexicon that supports the discussion of security, privacy, and risk management concepts.

***

<sup>(8)</sup> The Risk Management Framework in [SP 800- 37 ] is an example of a comprehensive risk management process.<br>
<sup>(9)</sup> This includes risk to critical infrastructure and key resources described in [HSPD-7].<br>
<sup>(10)</sup> A _federal information system_ is an information system used or operated by an agency, a contractor of an agency, or another organization on behalf of an agency.<br>
<sup>(11)</sup> Information systems that have been designated as national security systems, as defined in 44 U.S.C., Section 3542, are not subject to the requirements in [FISMA]. However, the controls established in this publication may be selected for national security systems as otherwise required (e.g., the Privacy Act of 1974) or with the approval of federal officials exercising policy authority over such systems. [CNSSP 22] and [CNSSI 1253] provide guidance for national security systems. [DODI 8510.01] provides guidance for the Department of Defense.<br>
<sup>(12)</sup> While the controls established in this publication are mandatory for federal information systems and organizations, other organizations such as state, local, and tribal governments as well as private sector organizations are encouraged to consider using these guidelines, as appropriate. See [SP 800-53B] for federal control baselines.<br>

***

Finally, the controls are independent of the process employed to select those controls. The control selection process can be part of an organization-wide risk management process, a systems engineering process [SP 800-160-1 ],<sup>(13)</sup> the Risk Management Framework [SP 800-37], the Cybersecurity Framework [NIST CSF], or the Privacy Framework [NIST PF].<sup>(14)</sup> The control selection criteria can be guided and informed by many factors, including mission and business needs, stakeholder protection needs, threats, vulnerabilities, and requirements to comply with federal laws, executive orders, directives, regulations, policies, standards, and guidelines. The combination of a catalog of security and privacy controls and a risk-based control selection process can help organizations comply with stated security and privacy requirements, obtain adequate security for their information systems, and protect the privacy of individuals.

## 1.2 TARGET AUDIENCE

This publication is intended to serve a diverse audience, including:

- Individuals with system, information security, privacy, or risk management and oversight responsibilities, including authorizing officials, chief information officers, senior agency information security officers, and senior agency officials for privacy;
- Individuals with system development responsibilities, including mission owners, program managers, system engineers, system security engineers, privacy engineers, hardware and software developers, system integrators, and acquisition or procurement officials;
- Individuals with logistical or disposition-related responsibilities, including program managers, procurement officials, system integrators, and property managers;
- Individuals with security and privacy implementation and operations responsibilities, including mission or business owners, system owners, information owners or stewards, system administrators, continuity planners, and system security or privacy officers;
- Individuals with security and privacy assessment and monitoring responsibilities, including auditors, Inspectors General, system evaluators, control assessors, independent verifiers and validators, and analysts; and
- Commercial entities, including industry partners, producing component products and systems, creating security and privacy technologies, or providing services or capabilities that support information security or privacy.

***

<sup>(13)</sup> Risk management is an integral part of systems engineering, systems security engineering, and privacy engineering.<br>
<sup>(14)</sup> [OMB A-130] requires federal agencies to implement the NIST Risk Management Framework for the selection of controls for federal information systems. [EO 13800] requires federal agencies to implement the NIST _Framework for Improving Critical Infrastructure Cybersecurity_ to manage cybersecurity risk. The NIST frameworks are also available to nonfederal organizations as optional resources.<br>

***

## 1.3 ORGANIZATIONAL RESPONSIBILITIES

Managing security and privacy risks is a complex, multifaceted undertaking that requires:

- Well-defined security and privacy requirements for systems and organizations;
- The use of trustworthy information system components based on state-of-the-practice hardware, firmware, and software development and acquisition processes;
- Rigorous security and privacy planning and system development life cycle management;
- The application of system security and privacy engineering principles and practices to securely develop and integrate system components into information systems;
- The employment of security and privacy practices that are properly documented and integrated into and supportive of the institutional and operational processes of organizations; and
- Continuous monitoring of information systems and organizations to determine the ongoing effectiveness of controls, changes in information systems and environments of operation, and the state of security and privacy organization-wide.

Organizations continuously assess the security and privacy risks to organizational operations and assets, individuals, other organizations, and the Nation. Security and privacy risks arise from the planning and execution of organizational mission and business functions, placing information systems into operation, or continuing system operations. Realistic assessments of risk require a thorough understanding of the susceptibility to threats based on the specific vulnerabilities in information systems and organizations and the likelihood and potential adverse impacts of successful exploitations of such vulnerabilities by those threats.<sup>(15)</sup> Risk assessments also require an understanding of privacy risks.<sup>(16)</sup>

To address the organization’s concerns about assessment and determination of risk, security and privacy requirements are satisfied with the knowledge and understanding of the organizational risk management strategy.<sup>(17)</sup> The risk management strategy considers the cost, schedule, performance, and supply chain issues associated with the design, development, acquisition, deployment, operation, sustainment, and disposal of organizational systems. A risk management process is then applied to manage risk on an ongoing basis.<sup>(18)</sup>

The catalog of security and privacy controls can be effectively used to protect organizations, individuals, and information systems from traditional and advanced persistent threats and privacy risks arising from the processing of personally identifiable information (PII) in varied operational, environmental, and technical scenarios. The controls can be used to demonstrate compliance with a variety of governmental, organizational, or institutional security and privacy requirements. Organizations have the responsibility to select the appropriate security and privacy controls, to implement the controls correctly, and to demonstrate the effectiveness of the controls in satisfying security and privacy requirements.<sup>(19)</sup> Security and privacy controls can also be used in developing specialized baselines or overlays for unique or specialized missions or business applications, information systems, threat concerns, operational environments, technologies, or communities of interest.<sup>(20)</sup>

***

<sup>(15)</sup> [SP 800-30 ] provides guidance on the risk assessment process.<br>
<sup>(16)</sup> [IR 8062] introduces privacy risk concepts.<br>
<sup>(17)</sup> [SP 800-39 ] provides guidance on risk management processes and strategies.<br>
<sup>(18)</sup> [SP 800-37 ] provides a comprehensive risk management process.<br>
<sup>(19)</sup> [SP 800-53A] provides guidance on assessing the effectiveness of controls.<br>
<sup>(20)</sup> [SP 800-53B] provides guidance for tailoring security and privacy control baselines and for developing overlays to support the specific protection needs and requirements of stakeholders and their organizations.<br>

***

Organizational risk assessments are used, in part, to inform the security and privacy control selection process. The selection process results in an agreed-upon set of security and privacy controls addressing specific mission or business needs consistent with organizational risk tolerance.<sup>(21)</sup> The process preserves, to the greatest extent possible, the agility and flexibility that organizations need to address an increasingly sophisticated and hostile threat space, mission and business requirements, rapidly changing technologies, complex supply chains, and many types of operational environments.

## 1.4 RELATIONSHIP TO OTHER PUBLICATION

This publication defines controls to satisfy a diverse set of security and privacy requirements that have been levied on information systems and organizations and that are consistent with and complementary to other recognized national and international information security and privacy standards. To develop a broadly applicable and technically sound set of controls for information systems and organizations, many sources were considered during the development of this publication. These sources included requirements and controls from the manufacturing, defense, financial, healthcare, transportation, energy, intelligence, industrial control, and audit communities as well as national and international standards organizations. In addition, the controls in this publication are used by the national security community in publications such as Committee on National Security Systems (CNSS) Instruction No. 1253 [CNSSI 1253] to provide guidance specific to systems designated as national security systems. Whenever possible, the controls have been mapped to international standards to help ensure maximum usability and applicability.<sup>(22)</sup> The controls have also been mapped to the requirements for federal information systems included in [OMB A-130].<sup>(23)</sup> The relationship of this publication to other security, privacy, and risk management publications can be found at [FISMA IMP].

## 1.5 REVISIONS AND EXTENSIONS

The security and privacy controls described in this publication represent the state-of-the-practice protection measures for individuals, information systems, and organizations. The controls are reviewed and revised periodically to reflect the experience gained from using the controls; new or revised laws, executive orders, directives, regulations, policies, and standards; changing security and privacy requirements; emerging threats, vulnerabilities, attack and information processing methods; and the availability of new technologies.

The security and privacy controls in the control catalog are also expected to change over time as controls are withdrawn, revised, and added. In addition to the need for change, the need for stability is addressed by requiring that proposed modifications to security and privacy controls go through a rigorous and transparent public review process to obtain public and private sector feedback and to build a consensus for such change. The review process provides a technically sound, flexible, and stable set of security and privacy controls for the organizations that use the control catalog.

***

<sup>(21)</sup> Authorizing officials or their designated representatives, by accepting the security and privacy plans, agree to the security and privacy controls proposed to meet the security and privacy requirements for organizations and systems.<br>
<sup>(22)</sup> Mapping tables are available at [SP 800-53 RES].<br>
<sup>(23)</sup> [OMB A-130] establishes policy for the planning, budgeting, governance, acquisition, and management of federal information, personnel, equipment, funds, IT resources, and supporting infrastructure and services.<br>

***

## 1. 6 PUBLICATION ORGANIZATION

The remainder of this special publication is organized as follows:

- **Chapter Two** describes the fundamental concepts associated with security and privacy controls, including the structure of the controls, how the controls are organized in the consolidated catalog, control implementation approaches, the relationship between security and privacy controls, and trustworthiness and assurance.
- **Chapter Three** provides a consolidated catalog of security and privacy controls including a discussion section to explain the purpose of each control and to provide useful information regarding control implementation and assessment, a list of related controls to show the relationships and dependencies among controls, and a list of references to supporting publications that may be helpful to organizations.
- **References** , **Glossary** , **Acronyms** , and **Control Summaries** provide additional information on the use of security and privacy controls.<sup>(24)</sup>

***

<sup>(24)</sup> Unless otherwise stated, all references to NIST publications refer to the most recent version of those publications.<br>

