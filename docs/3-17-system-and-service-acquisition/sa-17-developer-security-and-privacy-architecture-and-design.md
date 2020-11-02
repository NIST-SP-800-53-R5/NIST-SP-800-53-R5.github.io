---
layout: page
title: -- SA-17 DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN 
parent: . 3.17 SYSTEM AND SERVICES ACQUISITION 
nav_order: 317170 
---

## SA-17 DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN

<ins>Control</ins>: Require the developer of the system, system component, or system service to produce a design specification and security and privacy architecture that:
* a. Is consistent with the organization’s security and privacy architecture that is an integral part the organization’s enterprise architecture;
* b. Accurately and completely describes the required security and privacy functionality, and the allocation of controls among physical and logical components; and
* c. Expresses how individual security and privacy functions, mechanisms, and services work together to provide required security and privacy capabilities and a unified approach to protection.

<ins>Discussion</ins>: Developer security and privacy architecture and design are directed at external developers, although they could also be applied to internal (in-house) development. In contrast, PL-8 is directed at internal developers to ensure that organizations develop a security and privacy architecture that is integrated with the enterprise architecture. The distinction between SA-17 and PL-8 is especially important when organizations outsource the development of systems, system components, or system services and when there is a requirement to demonstrate consistency with the enterprise architecture and security and privacy architecture of the organization. [ISO 15408-2], [ISO 15408-3], and [SP 800-160-1] provide information on security architecture and design, including formal policy models, security-relevant components, formal and informal correspondence, conceptually simple design, and structuring for least privilege and testing.
   
<ins>Related Controls</ins>: PL-2 , PL-8 , PM-7 , SA-3 , SA-4 , SA-8 , SC-7.

<ins>Control Enhancements</ins>:
   
* (1) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / FORMAL POLICY MODEL<br>
**Require the developer of the system, system component, or system service to:**
    * **(a) Produce, as an integral part of the development process, a formal policy model describing the [ _Assignment: organization-defined elements of organizational security and privacy policy_ ] to be enforced; and**
    * **(b) Prove that the formal policy model is internally consistent and sufficient to enforce the defined elements of the organizational security and privacy policy when implemented.**

    <ins>Discussion</ins>: Formal models describe specific behaviors or security and privacy policies using formal languages, thus enabling the correctness of those behaviors and policies to be formally proven. Not all components of systems can be modeled. Generally, formal specifications are scoped to the behaviors or policies of interest, such as nondiscretionary access control policies. Organizations choose the formal modeling language and approach based on the nature of the behaviors and policies to be described and the available tools.

    <ins>Related Controls</ins>: AC-3 , AC-4 , AC-25.
   
* (2) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / SECURITY-RELEVANT COMPONENTS<br>
**Require the developer of the system, system component, or system service to:**
    * **(a) Define security-relevant hardware, software, and firmware; and**
    * **(b) Provide a rationale that the definition for security-relevant hardware, software, and firmware is complete.**

    <ins>Discussion</ins>: The security-relevant hardware, software, and firmware represent the portion of the system, component, or service that is trusted to perform correctly to maintain required security properties.

    <ins>Related Controls</ins>: AC-25 , SA-5.
   
* (3) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / FORMAL CORRESPONDENCE<br>
**Require the developer of the system, system component, or system service to:**
    * **(a) Produce, as an integral part of the development process, a formal top-level specification that specifies the interfaces to security-relevant hardware, software, and firmware in terms of exceptions, error messages, and effects;**
    * **(b) Show via proof to the extent feasible with additional informal demonstration as necessary, that the formal top-level specification is consistent with the formal policy model;**
    * **(c) Show via informal demonstration, that the formal top-level specification completely covers the interfaces to security-relevant hardware, software, and firmware;**   
    * **(d) Show that the formal top-level specification is an accurate description of the implemented security-relevant hardware, software, and firmware; and**
    * **(e) Describe the security-relevant hardware, software, and firmware mechanisms not addressed in the formal top-level specification but strictly internal to the security-relevant hardware, software, and firmware.**

    <ins>Discussion</ins>: Correspondence is an important part of the assurance gained through modeling. It demonstrates that the implementation is an accurate transformation of the model, and that any additional code or implementation details that are present have no impact on the behaviors or policies being modeled. Formal methods can be used to show that the high- level security properties are satisfied by the formal system description, and that the formal system description is correctly implemented by a description of some lower level, including a hardware description. Consistency between the formal top-level specification and the formal policy models is generally not amenable to being fully proven. Therefore, a combination of formal and informal methods may be needed to demonstrate such consistency. Consistency between the formal top-level specification and the actual implementation may require the use of an informal demonstration due to limitations on the applicability of formal methods to prove that the specification accurately reflects the implementation. Hardware, software, and firmware mechanisms internal to security-relevant components include mapping registers and direct memory input and output.

    <ins>Related Controls</ins>: AC-3 , AC-4 , AC-25 , SA-4 , SA-5.
   
* (4) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / INFORMAL CORRESPONDENCE<br>
**Require the developer of the system, system component, or system service to:**
    * **(a) Produce, as an integral part of the development process, an informal descriptive top-level specification that specifies the interfaces to security-relevant hardware, software, and firmware in terms of exceptions, error messages, and effects;**
    * **(b) Show via [ _Selection: informal demonstration, convincing argument with formal methods as feasible_ ] that the descriptive top-level specification is consistent with the formal policy model;**
    * **(c) Show via informal demonstration, that the descriptive top-level specification completely covers the interfaces to security-relevant hardware, software, and firmware;**
    * **(d) Show that the descriptive top-level specification is an accurate description of the interfaces to security-relevant hardware, software, and firmware; and**
    * **(e) Describe the security-relevant hardware, software, and firmware mechanisms not addressed in the descriptive top-level specification but strictly internal to the security-relevant hardware, software, and firmware.**

    <ins>Discussion</ins>: Correspondence is an important part of the assurance gained through modeling. It demonstrates that the implementation is an accurate transformation of the model, and that additional code or implementation detail has no impact on the behaviors or policies being modeled. Consistency between the descriptive top-level specification (i.e., high- level/low-level design) and the formal policy model is generally not amenable to being fully proven. Therefore, a combination of formal and informal methods may be needed to show such consistency. Hardware, software, and firmware mechanisms strictly internal to security-relevant hardware, software, and firmware include mapping registers and direct memory input and output.

    <ins>Related Controls</ins>: AC-3 , AC-4 , AC-25 , SA-4 , SA-5.
   
* (5) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / CONCEPTUALLY SIMPLE DESIGN<br>
**Require the developer of the system, system component, or system service to:**   
    * **(a) Design and structure the security-relevant hardware, software, and firmware to use a complete, conceptually simple protection mechanism with precisely defined semantics; and**
    * **(b) Internally structure the security-relevant hardware, software, and firmware with specific regard for this mechanism.**

    <ins>Discussion</ins>: The principle of reduced complexity states that the system design is as simple and small as possible (see SA-8(7)). A small and simple design is easier to understand and analyze and is also less prone to error (see AC-25, SA-8(13)). The principle of reduced complexity applies to any aspect of a system, but it has particular importance for security due to the various analyses performed to obtain evidence about the emergent security property of the system. For such analyses to be successful, a small and simple design is essential. Application of the principle of reduced complexity contributes to the ability of system developers to understand the correctness and completeness of system security functions and facilitates the identification of potential vulnerabilities. The corollary of reduced complexity states that the simplicity of the system is directly related to the number of vulnerabilities it will contain. That is, simpler systems contain fewer vulnerabilities. An important benefit of reduced complexity is that it is easier to understand whether the security policy has been captured in the system design and that fewer vulnerabilities are likely to be introduced during engineering development. An additional benefit is that any such conclusion about correctness, completeness, and existence of vulnerabilities can be reached with a higher degree of assurance in contrast to conclusions reached in situations where the system design is inherently more complex.

    <ins>Related Controls</ins>: AC-25 , SA-8 , SC-3.
   
* (6) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / STRUCTURE FOR TESTING<br>
**Require the developer of the system, system component, or system service to structure security-relevant hardware, software, and firmware to facilitate testing.**

    <ins>Discussion</ins>: Applying the security design principles in [SP 800-160-1] promotes complete, consistent, and comprehensive testing and evaluation of systems, system components, and services. The thoroughness of such testing contributes to the evidence produced to generate an effective assurance case or argument as to the trustworthiness of the system, system component, or service.

    <ins>Related Controls</ins>: SA-5 , SA-11.
   
* (7) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / STRUCTURE FOR LEAST PRIVILEGE<br>
**Require the developer of the system, system component, or system service to structure security-relevant hardware, software, and firmware to facilitate controlling access with least privilege.**

    <ins>Discussion</ins>: The principle of least privilege states that each component is allocated sufficient privileges to accomplish its specified functions but no more (see SA-8(14)). Applying the principle of least privilege limits the scope of the component’s actions, which has two desirable effects. First, the security impact of a failure, corruption, or misuse of the system component results in a minimized security impact. Second, the security analysis of the component is simplified. Least privilege is a pervasive principle that is reflected in all aspects of the secure system design. Interfaces used to invoke component capability are available to only certain subsets of the user population, and component design supports a sufficiently fine granularity of privilege decomposition. For example, in the case of an audit mechanism, there may be an interface for the audit manager, who configures the audit settings; an interface for the audit operator, who ensures that audit data is safely collected and stored; and, finally, yet another interface for the audit reviewer, who only has a need to view the audit data that has been collected but no need to perform operations on that data.
   
    In addition to its manifestations at the system interface, least privilege can be used as a guiding principle for the internal structure of the system itself. One aspect of internal least privilege is to construct modules so that only the elements encapsulated by the module are directly operated upon by the functions within the module. Elements external to a module that may be affected by the module’s operation are indirectly accessed through interaction (e.g., via a function call) with the module that contains those elements. Another aspect of internal least privilege is that the scope of a given module or component includes only those system elements that are necessary for its functionality, and the access modes to the elements (e.g., read, write) are minimal.

    <ins>Related Controls</ins>: AC-5 , AC-6 , SA-8.
   
* (8) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / ORCHESTRATION<br>
**Design [ _Assignment: organization-defined critical systems or system components_ ] with coordinated behavior to implement the following capabilities: [ _Assignment: organization-defined capabilities, by system or component_ ].**

    <ins>Discussion</ins>: Security resources that are distributed, located at different layers or in different system elements, or are implemented to support different aspects of trustworthiness can interact in unforeseen or incorrect ways. Adverse consequences can include cascading failures, interference, or coverage gaps. Coordination of the behavior of security resources (e.g., by ensuring that one patch is installed across all resources before making a configuration change that assumes that the patch is propagated) can avert such negative interactions.

    <ins>Related Controls</ins>: None.
   
* (9) DEVELOPER SECURITY AND PRIVACY ARCHITECTURE AND DESIGN / DESIGN DIVERSITY<br>
**Use different designs for [ _Assignment: organization-defined critical systems or system components_ ] to satisfy a common set of requirements or to provide equivalent functionality.**

    <ins>Discussion</ins>: Design diversity is achieved by supplying the same requirements specification to multiple developers, each of whom is responsible for developing a variant of the system or system component that meets the requirements. Variants can be in software design, in hardware design, or in both hardware and a software design. Differences in the designs of the variants can result from developer experience (e.g., prior use of a design pattern), design style (e.g., when decomposing a required function into smaller tasks, determining what constitutes a separate task and how far to decompose tasks into sub-tasks), selection of libraries to incorporate into the variant, and the development environment (e.g., different design tools make some design patterns easier to visualize). Hardware design diversity includes making different decisions about what information to keep in analog form and what information to convert to digital form, transmitting the same information at different times, and introducing delays in sampling (temporal diversity). Design diversity is commonly used to support fault tolerance.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [ISO 15408-2], [ISO 15408-3], [SP 800-160-1].
