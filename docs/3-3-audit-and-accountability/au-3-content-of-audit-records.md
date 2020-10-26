---
layout: page
title: --  AU-3 CONTENT OF AUDIT RECORDS 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 3330 
---

## AU-3 CONTENT OF AUDIT RECORDS

<ins>Control</ins>: Ensure that audit records contain information that establishes the following:

* a. What type of event occurred;
* b. When the event occurred;
* c. Where the event occurred;
* d. Source of the event;
* e. Outcome of the event; and
* f. Identity of any individuals, subjects, or objects/entities associated with the event.

<ins>Discussion</ins>: Audit record content that may be necessary to support the auditing function includes event descriptions (item a), time stamps (item b), source and destination addresses (item c), user or process identifiers (items d and f), success or fail indications (item e), and filenames involved (items a, c, e, and f) . Event outcomes include indicators of event success or failure and event-specific results, such as the system security and privacy posture after the event occurred. Organizations consider how audit records can reveal information about individuals that may give rise to privacy risks and how best to mitigate such risks. For example, there is the potential to reveal personally identifiable information in the audit trail, especially if the trail records inputs or is based on patterns or time of usage.

<ins>Related Controls</ins>: AU-2, AU-8, AU-12, AU-14, MA-4, PL-9, SA-8, SI-7, SI-11.

<ins>Control Enhancements</ins>:

* (1) CONTENT OF AUDIT RECORDS | ADDITIONAL AUDIT INFORMATION<br>
**Generate audit records containing the following additional information: [ _Assignment: organization-defined additional information_ ].**

    <ins>Discussion</ins>: The ability to add information generated in audit records is dependent on system functionality to configure the audit record content. Organizations may consider additional information in audit records including, but not limited to, access control or flow control rules invoked and individual identities of group account users. Organizations may also consider limiting additional audit record information to only information that is explicitly needed for audit requirements. This facilitates the use of audit trails and audit logs by not including information in audit records that could potentially be misleading, make it more difficult to locate information of interest, or increase the risk to individuals' privacy.

    <ins>Related Controls</ins>: None.

* (2) CONTENT OF AUDIT RECORDS | CENTRALIZED MANAGEMENT OF PLANNED AUDIT RECORD CONTENT<br>
[Withdrawn: Incorporated into PL-9.]

* (3) CONTENT OF AUDIT RECORDS | LIMIT PERSONALLY IDENTIFIABLE INFORMATION ELEMENTS<br>
Limit personally identifiable information contained in audit records to the following elements identified in the privacy risk assessment: [ _Assignment: organization-defined elements_ ].

    <ins>Discussion</ins>: Limiting personally identifiable information in audit records when such information is not needed for operational purposes helps reduce the level of privacy risk created by a system.

    <ins>Related Controls</ins>: RA-3.

<ins>References</ins>: [OMB A-130], [IR 8062].
