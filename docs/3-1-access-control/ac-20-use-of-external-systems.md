---
layout: default
title:  -- AC-20 USE OF EXTERNAL SYSTEMS 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15200
---

## AC-20 USE OF EXTERNAL SYSTEMS

<ins>Control</ins>:
* a. [ _Selection (one or more): Establish [ Assignment: organization-defined terms and conditions ] ; Identify [ Assignment: organization-defined controls asserted to be implemented on external systems ]_], consistent with the trust relationships established with other organizations owning, operating, and/or maintaining external systems, allowing authorized individuals to:

    * 1 . Access the system from external systems; and
    * 2 . Process, store, or transmit organization-controlled information using external systems; or

* b. Prohibit the use of [ _Assignment: organizationally-defined types of external systems_ ].

<ins>Discussion</ins>: External systems are systems that are used by but not part of organizational systems and for which the organization has no direct control over the implementation of required controls or the assessment of control effectiveness. External systems include personally owned systems, components, or devices; privately owned computing and communications devices in commercial or public facilities; systems owned or controlled by nonfederal organizations; systems managed by contractors; and federal information systems that are not owned by, operated by, or under the direct supervision or authority of the organization. External systems also include systems owned or operated by other components within the same organization and systems within the organization with different authorization boundaries. Organizations have the option to prohibit the use of any type of external system or prohibit the use of specified types of external systems, (e.g., prohibit the use of any external system that is not organizationally owned or prohibit the use of personally-owned systems).

For some external systems (i.e., systems operated by other organizations), the trust relationships that have been established between those organizations and the originating organization may be such that no explicit terms and conditions are required. Systems within these organizations may not be considered external. These situations occur when, for example, there are pre-existing information exchange agreements (either implicit or explicit) established between organizations or components or when such agreements are specified by applicable laws, executive orders, directives, regulations, policies, or standards. Authorized individuals include organizational personnel, contractors, or other individuals with authorized access to organizational systems and over which organizations have the authority to impose specific rules of behavior regarding system access. Restrictions that organizations impose on authorized individuals need not be uniform, as the restrictions may vary depending on trust relationships between organizations. Therefore, organizations may choose to impose different security restrictions on contractors than on state, local, or tribal governments.

External systems used to access public interfaces to organizational systems are outside the scope of AC-20. Organizations establish specific terms and conditions for the use of external systems in accordance with organizational security policies and procedures. At a minimum, terms and conditions address the specific types of applications that can be accessed on organizational systems from external systems and the highest security category of information that can be processed, stored, or transmitted on external systems. If the terms and conditions with the owners of the external systems cannot be established, organizations may impose restrictions on organizational personnel using those external systems.

<ins>Related Controls</ins>: AC-2, AC-3, AC-17, AC-19, CA-3, PL-2, PL-4, SA-9, SC-7.

<ins>Control Enhancements</ins>:

* (1) USE OF EXTERNAL SYSTEMS / LIMITS ON AUTHORIZED USE<br>
**Permit authorized individuals to use an external system to access the system or to process,**
**store, or transmit organization-controlled information only after:**
    * **(a) Verification of the implementation of controls on the external system as specified in the organization’s security and privacy policies and security and privacy plans; or**
    * **(b) Retention of approved system connection or processing agreements with the organizational entity hosting the external system.**

    <ins>Discussion</ins>: Limiting authorized use recognizes circumstances where individuals using external systems may need to access organizational systems. Organizations need assurance that the external systems contain the necessary controls so as not to compromise, damage, or otherwise harm organizational systems. Verification that the required controls have been implemented can be achieved by external, independent assessments, attestations, or other means, depending on the confidence level required by organizations.

    <ins>Related Controls</ins>: CA-2.

* (2) USE OF EXTERNAL SYSTEMS / PORTABLE STORAGE DEVICES — RESTRICTED USE<br>
**Restrict the use of organization-controlled portable storage devices by authorized individuals on external systems using [ _Assignment: organization-defined restrictions_ ].**

    <ins>Discussion</ins>: Limits on the use of organization-controlled portable storage devices in external systems include restrictions on how the devices may be used and under what conditions the devices may be used.

    <ins>Related Controls</ins>: MP-7, SC-41.

* (3) USE OF EXTERNAL SYSTEMS / NON-ORGANIZATIONALLY OWNED SYSTEMS — RESTRICTED USE<br>
**Restrict the use of non-organizationally owned systems or system components to process, store, or transmit organizational information using [ _Assignment: organization-defined restrictions_ ].**

    <ins>Discussion</ins>: Non-organizationally owned systems or system components include systems or system components owned by other organizations as well as personally owned devices. There are potential risks to using non-organizationally owned systems or components. In some cases, the risk is sufficiently high as to prohibit such use (see AC-20(6)). In other cases, the use of such systems or system components may be allowed but restricted in some way. Restrictions include requiring the implementation of approved controls prior to authorizing the connection of non-organizationally owned systems and components; limiting access to types of information, services, or applications; using virtualization techniques to limit processing and storage activities to servers or system components provisioned by the organization; and agreeing to the terms and conditions for usage. Organizations consult with the Office of the General Counsel regarding legal issues associated with using personally owned devices, including requirements for conducting forensic analyses during investigations after an incident.

    <ins>Related Controls</ins>: None.

* (4) USE OF EXTERNAL SYSTEMS / NETWORK ACCESSIBLE STORAGE DEVICES — PROHIBITED USE<br>
**Prohibit the use of [ _Assignment: organization-defined network accessible storage devices_ ] in external systems.**

    <ins>Discussion</ins>: Network-accessible storage devices in external systems include online storage devices in public, hybrid, or community cloud-based systems.

    <ins>Related Controls</ins>: None.

* (5) USE OF EXTERNAL SYSTEMS / PORTABLE STORAGE DEVICES — PROHIBITED USE<br>
**Prohibit the use of organization-controlled portable storage devices by authorized individuals on external systems.**

    <ins>Discussion</ins>: Limits on the use of organization-controlled portable storage devices in external systems include a complete prohibition of the use of such devices. Prohibiting such use is enforced using technical methods and/or nontechnical (i.e., process-based) methods.

    <ins>Related Controls</ins>: MP-7, PL-4, PS-6, SC-41.

<ins>References</ins>: [FIPS 199], [SP 800-171 ], [ SP 800-172 ].
