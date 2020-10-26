---
layout: page
title: --  AU-5 RESPONSE TO AUDIT LOGGING PROCESS FAILURES 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 3350 
---

## AU-5 RESPONSE TO AUDIT LOGGING PROCESS FAILURES

<ins>Control</ins>:

* a. Alert [ _Assignment: organization-defined personnel or roles_ ] within [ _Assignment: organization-defined time period_ ] in the event of an audit logging process failure; and
* b. Take the following additional actions: [ Assignment: organization-defined additional actions ].

<ins>Discussion</ins>: Audit logging process failures include software and hardware errors, failures in audit log capturing mechanisms, and reaching or exceeding audit log storage capacity. Organization- defined actions include overwriting oldest audit records, shutting down the system, and stopping the generation of audit records. Organizations may choose to define additional actions for audit logging process failures based on the type of failure, the location of the failure, the severity of the failure, or a combination of such factors. When the audit logging process failure is related to storage, the response is carried out for the audit log storage repository (i.e., the distinct system component where the audit logs are stored), the system on which the audit logs reside, the total audit log storage capacity of the organization (i.e., all audit log storage repositories combined), or all three. Organizations may decide to take no additional actions after alerting designated roles or personnel.

<ins>Related Controls</ins>: AU-2, AU-4, AU-7, AU-9, AU-11, AU-12, AU-14, SI-4, SI-12.

<ins>Control Enhancements</ins>:

* (1) RESPONSE TO AUDIT LOGGING PROCESS FAILURES | STORAGE CAPACITY WARNING<br>
**Provide a warning to [ _Assignment: organization-defined personnel, roles, and/or locations_ ] within [ _Assignment: organization-defined time period_ ] when allocated audit log storage volume reaches [ _Assignment: organization-defined percentage_ ] of repository maximum audit log storage capacity.**

    <ins>Discussion</ins>: Organizations may have multiple audit log storage repositories distributed across multiple system components with each repository having different storage volume capacities.

    <ins>Related Controls</ins>: None.

* (2) RESPONSE TO AUDIT LOGGING PROCESS FAILURES | REAL-TIME ALERTS<br>
**Provide an alert within [ _Assignment: organization-defined real-time period_ ] to [ _Assignment: organization-defined personnel, roles, and/or locations_ ] when the following audit failure events occur: [ _Assignment: organization-defined audit logging failure events requiring real-time alerts_ ].**

    <ins>Discussion</ins>: Alerts provide organizations with urgent messages. Real-time alerts provide
these messages at information technology speed (i.e., the time from event detection to alert
occurs in seconds or less).

    <ins>Related Controls</ins>: None.

* (3) RESPONSE TO AUDIT LOGGING PROCESS FAILURES | CONFIGURABLE TRAFFIC VOLUME THRESHOLDS<br>
**Enforce configurable network communications traffic volume thresholds reflecting limits on audit log storage capacity and [ _Selection: reject; delay_ ] network traffic above those thresholds.**

    <ins>Discussion</ins>: Organizations have the capability to reject or delay the processing of network communications traffic if audit logging information about such traffic is determined to exceed the storage capacity of the system audit logging function. The rejection or delay response is triggered by the established organizational traffic volume thresholds that can be adjusted based on changes to audit log storage capacity.

    <ins>Related Controls</ins>: None.

* (4) RESPONSE TO AUDIT LOGGING PROCESS FAILURES | SHUTDOWN ON FAILURE<br>
**Invoke a [ _Selection: full system shutdown; partial system shutdown; degraded operational mode with limited mission or business functionality available_ ] in the event of [ _Assignment: organization-defined audit logging failures_ ], unless an alternate audit logging capability exists.**

    <ins>Discussion</ins>: Organizations determine the types of audit logging failures that can trigger automatic system shutdowns or degraded operations. Because of the importance of ensuring mission and business continuity, organizations may determine that the nature of the audit logging failure is not so severe that it warrants a complete shutdown of the system supporting the core organizational mission and business functions. In those instances, partial system shutdowns or operating in a degraded mode with reduced capability may be viable alternatives.

    <ins>Related Controls</ins>: AU-15.

* (5) RESPONSE TO AUDIT LOGGING PROCESS FAILURES | ALTERNATE AUDIT LOGGING CAPABILITY<br>
Provide an alternate audit logging capability in the event of a failure in primary audit logging capability that implements [ _Assignment: organization-defined alternate audit logging functionality_ ].

    <ins>Discussion</ins>: Since an alternate audit logging capability may be a short-term protection solution employed until the failure in the primary audit logging capability is corrected, organizations may determine that the alternate audit logging capability need only provide a subset of the primary audit logging functionality that is impacted by the failure.

    <ins>Related Controls</ins>: AU-9.

<ins>References</ins>: None.
