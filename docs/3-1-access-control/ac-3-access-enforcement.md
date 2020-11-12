---
layout: default
title:  -- AC-3 ACCESS ENFORCEMENT 
parent: . 3.1 ACCESS CONTROL 
nav_order: 1530
---

## AC-3 ACCESS ENFORCEMENT

<ins>Control:</ins> Enforce approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

<ins>Discussion</ins>: Access control policies control access between active entities or subjects (i.e., users or processes acting on behalf of users) and passive entities or objects (i.e., devices, files, records, domains) in organizational systems. In addition to enforcing authorized access at the system level and recognizing that systems can host many applications and services in support of mission and business functions, access enforcement mechanisms can also be employed at the application and service level to provide increased information security and privacy. In contrast to logical access controls that are implemented within the system, physical access controls are addressed by the controls in the Physical and Environmental Protection (PE) family.

<ins>Related Controls</ins>: AC-2, AC-4, AC-5, AC-6, AC-16, AC-17, AC-18, AC-19, AC-20, AC-21, AC-22, AC- 24, AC-25, AT-2, AT-3, AU-9, CA-9, CM-5, CM-11, IA-2, IA-5, IA-6, IA-7, IA-11, MA-3, MA-4, MA-5, MP-4, PM-2, PS-3, PT-2, PT-3, SA-17, SC-2, SC-3, SC-4, SC-12, SC-13, SC-28, SC-31, SC-34, SI-4, SI-8.

<ins>Control Enhancements</ins>:
* (1) ACCESS ENFORCEMENT / RESTRICTED ACCESS TO PRIVILEGED FUNCTIONS
[Withdrawn: Incorporated into AC-6.]

* (2) ACCESS ENFORCEMENT / DUAL AUTHORIZATION<br>
    **Enforce dual authorization for [ _Assignment: organization-defined privileged commands and/or other organization-defined actions_ ].**<br>

    <ins>Discussion</ins>: Dual authorization, also known as two-person control, reduces risk related to insider threats. Dual authorization mechanisms require the approval of two authorized individuals to execute. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals. Organizations consider the risk associated with implementing dual authorization mechanisms when immediate responses are necessary to ensure public and environmental safety.<br>

    <ins>Related Controls</ins>: CP-9, MP-6.<br>

* (3) ACCESS ENFORCEMENT / MANDATORY ACCESS CONTROL<br>
**Enforce [ _Assignment: organization-defined mandatory access control policy_ ] over the set of covered subjects and objects specified in the policy, and where the policy:**<br>
    * **(a) Is uniformly enforced across the covered subjects and objects within the system;**<br>
    * **(b) Specifies that a subject that has been granted access to information is constrained from doing any of the following;**<br>
        * **(1) Passing the information to unauthorized subjects or objects;**<br>
        * **(2) Granting its privileges to other subjects;**<br>
        * **(3) Changing one or more security attributes (specified by the policy) on subjects, objects, the system, or system components;**<br>
        * **(4) Choosing the security attributes and attribute values (specified by the policy) to be associated with newly created or modified objects; and**<br>
        * **(5) Changing the rules governing access control; and**<br>
    * **(c) Specifies that [ Assignment: organization-defined subjects ] may explicitly be granted [ _Assignment: organization-defined privileges_ ] such that they are not limited by any defined subset (or all) of the above constraints.**<br>

    <ins>Discussion</ins>: Mandatory access control is a type of nondiscretionary access control. Mandatory access control policies constrain what actions subjects can take with information obtained from objects for which they have already been granted access. This prevents the subjects from passing the information to unauthorized subjects and objects. Mandatory access control policies constrain actions that subjects can take with respect to the propagation of access control privileges; that is, a subject with a privilege cannot pass that privilege to other subjects. The policy is uniformly enforced over all subjects and objects to which the system has control. Otherwise, the access control policy can be circumvented. This enforcement is provided by an implementation that meets the reference monitor concept as described in AC-25. The policy is bounded by the system (i.e., once the information is passed outside of the control of the system, additional means may be required to ensure that the constraints on the information remain in effect).

    The trusted subjects described above are granted privileges consistent with the concept of
least privilege (see AC-6). Trusted subjects are only given the minimum privileges necessary
for satisfying organizational mission/business needs relative to the above policy. The control
is most applicable when there is a mandate that establishes a policy regarding access to
controlled unclassified information or classified information and some users of the system
are not authorized access to all such information resident in the system. Mandatory access
control can operate in conjunction with discretionary access control as described in AC-3(4).
A subject constrained in its operation by mandatory access control policies can still operate
under the less rigorous constraints of AC-3(4), but mandatory access control policies take
precedence over the less rigorous constraints of AC-3(4). For example, while a mandatory
access control policy imposes a constraint that prevents a subject from passing information
to another subject operating at a different impact or classification level, AC-3(4) permits the
subject to pass the information to any other subject with the same impact or classification
level as the subject. Examples of mandatory access control policies include the Bell-LaPadula
policy to protect confidentiality of information and the Biba policy to protect the integrity of
information.

    <ins>Related Controls</ins>: SC-7.

* (4) ACCESS ENFORCEMENT / DISCRETIONARY ACCESS CONTROL<br>
**Enforce [ _Assignment: organization-defined discretionary access control policy_ ] over the set of covered subjects and objects specified in the policy, and where the policy specifies that a subject that has been granted access to information can do one or more of the following:**<br>

    * **(a) Pass the information to any other subjects or objects;**<br>
    * **(b) Grant its privileges to other subjects;**<br>
    * **(c) Change security attributes on subjects, objects, the system, or the system’s components;**<br>
    * **(d) Choose the security attributes to be associated with newly created or revised objects; or**<br>
    * **(e) Change the rules governing access control.**<br>

    <ins>Discussion</ins>: When discretionary access control policies are implemented, subjects are not constrained with regard to what actions they can take with information for which they have already been granted access. Thus, subjects that have been granted access to information are not prevented from passing the information to other subjects or objects (i.e., subjects have the discretion to pass). Discretionary access control can operate in conjunction with mandatory access control as described in AC-3(3) and AC-3(15). A subject that is constrained in its operation by mandatory access control policies can still operate under the less rigorous constraints of discretionary access control. Therefore, while AC-3(3) imposes constraints that prevent a subject from passing information to another subject operating at a different impact or classification level, AC-3(4) permits the subject to pass the information to any subject at the same impact or classification level. The policy is bounded by the system. Once the information is passed outside of system control, additional means may be required to ensure that the constraints remain in effect. While traditional definitions of discretionary access control require identity-based access control, that limitation is not required for this particular use of discretionary access control.<br>

    <ins>Related Controls</ins>: None.<br>

* (5) ACCESS ENFORCEMENT / SECURITY-RELEVANT INFORMATION<br>
**Prevent access to [ _Assignment: organization-defined security-relevant information_ ] except during secure, non-operable system states.**<br>

    <ins>Discussion</ins>: Security-relevant information is information within systems that can potentially impact the operation of security functions or the provision of security services in a manner that could result in failure to enforce system security and privacy policies or maintain the separation of code and data. Security-relevant information includes access control lists, filtering rules for routers or firewalls, configuration parameters for security services, and cryptographic key management information. Secure, non-operable system states include the times in which systems are not performing mission or business-related processing, such as when the system is offline for maintenance, boot-up, troubleshooting, or shut down.<br>
    
    <ins>Related Controls</ins>: CM-6, SC-39.<br>

* (6) ACCESS ENFORCEMENT / PROTECTION OF USER AND SYSTEM INFORMATION<br>
[Withdrawn: Incorporated into MP-4 and SC-28.]

* (7) ACCESS ENFORCEMENT / ROLE-BASED ACCESS CONTROL<br>
**Enforce a role-based access control policy over defined subjects and objects and control access based upon [ _Assignment: organization-defined roles and users authorized to assume such roles_ ].**<br>

    <ins>Discussion</ins>: Role-based access control (RBAC) is an access control policy that enforces access to objects and system functions based on the defined role (i.e., job function) of the subject. Organizations can create specific roles based on job functions and the authorizations (i.e., privileges) to perform needed operations on the systems associated with the organization-defined roles. When users are assigned to specific roles, they inherit the authorizations or privileges defined for those roles. RBAC simplifies privilege administration for organizations because privileges are not assigned directly to every user (which can be a large number of individuals) but are instead acquired through role assignments. RBAC can also increase privacy and security risk if individuals assigned to a role are given access to information beyond what they need to support organizational missions or business functions. RBAC can be implemented as a mandatory or discretionary form of access control. For organizations implementing RBAC with mandatory access controls, the requirements in AC-3(3) define the scope of the subjects and objects covered by the policy.<br>

    <ins>Related Controls</ins>: None.<br>

* (8) ACCESS ENFORCEMENT / REVOCATION OF ACCESS AUTHORIZATIONS<br>
**Enforce the revocation of access authorizations resulting from changes to the security attributes of subjects and objects based on [ _Assignment: organization-defined rules governing the timing of revocations of access authorizations_ ].**<br>

    <ins>Discussion</ins>: Revocation of access rules may differ based on the types of access revoked. For example, if a subject (i.e., user or process acting on behalf of a user) is removed from a group, access may not be revoked until the next time the object is opened or the next time the subject attempts to access the object. Revocation based on changes to security labels may take effect immediately. Organizations provide alternative approaches on how to make revocations immediate if systems cannot provide such capability and immediate revocation is necessary.<br>

    <ins>Related Controls</ins>: None.

* (9) ACCESS ENFORCEMENT | CONTROLLED RELEASE<br>
**Release information outside of the system only if:**
    * **(a) The receiving [ _Assignment: organization-defined system or system component_ ] provides [ _Assignment: organization-defined controls_ ]; and**<br>
    * **(b) [ _Assignment: organization-defined controls_ ] are used to validate the appropriateness of the information designated for release.**<br>

    <ins>Discussion</ins>: Organizations can only directly protect information when it resides within the system. Additional controls may be needed to ensure that organizational information is adequately protected once it is transmitted outside of the system. In situations where the system is unable to determine the adequacy of the protections provided by external entities, as a mitigating control, organizations procedurally determine whether the external systems are providing adequate controls. The means used to determine the adequacy of controls provided by external systems include conducting periodic assessments (inspections/tests), establishing agreements between the organization and its counterpart organizations, or some other process. The means used by external entities to protect the information received need not be the same as those used by the organization, but the means employed are sufficient to provide consistent adjudication of the security and privacy policy to protect the information and individuals’ privacy.

    Controlled release of information requires systems to implement technical or procedural means to validate the information prior to releasing it to external systems. For example, if the system passes information to a system controlled by another organization, technical means are employed to validate that the security and privacy attributes associated with the exported information are appropriate for the receiving system. Alternatively, if the system passes information to a printer in organization-controlled space, procedural means can be employed to ensure that only authorized individuals gain access to the printer.<br>

    <ins>Related Controls</ins>: CA-3, PT-7, PT-8, SA-9, SC-16

* (10) ACCESS ENFORCEMENT / AUDITED OVERRIDE OF ACCESS CONTROL MECHANISMS<br>
**Employ an audited override of automated access control mechanisms under [ _Assignment: organization-defined conditions_ ] by [ _Assignment: organization-defined roles_ ].**<br>

    <ins>Discussion</ins>: In certain situations, such as when there is a threat to human life or an event that threatens the organization’s ability to carry out critical missions or business functions, an override capability for access control mechanisms may be needed. Override conditions are defined by organizations and used only in those limited circumstances. Audit events are defined in AU-2. Audit records are generated in AU-12.

    <ins>Related Controls</ins>: AU-2, AU-6, AU-10, AU-12, AU-14.

* (11) ACCESS ENFORCEMENT / RESTRICT ACCESS TO SPECIFIC INFORMATION TYPES<br>
**Restrict access to data repositories containing [ _Assignment: organization-defined information types_ ].**<br>

    <ins>Discussion</ins>: Restricting access to specific information is intended to provide flexibility regarding access control of specific information types within a system. For example, role-based access could be employed to allow access to only a specific type of personally identifiable information within a database rather than allowing access to the database in its entirety. Other examples include restricting access to cryptographic keys, authentication information, and selected system information.<br>

    <ins>Related Controls</ins>: CM-8, CM-12, CM-13, PM-5.<br>

* (12) ACCESS ENFORCEMENT / ASSERT AND ENFORCE APPLICATION ACCESS<br>
    * **(a) Require applications to assert, as part of the installation process, the access needed to the following system applications and functions: [ Assignment: organization-defined system applications and functions ];**<br>
    * **(b) Provide an enforcement mechanism to prevent unauthorized access; and**<br>
    * **(c) Approve access changes after initial installation of the application.**<br>

    <ins>Discussion</ins>: Asserting and enforcing application access is intended to address applications that need to access existing system applications and functions, including user contacts, global positioning systems, cameras, keyboards, microphones, networks, phones, or other files.<br>

    <ins>Related Controls</ins>: CM-7.

* (13) ACCESS ENFORCEMENT / ATTRIBUTE-BASED ACCESS CONTROL
**Enforce attribute-based access control policy over defined subjects and objects and control access based upon [ _Assignment: organization-defined attributes to assume access permissions_ ].**<br>

    <ins>Discussion</ins>: Attribute-based access control is an access control policy that restricts system access to authorized users based on specified organizational attributes (e.g., job function, identity), action attributes (e.g., read, write, delete), environmental attributes (e.g., time of day, location), and resource attributes (e.g., classification of a document). Organizations can create rules based on attributes and the authorizations (i.e., privileges) to perform needed operations on the systems associated with organization-defined attributes and rules. When users are assigned to attributes defined in attribute-based access control policies or rules, they can be provisioned to a system with the appropriate privileges or dynamically granted access to a protected resource. Attribute-based access control can be implemented as either a mandatory or discretionary form of access control. When implemented with mandatory access controls, the requirements in AC-3(3) define the scope of the subjects and objects covered by the policy.<br>

    <ins>Related Controls</ins>: None.

* (14) ACCESS ENFORCEMENT / INDIVIDUAL ACCESS
**Provide [ _Assignment: organization-defined mechanisms_ ] to enable individuals to have access to the following elements of their personally identifiable information: [ _Assignment: organization-defined elements_ ].**<br>

    <ins>Discussion</ins>: Individual access affords individuals the ability to review personally identifiable information about them held within organizational records, regardless of format. Access helps individuals to develop an understanding about how their personally identifiable information is being processed. It can also help individuals ensure that their data is accurate. Access mechanisms can include request forms and application interfaces. For federal agencies, [PRIVACT] processes can be located in systems of record notices and on agency websites. Access to certain types of records may not be appropriate (e.g., for federal agencies, law enforcement records within a system of records may be exempt from disclosure under the [PRIVACT]) or may require certain levels of authentication assurance. Organizational personnel consult with the senior agency official for privacy and legal counsel to determine appropriate mechanisms and access rights or limitations.<br>

    <ins>Related Controls</ins>: IA-8, PM-22, PM-20, PM-21.

* (15) ACCESS ENFORCEMENT / DISCRETIONARY AND MANDATORY ACCESS CONTROL<br>
    * **(a) Enforce [ Assignment: organization-defined mandatory access control policy ] over the set of covered subjects and objects specified in the policy; and**<br>
    * **(b) Enforce [ _Assignment: organization-defined discretionary access control policy_ ] over the set of covered subjects and objects specified in the policy.**<br>

    <ins>Discussion</ins>: Simultaneously implementing a mandatory access control policy and a discretionary access control policy can provide additional protection against the unauthorized execution of code by users or processes acting on behalf of users. This helps prevent a single compromised user or process from compromising the entire system.<br>

    <ins>Related Controls</ins>: SC-2, SC-3, AC-4.

<ins>References</ins>: [PRIVACT], [OMB A-130], [SP 800-57-1], [SP 800-57-2], [SP 800-57-3], [SP 800-162], [SP 800-178], [IR 7874].
