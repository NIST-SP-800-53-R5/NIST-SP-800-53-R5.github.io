---
layout: page
title: -- SI-20 TAINTING 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319200 
---

## SI-20 TAINTING

<ins>Control</ins>: Embed data or capabilities in the following systems or system components to determine if organizational data has been exfiltrated or improperly removed from the organization: [ _Assignment: organization-defined systems or system components_ ].

<ins>Discussion</ins>: Many cyber-attacks target organizational information, or information that the organization holds on behalf of other entities (e.g., personally identifiable information), and exfiltrate that data. In addition, insider attacks and erroneous user procedures can remove information from the system that is in violation of the organizational policies. Tainting approaches can range from passive to active. A passive tainting approach can be as simple as adding false email names and addresses to an internal database. If the organization receives email at one of the false email addresses, it knows that the database has been compromised. Moreover, the organization knows that the email was sent by an unauthorized entity, so any packets it includes potentially contain malicious code, and that the unauthorized entity may have potentially obtained a copy of the database. Another tainting approach can include embedding false data or steganographic data in files to enable the data to be found via open-source analysis. Finally, an active tainting approach can include embedding software in the data that is able to “call home,” thereby alerting the organization to its “capture,” and possibly its location, and the path by which it was exfiltrated or removed.

<ins>Related Controls</ins>: AU-13.

<ins>Control Enhancements</ins>: None.

<ins>References</ins>: [OMB A-130, Appendix II], [SP 800-160-2].
