---
layout: default
title:  -- AC-23 DATA MINING PROTECTION 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15230
---

## AC-23 DATA MINING PROTECTION

<ins>Control</ins>: Employ [ _Assignment: organization-defined data mining prevention and detection techniques_ ] for [ _Assignment: organization-defined data storage objects_ ] to detect and protect against unauthorized data mining.

<ins>Discussion</ins>: Data mining is an analytical process that attempts to find correlations or patterns in large data sets for the purpose of data or knowledge discovery. Data storage objects include database records and database fields. Sensitive information can be extracted from data mining operations. When information is personally identifiable information, it may lead to unanticipated revelations about individuals and give rise to privacy risks. Prior to performing data mining activities, organizations determine whether such activities are authorized. Organizations may be subject to applicable laws, executive orders, directives, regulations, or policies that address data mining requirements. Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such requirements.

Data mining prevention and detection techniques include limiting the number and frequency of database queries to increase the work factor needed to determine the contents of databases, limiting types of responses provided to database queries, applying differential privacy techniques or homomorphic encryption, and notifying personnel when atypical database queries or accesses occur. Data mining protection focuses on protecting information from data mining while such information resides in organizational data stores. In contrast, AU-13 focuses on monitoring for organizational information that may have been mined or otherwise obtained from data stores and is available as open-source information residing on external sites, such as social networking or social media websites.

[EO 13587] requires the establishment of an insider threat program for deterring, detecting, and mitigating insider threats, including the safeguarding of sensitive information from exploitation, compromise, or other unauthorized disclosure. Data mining protection requires organizations to identify appropriate techniques to prevent and detect unnecessary or unauthorized data mining. Data mining can be used by an insider to collect organizational information for the purpose of exfiltration.

<ins>Related Controls</ins>: PM-12, PT- 2.

<ins>Control Enhancements</ins>: None.

<ins>References</ins>: [EO 13587 ].
