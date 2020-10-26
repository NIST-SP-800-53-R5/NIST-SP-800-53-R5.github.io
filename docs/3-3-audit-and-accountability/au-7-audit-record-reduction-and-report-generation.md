---
layout: page
title: --  AU-7 AUDIT RECORD REDUCTION AND REPORT GENERATION 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 3370 
---

## AU-7 AUDIT RECORD REDUCTION AND REPORT GENERATION

<ins>Control</ins>: Provide and implement an audit record reduction and report generation capability that:

* a. Supports on-demand audit record review, analysis, and reporting requirements and after-the-fact investigations of incidents; and
* b. Does not alter the original content or time ordering of audit records.

<ins>Discussion</ins>: Audit record reduction is a process that manipulates collected audit log information and organizes it into a summary format that is more meaningful to analysts. Audit record reduction and report generation capabilities do not always emanate from the same system or from the same organizational entities that conduct audit logging activities. The audit record reduction capability includes modern data mining techniques with advanced data filters to identify anomalous behavior in audit records. The report generation capability provided by the system can generate customizable reports. Time ordering of audit records can be an issue if the granularity of the timestamp in the record is insufficient.

<ins>Related Controls</ins>: AC-2, AU-2, AU-3, AU-4, AU-5, AU-6, AU-12, AU-16, CM-5, IA-5, IR-4, PM-12, SI- 4.

<ins>Control Enhancements</ins>:

* (1) AUDIT RECORD REDUCTION AND REPORT GENERATION | AUTOMATIC PROCESSING<br>
**Provide and implement the capability to process, sort, and search audit records for events of interest based on the following content: [ _Assignment: organization-defined fields within audit records_ ].**

    <ins>Discussion</ins>: Events of interest can be identified by the content of audit records, including system resources involved, information objects accessed, identities of individuals, event types, event locations, event dates and times, Internet Protocol addresses involved, or event success or failure. Organizations may define event criteria to any degree of granularity required, such as locations selectable by a general networking location or by specific system component.

    <ins>Related Controls</ins>: None.

* (2) AUDIT RECORD REDUCTION AND REPORT GENERATION | AUTOMATIC SORT AND SEARCH<br>
[Withdrawn: Incorporated into AU-7(1).]

<ins>References</ins>: None.

