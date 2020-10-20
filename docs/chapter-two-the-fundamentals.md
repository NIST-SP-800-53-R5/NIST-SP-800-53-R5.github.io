---
layout: default
title: CHAPTER TWO, THE FUNDAMENTALS 
nav_order: 200
---

**CHAPTER TWO**

# THE FUNDAMENTALS 
{: .no_toc }
STRUCTURE, TYPE, AND ORGANIZATION OF SECURITY AND PRIVACY CONTROLS

1. TOC
{:toc}

This chapter presents the fundamental concepts associated with security and privacy controls, including the relationship between requirements and controls, the structure of controls, how controls are organized in the consolidated control catalog, the different control implementation approaches for information systems and organizations, the relationship between security and privacy controls, the importance of the concepts of trustworthiness and assurance for security and privacy controls, and the effects of the controls on achieving trustworthy, secure, and resilient systems.

## 2. 1 REQUIREMENTS AND CONTROLS

It is important to understand the relationship between requirements and controls. For federal information security and privacy policies, the term requirement is generally used to refer to information security and privacy obligations imposed on organizations. For example, [OMB A- 130] imposes information security and privacy requirements with which federal agencies must comply when managing information resources. The term requirement can also be used in a broader sense to refer to an expression of stakeholder protection needs for a particular system or organization. Stakeholder protection needs and the corresponding security and privacy requirements may be derived from many sources (e.g., laws, executive orders, directives, regulations, policies, standards, mission and business needs, or risk assessments). The term requirement, as used in this guideline, includes both legal and policy requirements, as well as an expression of the broader set of stakeholder protection needs that may be derived from other sources. All of these requirements, when applied to a system, help determine the necessary characteristics of the system—encompassing security, privacy, and assurance.<sup>25</sup>

Organizations may divide security and privacy requirements into more granular categories, depending on where the requirements are employed in the system development life cycle (SDLC) and for what purpose. Organizations may use the term capability requirement to describe a capability that the system or organization must provide to satisfy a stakeholder protection need. In addition, organizations may refer to system requirements that pertain to particular hardware, software, and firmware components of a system as specification requirements—that is, capabilities that implement all or part of a control and that may be assessed (i.e., as part of the verification, validation, testing, and evaluation processes). Finally, organizations may use the term statement of work requirements to refer to actions that must be performed operationally or during system development.

***

<sup>(25)</sup> The system characteristics that impact security and privacy vary and include the system type and function in terms of its primary purpose; the system make-up in terms of its technology, mechanical, physical, and human elements; the modes and states within which the system delivers its functions and services; the criticality or importance of the system and its constituent functions and services; the sensitivity of the data or information processed, stored, or transmitted; the consequence of loss, failure, or degradation relative to the ability of the system to execute correctly and to provide for its own protection (i.e., self-protection); and monetary or other value [SP 800-160-1].

***

Controls can be viewed as descriptions of the safeguards and protection capabilities appropriate for achieving the particular security and privacy objectives of the organization and reflecting the protection needs of organizational stakeholders. Controls are selected and implemented by the organization in order to satisfy the system requirements. Controls can include administrative, technical, and physical aspects. In some cases, the selection and implementation of a control may necessitate additional specification by the organization in the form of derived requirements or instantiated control parameter values. The derived requirements and control parameter values may be necessary to provide the appropriate level of implementation detail for particular controls within the SDLC.

## 2. 2 CONTROL STRUCTURE AND ORGANIZATION

Security and privacy controls described in this publication have a well-defined organization and structure. For ease of use in the security and privacy control selection and specification process, controls are organized into 20 families.<sup>26</sup> Each family contains controls that are related to the specific topic of the family. A two-character identifier uniquely identifies each control family (e.g., PS for Personnel Security). Security and privacy controls may involve aspects of policy, oversight, supervision, manual processes, and automated mechanisms that are implemented by systems or actions by individuals. Table 1 lists the security and privacy control families and their associated family identifiers.

###### TABLE 1: SECURITY AND PRIVACY CONTROL FAMILIES
<table>
  <tr>
    <td>
    </td>
    <td>
    </td>
    <td>
    </td>    
    <td>
    </td>
    <td>
    </td>
    <td>
    </td>
  </tr>
  <tr>
    <td style="background-color:#6790ab">
<span style="color:#000000">ID</span>
    </td>
    <td colspan="2" style="background-color:#6790ab">
<span style="color:#000000">FAMILY</span>
    </td>
    <td style="background-color:#6790ab">
<span style="color:#000000">ID</span>
    </td>
    <td colspan="2" style="background-color:#6790ab">
<span style="color:#000000">FAMILY</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Access Control</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PE</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Physical and Environmental Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Access Control</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PE</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Physical and Environmental Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Access Control</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PE</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Physical and Environmental Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Access Control</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PE</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Physical and Environmental Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Access Control</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PE</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Physical and Environmental Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AT</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Awareness and Training</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PL</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Planning</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">AU</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Audit and Accountability</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PM</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Program Management</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">CA</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Assessment, Authorization, and Monitoring</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PS</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Personnel Security</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">CM</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Configuration Management</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">PT</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">PII Processing and Transparency</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">CP</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Contingency Planning</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">RA</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Risk Assessment</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">IA</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Identification and Authentication</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">SA</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">System and Services Acquisition</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">IR</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Incident Response</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">SC</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">System and Communications Protection</span>
    </td>
  </tr>
  <tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">MA</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Maintenance</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">SI</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">System and Information Integrity</span>
    </td>
  </tr>
    <td style="background-color:#bad1e0">
<span style="color:#000000">MP</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Media Protection</span>
    </td>
    <td style="background-color:#bad1e0">
<span style="color:#000000">SR</span>
    </td>
    <td colspan="2" style="background-color:#bad1e0">
<span style="color:#000000">Supply Chain Risk Management</span>
    </td>
  </tr>
</table>

***

<sup>(26)</sup> Of the 20 control families in NIST SP 800-53, 17 are aligned with the minimum security requirements in [FIPS 200]. The Program Management (PM), PII Processing and Transparency (PT), and Supply Chain Risk Management (SR) families address enterprise-level program management, privacy, and supply chain risk considerations pertaining to federal mandates emergent since [FIPS 200].

***

Families of controls contain base controls and control enhancements, which are directly related to their base controls. Control enhancements either add functionality or specificity to a base control or increase the strength of a base control. Control enhancements are used in systems and environments of operation that require greater protection than the protection provided by the base control. The need for organizations to select and implement control enhancements is due to the potential adverse organizational or individual impacts or when organizations require additions to the base control functionality or assurance based on assessments of risk. The selection and implementation of control enhancements always requires the selection and implementation of the base control.

The families are arranged in alphabetical order, while the controls and control enhancements within each family are in numerical order. The order of the families, controls, and control enhancements does not imply any logical progression, level of prioritization or importance, or order in which the controls or control enhancements are to be implemented. Rather, it reflects the order in which they were included in the catalog. Control designations are not re-used when a control is withdrawn.

Security and privacy controls have the following structure: a base control section, a discussion section, a related controls section, a control enhancements section, and a references section. Figure 1 illustrates the structure of a typical control.

![FIGURE 1: CONTROL STRUCTURE](https://statics.bsafes.com/images/NIST-SP-800-53-R5-Fig-1.png)
###### FIGURE 1: CONTROL STRUCTURE

The control section prescribes a security or privacy capability to be implemented. Security and privacy capabilities are achieved by the activities or actions, automated or nonautomated, carried out by information systems and organizations. Organizations designate the responsibility for control development, implementation, assessment, and monitoring. Organizations have the flexibility to implement the controls selected in whatever manner that satisfies organizational mission or business needs consistent with law, regulation, and policy.

The _discussion_ section provides additional information about a control. Organizations can use the information as needed when developing, tailoring, implementing, assessing, or monitoring controls. The information provides important considerations for implementing controls based on mission or business requirements, operational environments, or assessments of risk. The additional information can also explain the purpose of controls and often includes examples. Control enhancements may also include a separate discussion section when the discussion information is applicable only to a specific control enhancement.

The _related controls_ section provides a list of controls from the control catalog that impact or support the implementation of a particular control or control enhancement, address a related security or privacy capability, or are referenced in the discussion section. Control enhancements are inherently related to their base control. Thus, related controls that are referenced in the base control are not repeated in the control enhancements. However, there may be related controls identified for control enhancements that are not referenced in the base control (i.e., the related control is only associated with the specific control enhancement). Controls may also be related to enhancements of other base controls. When a control is designated as a related control, a corresponding designation is made on that control in its source location in the catalog to illustrate the two-way relationship. Additionally, each control in a given family is inherently related to the -1 control (Policy and Procedures) in the same family. Therefore, the relationship between the -1 control and the other controls in the same family is not specified in the related controls section for each control.

The _control enhancements_ section provides statements of security and privacy capability that augment a base control. The control enhancements are numbered sequentially within each control so that the enhancements can be easily identified when selected to supplement the base control. Each control enhancement has a short subtitle to indicate the intended function or capability provided by the enhancement. In the AU-4 example, if the control enhancement is selected, the control designation becomes AU-4(1). The numerical designation of a control enhancement is used only to identify that enhancement within the control. The designation is not indicative of the strength of the control enhancement, level of protection, priority, degree of importance, or any hierarchical relationship among the enhancements. Control enhancements are not intended to be selected independently. That is, if a control enhancement is selected, then the corresponding base control is also selected and implemented.

The _references _section includes a list of applicable laws, policies, standards, guidelines, websites, and other useful references that are relevant to a specific control or control enhancement.<sup>(27)</sup> The references section also includes hyperlinks to publications for obtaining additional information for control development, implementation, assessment, and monitoring.

***

<sup>(27)</sup> References are provided to assist organizations in understanding and implementing the security and privacy controls and are not intended to be inclusive or complete.

***

For some controls, additional flexibility is provided by allowing organizations to define specific values for designated parameters associated with the controls. Flexibility is achieved as part of a tailoring process using assignment and selection operations embedded within the controls and enclosed by brackets. The assignment and selection operations give organizations the capability to customize controls based on organizational security and privacy requirements. In contrast to assignment operations which allow complete flexibility in the designation of parameter values, selection operations narrow the range of potential values by providing a specific list of items from which organizations choose.

Determination of the organization-defined parameters can evolve from many sources, including laws, executive orders, directives, regulations, policies, standards, guidance, and mission or business needs. Organizational risk assessments and risk tolerance are also important factors in determining the values for control parameters. Once specified by the organization, the values for the assignment and selection operations become a part of the control. Organization-defined control parameters used in the base controls also apply to the control enhancements associated with those controls. The implementation of the control is assessed for effectiveness against the completed control statement.

In addition to assignment and selection operations embedded in a control, additional flexibility is achieved through iteration and refinement actions. Iteration allows organizations to use a control multiple times with different assignment and selection values, perhaps being applied in different situations or when implementing multiple policies. For example, an organization may have multiple systems implementing a control but with different parameters established to address different risks for each system and environment of operation. Refinement is the process of providing additional implementation detail to a control. Refinement can also be used to narrow the scope of a control in conjunction with iteration to cover all applicable scopes (e.g., applying different authentication mechanisms to different system interfaces). The combination of assignment and selection operations and iteration and refinement actions when applied to controls provides the needed flexibility to allow organizations to satisfy a broad base of security and privacy requirements at the organization, mission and business process, and system levels of implementation.

> **SECURITY AS A DESIGN PROBLEM**<br>
> “Providing satisfactory security controls in a computer system is....a system design problem. A combination of hardware, software, communications, physical, personnel and administrative-procedural safeguards is required for comprehensive security....software safeguards alone are not sufficient.”<br>
> -- **The Ware Report**<br>
> _Defense Science Board Task Force on Computer Security, 1970_


## 2. 3 CONTROL IMPLEMENTATION APPROACHES

There are three approaches to implementing the controls in Chapter Three: (1) a common (inheritable) control implementation approach, (2) a system-specific control implementation approach, and (3) a hybrid control implementation approach. The control implementation approaches define the scope of applicability for the control, the shared nature or inheritability of the control, and the responsibility for control development, implementation, assessment, and authorization. Each control implementation approach has a specific objective and focus that helps organizations select the appropriate controls, implement the controls in an effective manner, and satisfy security and privacy requirements. A specific control implementation approach may achieve cost benefits by leveraging security and privacy capabilities across multiple systems and environments of operation.<sup>(28)</sup>

Common controls are controls whose implementation results in a capability that is inheritable by multiple systems or programs. A control is deemed inheritable when the system or program receives protection from the implemented control, but the control is developed, implemented, assessed, authorized, and monitored by an internal or external entity other than the entity responsible for the system or program. The security and privacy capabilities provided by common controls can be inherited from many sources, including mission or business lines, organizations, enclaves, environments of operation, sites, or other systems or programs. Implementing controls as common controls can introduce the risk of a single point of failure.

Many of the controls needed to protect organizational information systems—including many physical and environmental protection controls, personnel security controls, and incident response controls—are inheritable and, therefore, are good candidates for common control status. Common controls can also include technology-based controls, such as identification and authentication controls, boundary protection controls, audit and accountability controls, and access controls. The cost of development, implementation, assessment, authorization, and monitoring can be amortized across multiple systems, organizational elements, and programs using the common control implementation approach.

Controls not implemented as common controls are implemented as system-specific or hybrid controls. System-specific controls are the primary responsibility of the system owner and the authorizing official for a given system. Implementing system-specific controls can introduce risk if the control implementations are not interoperable with common controls. Organizations can implement a control as hybrid if one part of the control is common (inheritable) and the other part is system-specific. For example, an organization may implement control CP-2 using a predefined template for the contingency plan for all organizational information systems with individual system owners tailoring the plan for system-specific uses, where appropriate. The division of a hybrid control into its common (inheritable) and system-specific parts may vary by organization, depending on the types of information technologies employed, the approach used by the organization to manage its controls, and assignment of responsibilities. When a control is implemented as a hybrid control, the common control provider is responsible for ensuring the implementation, assessment, and monitoring of the common part of the hybrid control, and the system owner is responsible for ensuring the implementation, assessment, and monitoring of the system-specific part of the hybrid control. Implementing controls as hybrid controls can introduce risk if the responsibility for the implementation and ongoing management of the common and system-specific parts of the controls is unclear.

***

<sup>(28)</sup> [SP 800-37 ] provides additional guidance on control implementation approaches (formerly referred to as control designations) and how the different approaches are used in the _Risk Management Framework_.

The determination as to the appropriate control implementation approach (i.e., common, hybrid, or system-specific) is context-dependent. The control implementation approach cannot be determined to be common, hybrid, or system-specific simply based on the language of the control. Identifying the control implementation approach can result in significant savings to organizations in implementation and assessment costs and a more consistent application of the controls organization-wide. Typically, the identification of the control implementation approach is straightforward. However, the implementation takes significant planning and coordination.

Planning for the implementation approach of a control (i.e., common, hybrid, or system-specific) is best carried out early in the system development life cycle and coordinated with the entities providing the control [SP 800-37]. Similarly, if a control is to be inheritable, coordination is required with the inheriting entity to ensure that the control meets its needs. This is especially important given the nature of control parameters. An inheriting entity cannot assume that controls are the same and mitigate the appropriate risk to the system just because the control identifiers (e.g., AC-1) are the same. It is essential to examine the control parameters (e.g., assignment or selection operations) when determining if a common control is adequate to mitigate system-specific risks.

## 2. 4 SECURITY AND PRIVACY CONTROLS

The selection and implementation of security and privacy controls reflect the objectives of information security and privacy programs and how those programs manage their respective risks. Depending on the circumstances, these objectives and risks can be independent or overlapping. Federal information security programs are responsible for protecting information and information systems from unauthorized access, use, disclosure, disruption, modification, or destruction (i.e., unauthorized activity or system behavior) to provide confidentiality, integrity, and availability. Those programs are also responsible for managing security risk and for ensuring compliance with applicable security requirements. Federal privacy programs are responsible for managing risks to individuals associated with the creation, collection, use, processing, storage, maintenance, dissemination, disclosure, or disposal (collectively referred to as “processing”) of personally identifiable information (PII) and for ensuring compliance with applicable privacy requirements.<sup>(29)</sup> When a system processes PII, the information security program and the privacy program have a shared responsibility for managing the security risks for the PII in the system. Due to this overlap in responsibilities, the controls that organizations select to manage these security risks will generally be the same regardless of their designation as security or privacy controls in control baselines or program or system plans.

There also may be circumstances in which the selection and/or implementation of the control or control enhancement affects the ability of a program to achieve its objectives and manage its respective risks. The control discussion section may highlight specific security and/or privacy considerations so that organizations can take these considerations into account as they determine the most effective method to implement the control. However, these considerations are not exhaustive.

***

<sup>(29)</sup> Privacy programs may also choose to consider the risks to individuals that may arise from their interactions with information systems, where the processing of personally identifiable information may be less impactful than the effect that the system has on individuals’ behavior or activities. Such effects would constitute risks to individual autonomy, and organizations may need to take steps to manage those risks in addition to information security and privacy risks.

For example, an organization might select AU-3 (Content of Audit Records) to support monitoring for unauthorized access to an information asset that does not include PII. Since the potential loss of confidentiality of the information asset does not affect privacy, security objectives are the primary driver for the selection of the control. However, the implementation of the control with respect to monitoring for unauthorized access could involve the processing of PII which may result in privacy risks and affect privacy program objectives. The discussion section in AU-3 includes privacy risk considerations so that organizations can take those considerations into account as they determine the best way to implement the control. Additionally, the control enhancement AU-3(3) (Limit Personally Identifiable Information Elements) could be selected to support managing these privacy risks.

Due to permutations in the relationship between information security and privacy program objectives and risk management, there is a need for close collaboration between programs to select and implement the appropriate controls for information systems processing PII. Organizations consider how to promote and institutionalize collaboration between the two programs to ensure that the objectives of both disciplines are met and risks are appropriately managed. <sup>(30)</sup>

## 2. 5 TRUSTWORTHINESS AND ASSURANCE

The trustworthiness of systems, system components, and system services is an important part of the risk management strategies developed by organizations.<sup>(31)</sup> Trustworthiness, in this context, means worthy of being trusted to fulfill whatever requirements may be needed for a component, subsystem, system, network, application, mission, business function, enterprise, or other entity.<sup>(32)</sup> Trustworthiness requirements can include attributes of reliability, dependability, performance, resilience, safety, security, privacy, and survivability under a range of potential adversity in the form of disruptions, hazards, threats, and privacy risks. Effective measures of trustworthiness are meaningful only to the extent that the requirements are complete, well- defined, and can be accurately assessed.

Two fundamental concepts that affect the trustworthiness of systems are functionality and assurance. Functionality is defined in terms of the security and privacy features, functions, mechanisms, services, procedures, and architectures implemented within organizational systems and programs and the environments in which those systems and programs operate. Assurance is the measure of confidence that the system functionality is implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security and privacy requirements for the system—thus possessing the capability to accurately mediate and enforce established security and privacy policies.

In general, the task of providing meaningful assurance that a system is likely to do what is expected of it can be enhanced by techniques that simplify or narrow the analysis by, for example, increasing the discipline applied to the system architecture, software design, specifications, code style, and configuration management. Security and privacy controls address functionality and assurance. Certain controls focus primarily on functionality while other controls focus primarily on assurance. Some controls can support functionality and assurance.

***

<sup>(30)</sup> Resources to support information security and privacy program collaboration are available at [SP 800-53 RES].
<sup>(31)</sup> [SP 800-160-1] provides guidance on systems security engineering and the application of security design principles to achieve trustworthy systems.
<sup>(32)</sup> See [NEUM04].

Organizations can select assurance-related controls to define system development activities, generate evidence about the functionality and behavior of the system, and trace the evidence to the system elements that provide such functionality or exhibit such behavior. The evidence is used to obtain a degree of confidence that the system satisfies the stated security and privacy requirements while supporting the organization’s mission and business functions. Assurance- related controls are identified in the control summary tables in Appendix C.

**`EVIDENCE OF CONTROL IMPLEMENTATION`**<br>
`During control selection and implementation, it is important for organizations to consider the evidence (e.g., artifacts, documentation) that will be needed to support current and future control assessments. Such assessments help determine whether the controls are implemented correctly, operating as intended, and satisfying security and privacy policies—thus, providing essential information for senior leaders to make informed risk-based decisions.`

