---
layout: page
title: -- SR-4 PROVENANCE 
parent: . 3.20 SUPPLY CHAIN RISK MANAGEMENT
nav_order: 32040 
---

## SR-4 PROVENANCE

<ins>Control</ins>: Document, monitor, and maintain valid provenance of the following systems, system components, and associated data: [ _Assignment: organization-defined systems, system components, and associated data_ ].

<ins>Discussion</ins>: Every system and system component has a point of origin and may be changed throughout its existence. Provenance is the chronology of the origin, development, ownership, location, and changes to a system or system component and associated data. It may also include personnel and processes used to interact with or make modifications to the system, component, or associated data. Organizations consider developing procedures (see SR-1) for allocating responsibilities for the creation, maintenance, and monitoring of provenance for systems and system components; transferring provenance documentation and responsibility between organizations; and preventing and monitoring for unauthorized changes to the provenance records. Organizations have methods to document, monitor, and maintain valid provenance baselines for systems, system components, and related data. These actions help track, assess, and document any changes to the provenance, including changes in supply chain elements or configuration, and help ensure non-repudiation of provenance information and the provenance change records. Provenance considerations are addressed throughout the system development life cycle and incorporated into contracts and other arrangements, as appropriate.

<ins>Related Controls</ins>: CM-8 , MA-2 , MA-6 , RA-9 , SA-3 , SA-8 , SI-4.
   
<ins>Control Enhancements</ins>:
   
* (1) PROVENANCE / IDENTITY<br>
**Establish and maintain unique identification of the following supply chain elements, processes, and personnel associated with the identified system and critical system components: [ _Assignment: organization-defined supply chain elements, processes, and personnel associated with organization-defined systems and critical system components_ ].**

    <ins>Discussion</ins>: Knowing who and what is in the supply chains of organizations is critical to gaining visibility into supply chain activities. Visibility into supply chain activities is also important for monitoring and identifying high-risk events and activities. Without reasonable visibility into supply chains elements, processes, and personnel, it is very difficult for organizations to understand and manage risk and reduce their susceptibility to adverse events. Supply chain elements include organizations, entities, or tools used for the research and development, design, manufacturing, acquisition, delivery, integration, operations, maintenance, and disposal of systems and system components. Supply chain processes include development processes for hardware, software, and firmware; shipping and handling procedures; configuration management tools, techniques, and measures to maintain provenance; personnel and physical security programs; or other programs, processes, or procedures associated with the production and distribution of supply chain elements. Supply chain personnel are individuals with specific roles and responsibilities related to the secure the research and development, design, manufacturing, acquisition, delivery, integration, operations and maintenance, and disposal of a system or system component. Identification methods are sufficient to support an investigation in case of a supply chain change (e.g. if a supply company is purchased), compromise, or event.

    <ins>Related Controls</ins>: IA-2 , IA-8 , PE-16.
   
* (2) PROVENANCE / TRACK AND TRACE<br>
**Establish and maintain unique identification of the following systems and critical system components for tracking through the supply chain: [ _Assignment: organization-defined systems and critical system components_ ].**

    <ins>Discussion</ins>: Tracking the unique identification of systems and system components during development and transport activities provides a foundational identity structure for the establishment and maintenance of provenance. For example, system components may be labeled using serial numbers or tagged using radio-frequency identification tags. Labels and tags can help provide better visibility into the provenance of a system or system component. A system or system component may have more than one unique identifier. Identification methods are sufficient to support a forensic investigation after a supply chain compromise or event.

    <ins>Related Controls</ins>: IA-2 , IA-8 , PE-16 , PL-2.
   
* (3) PROVENANCE / VALIDATE AS GENUINE AND NOT ALTERED<br>
**Employ the following controls to validate that the system or system component received is genuine and has not been altered: [ _Assignment: organization-defined controls_ ].**

    <ins>Discussion</ins>: For many systems and system components, especially hardware, there are technical means to determine if the items are genuine or have been altered, including optical and nanotechnology tagging, physically unclonable functions, side-channel analysis, cryptographic hash verifications or digital signatures, and visible anti-tamper labels or stickers. Controls can also include monitoring for out of specification performance, which can be an indicator of tampering or counterfeits. Organizations may leverage supplier and contractor processes for validating that a system or component is genuine and has not been altered and for replacing a suspect system or component. Some indications of tampering may be visible and addressable before accepting delivery, such as inconsistent packaging, broken seals, and incorrect labels. When a system or system component is suspected of being altered or counterfeit, the supplier, contractor, or original equipment manufacturer may be able to replace the item or provide a forensic capability to determine the origin of the counterfeit or altered item. Organizations can provide training to personnel on how to identify suspicious system or component deliveries.

    <ins>Related Controls</ins>: AT-3 , SR-9 , SR-10 , SR-11.
   
* (4) PROVENANCE / SUPPLY CHAIN INTEGRITY — PEDIGREE<br>
**Employ [ _Assignment: organization-defined controls_ ] and conduct [ _Assignment: organization-defined analysis_ ] to ensure the integrity of the system and system components by validating the internal composition and provenance of critical or mission-essential technologies, products, and services.**

    <ins>Discussion</ins>: Authoritative information regarding the internal composition of system components and the provenance of technology, products, and services provides a strong basis for trust. The validation of the internal composition and provenance of technologies, products, and services is referred to as the pedigree. For microelectronics, this includes material composition of components. For software this includes the composition of open- source and proprietary code, including the version of the component at a given point in time. Pedigrees increase the assurance that the claims suppliers assert about the internal composition and provenance of the products, services, and technologies they provide are valid. The validation of the internal composition and provenance can be achieved by various evidentiary artifacts or records that manufacturers and suppliers produce during the research and development, design, manufacturing, acquisition, delivery, integration, operations and maintenance, and disposal of technology, products, and services. Evidentiary artifacts include, but are not limited to, software identification (SWID) tags, software component inventory, the manufacturers’ declarations of platform attributes (e.g., serial numbers, hardware component inventory), and measurements (e.g., firmware hashes) that are tightly bound to the hardware itself.

    <ins>Related Controls</ins>: RA-3.

<ins>References</ins>: [FASC18], [41 CFR 201], [EO 13873], [ISO 27036], [ISO 20243], [SP 800-160-1 ], [SP
800-161 ], [IR 7622], [IR 8112], [IR 8272].
