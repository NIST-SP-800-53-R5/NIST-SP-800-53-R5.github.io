---
layout: page
title: -- IA-8 IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) 
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 3780 
---

## IA-8 IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS)

<ins>Control</ins>: Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational users.

<ins>Discussion</ins>: Non-organizational users include system users other than organizational users explicitly covered by IA-2. Non-organizational users are uniquely identified and authenticated for accesses other than those explicitly identified and documented in AC-14. Identification and authentication of non-organizational users accessing federal systems may be required to protect federal, proprietary, or privacy-related information (with exceptions noted for national security systems). Organizations consider many factors—including security, privacy, scalability, and practicality—when balancing the need to ensure ease of use for access to federal information and systems with the need to protect and adequately mitigate risk.

<ins>Related Controls</ins>: AC-2, AC-6, AC-14, AC-17, AC-18, AU-6, IA-2, IA-4, IA-5, IA-10, IA-11, MA-4, RA- 3, SA-4, SC-8.

<ins>Control Enhancements</ins>:

* (1) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / ACCEPTANCE OF PIV CREDENTIALS FROM OTHER AGENCIES<br>
**Accept and electronically verify Personal Identity Verification-compliant credentials from other federal agencies.**

    <ins>Discussion</ins>: Acceptance of Personal Identity Verification (PIV) credentials from other federal agencies applies to both logical and physical access control systems. PIV credentials are those credentials issued by federal agencies that conform to FIPS Publication 201 and supporting guidelines. The adequacy and reliability of PIV card issuers are addressed and authorized using [SP 800-79-2].

    <ins>Related Controls</ins>: PE-3.

* (2) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / ACCEPTANCE OF EXTERNAL AUTHENTICATORS<br>
    * **(a) Accept only external authenticators that are NIST-compliant; and**
    * **(b) Document and maintain a list of accepted external authenticators.**

    <ins>Discussion</ins>: Acceptance of only NIST-compliant external authenticators applies to organizational systems that are accessible to the public (e.g., public-facing websites). External authenticators are issued by nonfederal government entities and are compliant with [SP 800-63B]. Approved external authenticators meet or exceed the minimum Federal Government-wide technical, security, privacy, and organizational maturity requirements. Meeting or exceeding Federal requirements allows Federal Government relying parties to trust external authenticators in connection with an authentication transaction at a specified authenticator assurance level.

    <ins>Related Controls</ins>: None.

* (3) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / USE OF FICAM-APPROVED PRODUCTS<br>
[Withdrawn: Incorporated into IA -8(2).]

* (4) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / USE OF DEFINED PROFILES<br>
**Conform to the following profiles for identity management [ _Assignment: organization-defined identity management profiles_ ].**

    <ins>Discussion</ins>: Organizations define profiles for identity management based on open identity management standards. To ensure that open identity management standards are viable, robust, reliable, sustainable, and interoperable as documented, the Federal Government assesses and scopes the standards and technology implementations against applicable laws, executive orders, directives, policies, regulations, standards, and guidelines.

    <ins>Related Controls</ins>: None.

* (5) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / ACCEPTANCE OF PIV-I CREDENTIALS<br>
**Accept and verify federated or PKI credentials that meet [ _Assignment: organization-defined policy_ ].**

    <ins>Discussion</ins>: Acceptance of PIV-I credentials can be implemented by PIV, PIV-I, and other commercial or external identity providers. The acceptance and verification of Personal Identity Verification (PIV)-I-compliant credentials apply to both logical and physical access control systems. The acceptance and verification of PIV-I credentials address nonfederal issuers of identity cards that desire to interoperate with United States Government PIV systems and that can be trusted by Federal Government-relying parties. The X.509 certificate policy for the Federal Bridge Certification Authority (FBCA) addresses PIV-I requirements. The PIV-I card is commensurate with the PIV credentials as defined in cited references. PIV-I credentials are the credentials issued by a PIV-I provider whose PIV-I certificate policy maps to the Federal Bridge PIV-I Certificate Policy. A PIV-I provider is cross-certified with the FBCA (directly or through another PKI bridge) with policies that have been mapped and approved as meeting the requirements of the PIV-I policies defined in the FBCA certificate policy.

    <ins>Related Controls</ins>: None.

* (6) IDENTIFICATION AND AUTHENTICATION (NON-ORGANIZATIONAL USERS) / DISASSOCIABILITY<br>
**Implement the following measures to disassociate user attributes or identifier assertion relationships among individuals, credential service providers, and relying parties: [ _Assignment: organization-defined measures_ ].**

    <ins>Discussion</ins>: Federated identity solutions can create increased privacy risks due to the tracking and profiling of individuals. Using identifier mapping tables or cryptographic techniques to blind credential service providers and relying parties from each other or to make identity attributes less visible to transmitting parties can reduce these privacy risks.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [FED PKI], [FIPS 201-2], [SP 800-63-3], [SP 800-79-2], [SP 800-116], [IR 8062].

