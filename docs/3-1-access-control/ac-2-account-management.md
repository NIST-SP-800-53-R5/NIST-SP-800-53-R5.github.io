---
layout: default
title:  -- AC-2 ACCOUNT MANAGEMENT 
parent: . 3.1 ACCESS CONTROL 
nav_order: 1520
---

## AC-2 ACCOUNT MANAGEMENT

<ins>Control:</ins>
* a. Define and document the types of accounts allowed and specifically prohibited for use within the system;
* b. Assign account managers;
* c. Require [_Assignment: organization-defined prerequisites and criteria_] for group and role membership;
* d. Specify:
    * 1 . Authorized users of the system;
    * 2 . Group and role membership; and
    * 3 . Access authorizations (i.e., privileges) and [_Assignment: organization-defined attributes (as required)_] for each account;
* e. Require approvals by [_Assignment: organization-defined personnel or roles_] for requests to create accounts;
* f. Create, enable, modify, disable, and remove accounts in accordance with [_Assignment: organization-defined policy, procedures, prerequisites, and criteria_];
* g. Monitor the use of accounts;
* h. Notify account managers and [_Assignment: organization-defined personnel or roles_] within:
    * 1 . [_Assignment: organization-defined time period_ ] when accounts are no longer required;
    * 2 . [ _Assignment: organization-defined time period_ ] when users are terminated or transferred; and
    * 3 . [ _Assignment: organization-defined time period_ ] when system usage or need-to-know changes for an individual;
* i. Authorize access to the system based on:
    * 1 . A valid access authorization;
    * 2 . Intended system usage; and
    * 3 . [ _Assignment: organization-defined attributes (as required)_ ];
* j. Review accounts for compliance with account management requirements [ _Assignment: organization-defined frequency_ ];
* k. Establish and implement a process for changing shared or group account authenticators (if deployed) when individuals are removed from the group; and
* l. Align account management processes with personnel termination and transfer processes.
    <ins>Discussion</ins>: Examples of system account types include individual, shared, group, system, guest, anonymous, emergency, developer, temporary, and service. Identification of authorized system users and the specification of access privileges reflect the requirements in other controls in the security plan. Users requiring administrative privileges on system accounts receive additional scrutiny by organizational personnel responsible for approving such accounts and privileged access, including system owner, mission or business owner, senior agency information security officer, or senior agency official for privacy. Types of accounts that organizations may wish to prohibit due to increased risk include shared, group, emergency, anonymous, temporary, and guest accounts.

    Where access involves personally identifiable information, security programs collaborate with the senior agency official for privacy to establish the specific conditions for group and role membership; specify authorized users, group and role membership, and access authorizations for each account; and create, adjust, or remove system accounts in accordance with organizational policies. Policies can include such information as account expiration dates or other factors that trigger the disabling of accounts. Organizations may choose to define access privileges or other attributes by account, type of account, or a combination of the two. Examples of other attributes required for authorizing access include restrictions on time of day, day of week, and point of origin. In defining other system account attributes, organizations consider system-related requirements and mission/business requirements. Failure to consider these factors could affect system availability.

    Temporary and emergency accounts are intended for short-term use. Organizations establish temporary accounts as part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts, including local logon accounts used for special tasks or when network resources are unavailable (may also be known as accounts of last resort). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include when shared/group, emergency, or temporary accounts are no longer required and when individuals are transferred or terminated. Changing shared/group authenticators when members leave the group is intended to ensure that former group members do not retain access to the shared or group account. Some types of system accounts may require specialized training.

    <ins>Related Controls<ins>:  AC-3, AC-5, AC-6, AC-17, AC-18, AC-20, AC-24, AU-2, AU-12, CM-5, IA-2, IA-4, IA-5, IA-8, MA-3, MA-5, PE-2, PL-4, PS-2, PS-4, PS-5, PS-7, PT-2, PT-3, SC-7, SC-12, SC-13, SC-37.

    <ins>Control Enhancements<ins>:
    * (1) ACCOUNT MANAGEMENT / AUTOMATED SYSTEM ACCOUNT MANAGEMENT<br>
    **Support the management of system accounts using [_Assignment: organization-defined automated mechanisms_].**<br>

        <ins>Discussion</ins>: Automated system account management includes using automated mechanisms to create, enable, modify, disable, and remove accounts; notify account managers when an account is created, enabled, modified, disabled, or removed, or when users are terminated or transferred; monitor system account usage; and report atypical system account usage. Automated mechanisms can include internal system functions and email, telephonic, and text messaging notifications.<br>

        <ins>Related Controls<ins>: None.<br>

    * (2) ACCOUNT MANAGEMENT / AUTOMATED TEMPORARY AND EMERGENCY ACCOUNT MANAGEMENT<br>
    **Automatically [ _Selection: remove; disable_ ] temporary and emergency accounts after [ _Assignment: organization-defined time period for each type of account_ ].**<br>

        <ins>Discussion</ins>: Management of temporary and emergency accounts includes the removal or disabling of such accounts automatically after a predefined time period rather than at the convenience of the system administrator. Automatic removal or disabling of accounts provides a more consistent implementation.<br>

        <ins>Related Controls</ins>: None.

    * (3) ACCOUNT MANAGEMENT / DISABLE ACCOUNTS<br>
    **Disable accounts within [ _Assignment: organization-defined time period_ ] when the accounts:**
        * **(a) Have expired;**
        * **(b) Are no longer associated with a user or individual;**
        * **(c) Are in violation of organizational policy; or**
        * **(d) Have been inactive for [ _Assignment: organization-defined time period_ ].**<br>

        <ins>Discussion</ins>: Disabling expired, inactive, or otherwise anomalous accounts supports the concepts of least privilege and least functionality which reduce the attack surface of the system.<br>

        <ins>Related Controls</ins>: None.<br>

    * (4) ACCOUNT MANAGEMENT / AUTOMATED AUDIT ACTIONS<br>
    **Automatically audit account creation, modification, enabling, disabling, and removal actions.**<br>

        <ins>Discussion</ins>: Account management audit records are defined in accordance with AU-2 and reviewed, analyzed, and reported in accordance with AU-6.<br>

        <ins>Related Controls</ins>: AU-2, AU-6.<br>

    * (5) ACCOUNT MANAGEMENT / INACTIVITY LOGOUT<br>
    **Require that users log out when [ _Assignment: organization-defined time period of expected inactivity or description of when to log out_ ].**<br>

        <ins>Discussion</ins>: Inactivity logout is behavior- or policy-based and requires users to take physical action to log out when they are expecting inactivity longer than the defined period. Automatic enforcement of inactivity logout is addressed by AC-11.<br>

        <ins>Related Controls</ins>: AC-11.<br>

    * (6) ACCOUNT MANAGEMENT / DYNAMIC PRIVILEGE MANAGEMENT<br>
    **Implement [ _Assignment: organization-defined dynamic privilege management capabilities_ ].**<br>

        <ins>Discussion</ins>: In contrast to access control approaches that employ static accounts and predefined user privileges, dynamic access control approaches rely on runtime access control decisions facilitated by dynamic privilege management, such as attribute-based access control. While user identities remain relatively constant over time, user privileges typically change more frequently based on ongoing mission or business requirements and the operational needs of organizations. An example of dynamic privilege management is the immediate revocation of privileges from users as opposed to requiring that users terminate and restart their sessions to reflect changes in privileges. Dynamic privilege management can also include mechanisms that change user privileges based on dynamic rules as opposed to editing specific user profiles. Examples include automatic adjustments of user privileges if they are operating out of their normal work times, if their job function or assignment changes, or if systems are under duress or in emergency situations. Dynamic privilege management includes the effects of privilege changes, for example, when there are changes to encryption keys used for communications.<br>

        <ins>Related Controls</ins>: AC-16.<br>

    * (7) ACCOUNT MANAGEMENT / PRIVILEGED USER ACCOUNTS<br>
        * **(a) Establish and administer privileged user accounts in accordance with [ _Selection: a role-based access scheme; an attribute-based access scheme_ ];**<br>
        * **(b) Monitor privileged role or attribute assignments;**<br>
        * **(c) Monitor changes to roles or attributes; and**<br>
        * **(d) Revoke access when privileged role or attribute assignments are no longer appropriate.**<br>

        <ins>Discussion</ins>: Privileged roles are organization-defined roles assigned to individuals that allow those individuals to perform certain security-relevant functions that ordinary users are not authorized to perform. Privileged roles include key management, account management, database administration, system and network administration, and web administration. A role-based access scheme organizes permitted system access and privileges into roles. In contrast, an attribute-based access scheme specifies allowed system access and privileges based on attributes.<br>

        <ins>Related Controls</ins>: None.<br>

    * (8) ACCOUNT MANAGEMENT / DYNAMIC ACCOUNT MANAGEMENT<br>
    **Create, activate, manage, and deactivate [ _Assignment: organization- defined system accounts_ ] dynamically.**<br>

        <ins>Discussion</ins>: Approaches for dynamically creating, activating, managing, and deactivating system accounts rely on automatically provisioning the accounts at runtime for entities that were previously unknown. Organizations plan for the dynamic management, creation, activation, and deactivation of system accounts by establishing trust relationships, business rules, and mechanisms with appropriate authorities to validate related authorizations and privileges.<br>

        <ins>Related Controls</ins>: AC-16.

    * (9) ACCOUNT MANAGEMENT / RESTRICTIONS ON USE OF SHARED AND GROUP ACCOUNTS<br>
    **Only permit the use of shared and group accounts that meet [ _Assignment: organization-defined conditions for establishing shared and group accounts_ ].**<br>

        <ins>Discussion</ins>: Before permitting the use of shared or group accounts, organizations consider the increased risk due to the lack of accountability with such accounts.<br>

        <ins>Related Controls</ins>: None.<br>

    * (10) ACCOUNT MANAGEMENT / SHARED AND GROUP ACCOUNT CREDENTIAL CHANGE<br>
    [Withdrawn: Incorporated into AC-2k.]

    * (11) ACCOUNT MANAGEMENT / USAGE CONDITIONS<br>
    **Enforce [ _Assignment: organization-defined circumstances and/or usage conditions_ ] for [ _Assignment: organization-defined system accounts_ ].**<br>

        <ins>Discussion</ins>: Specifying and enforcing usage conditions helps to enforce the principle of least privilege, increase user accountability, and enable effective account monitoring. Account monitoring includes alerts generated if the account is used in violation of organizational parameters. Organizations can describe specific conditions or circumstances under which system accounts can be used, such as by restricting usage to certain days of the week, time of day, or specific durations of time.

        <ins>Related Controls</ins>: None.<br>

    * (12) ACCOUNT MANAGEMENT / ACCOUNT MONITORING FOR ATYPICAL USAGE<br>
        * **(a) Monitor system accounts for [ _Assignment: organization-defined atypical usage_ ]; and**<br>
        * **(b) Report atypical usage of system accounts to [ _Assignment: organization-defined personnel or roles_ ].**<br>

        <ins>Discussion</ins>: Atypical usage includes accessing systems at certain times of the day or from locations that are not consistent with the normal usage patterns of individuals. Monitoring for atypical usage may reveal rogue behavior by individuals or an attack in progress. Account monitoring may inadvertently create privacy risks since data collected to identify atypical usage may reveal previously unknown information about the behavior of individuals. Organizations assess and document privacy risks from monitoring accounts for atypical usage in their privacy impact assessment and make determinations that are in alignment with their privacy program plan.<br>

        <ins>Related Controls</ins>: AU-6, AU-7, CA-7, IR -8, SI-4.<br>

    * (13) ACCOUNT MANAGEMENT / DISABLE ACCOUNTS FOR HIGH-RISK INDIVIDUALS<br>
    **Disable accounts of individuals within [ _Assignment: organization-defined time period_ ] of discovery of [ _Assignment: organization-defined significant risks_ ].**<br>

        <ins>Discussion</ins>: Users who pose a significant security and/or privacy risk include individuals for whom reliable evidence indicates either the intention to use authorized access to systems to cause harm or through whom adversaries will cause harm. Such harm includes adverse impacts to organizational operations, organizational assets, individuals, other organizations, or the Nation. Close coordination among system administrators, legal staff, human resource managers, and authorizing officials is essential when disabling system accounts for high-risk individuals.<br>

        <ins>Related Controls</ins>: AU-6, SI-4.<br>

    References: [SP 800-162], [SP 800-178], [SP 800-192].
