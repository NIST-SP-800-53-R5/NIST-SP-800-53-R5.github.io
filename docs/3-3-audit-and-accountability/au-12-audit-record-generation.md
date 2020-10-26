---
layout: page
title: --  AU-12 AUDIT RECORD GENERATION 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 33120 
---

## AU-12 AUDIT RECORD GENERATION

<ins>Control</ins>:

* a. Provide audit record generation capability for the event types the system is capable of auditing as defined in AU-2a on [ _Assignment: organization-defined system components_ ];
* b. Allow [ _Assignment: organization-defined personnel or roles_ ] to select the event types that are to be logged by specific components of the system; and
* c. Generate audit records for the event types defined in AU-2c that include the audit record content defined in AU-3.

<ins>Discussion</ins>: Audit records can be generated from many different system components. The event types specified in AU-2d are the event types for which audit logs are to be generated and are a subset of all event types for which the system can generate audit records.

<ins>Related Controls</ins>: AC-6, AC-17, AU-2, AU-3, AU-4, AU-5, AU-6, AU-7, AU-14, CM-5, MA-4, MP-4, PM-12, SA-8, SC-18, SI-3, SI-4, SI-7, SI-10.

<ins>Control Enhancements</ins>:

* (1) AUDIT RECORD GENERATION | SYSTEM-WIDE AND TIME-CORRELATED AUDIT TRAIL<br>
**Compile audit records from [ _Assignment: organization-defined system components_ ] into a system-wide (logical or physical) audit trail that is time-correlated to within [ _Assignment: organization-defined level of tolerance for the relationship between time stamps of individual records in the audit trail_ ].**

    <ins>Discussion</ins>: Audit trails are time-correlated if the time stamps in the individual audit records can be reliably related to the time stamps in other audit records to achieve a time ordering of the records within organizational tolerances.

    <ins>Related Controls</ins>: AU-8, SC-45.

* (2) AUDIT RECORD GENERATION | STANDARDIZED FORMATS<br>
**Produce a system-wide (logical or physical) audit trail composed of audit records in a standardized format.**

    <ins>Discussion</ins>: Audit records that follow common standards promote interoperability and information exchange between devices and systems. Promoting interoperability and information exchange facilitates the production of event information that can be readily analyzed and correlated. If logging mechanisms do not conform to standardized formats, systems may convert individual audit records into standardized formats when compiling system-wide audit trails.

    <ins>Related Controls</ins>: None.

* (3) AUDIT RECORD GENERATION | CHANGES BY AUTHORIZED INDIVIDUALS<br>
**Provide and implement the capability for [ _Assignment: organization-defined individuals or roles_ ] to change the logging to be performed on [ _Assignment: organization-defined system components_ ] based on [ _Assignment: organization-defined selectable event criteria_ ] within [ _Assignment: organization-defined time thresholds_ ].**

    <ins>Discussion</ins>: Permitting authorized individuals to make changes to system logging enables organizations to extend or limit logging as necessary to meet organizational requirements. Logging that is limited to conserve system resources may be extended (either temporarily or permanently) to address certain threat situations. In addition, logging may be limited to a specific set of event types to facilitate audit reduction, analysis, and reporting. Organizations can establish time thresholds in which logging actions are changed (e.g., near real-time, within minutes, or within hours).

    <ins>Related Controls</ins>: AC-3.

* (4) AUDIT RECORD GENERATION | QUERY PARAMETER AUDITS OF PERSONALLY IDENTIFIABLE INFORMATION<br>
**Provide and implement the capability for auditing the parameters of user query events for data sets containing personally identifiable information.**

    <ins>Discussion</ins>: Query parameters are explicit criteria that an individual or automated system submits to a system to retrieve data. Auditing of query parameters for datasets that contain personally identifiable information augments the capability of an organization to track and understand the access, usage, or sharing of personally identifiable information by authorized personnel.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
