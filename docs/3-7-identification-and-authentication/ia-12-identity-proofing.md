---
layout: page
title: IA-12 IDENTITY PROOFING 
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 37120 
---

## IA-12 IDENTITY PROOFING

<ins>Control</ins>:
* a. Identity proof users that require accounts for logical access to systems based on appropriate identity assurance level requirements as specified in applicable standards and guidelines;
* b. Resolve user identities to a unique individual; and
* c. Collect, validate, and verify identity evidence.

<ins>Discussion</ins>: Identity proofing is the process of collecting, validating, and verifying a user’s identity information for the purposes of establishing credentials for accessing a system. Identity proofing is intended to mitigate threats to the registration of users and the establishment of their accounts. Standards and guidelines specifying identity assurance levels for identity proofing include [SP 800-63-3] and [SP 800-63A]. Organizations may be subject to laws, executive orders, directives, regulations, or policies that address the collection of identity evidence. Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such requirements.

<ins>Related Controls</ins>: AC-5, IA-1, IA-2, IA-3, IA-4, IA-5, IA-6, IA-8.

<ins>Control Enhancements</ins>:

* (1) IDENTITY PROOFING / SUPERVISOR AUTHORIZATION<br>
**Require that the registration process to receive an account for logical access includes supervisor or sponsor authorization.**

    <ins>Discussion</ins>: Including supervisor or sponsor authorization as part of the registration process provides an additional level of scrutiny to ensure that the user’s management chain is aware of the account, the account is essential to carry out organizational missions and functions, and the user’s privileges are appropriate for the anticipated responsibilities and authorities within the organization.

    <ins>Related Controls</ins>: None.

* (2) IDENTITY PROOFING / IDENTITY EVIDENCE<br>
**Require evidence of individual identification be presented to the registration authority.**

    <ins>Discussion</ins>: Identity evidence, such as documentary evidence or a combination of documents and biometrics, reduces the likelihood of individuals using fraudulent identification to establish an identity or at least increases the work factor of potential adversaries. The forms of acceptable evidence are consistent with the risks to the systems, roles, and privileges associated with the user’s account.

    <ins>Related Controls</ins>: None.

* (3) IDENTITY PROOFING / IDENTITY EVIDENCE VALIDATION AND VERIFICATION<br>
**Require that the presented identity evidence be validated and verified through [ _Assignment: organizational defined methods of validation and verification_ ].**

    <ins>Discussion</ins>: Validation and verification of identity evidence increases the assurance that accounts and identifiers are being established for the correct user and authenticators are being bound to that user. Validation refers to the process of confirming that the evidence is genuine and authentic, and the data contained in the evidence is correct, current, and related to an individual. Verification confirms and establishes a linkage between the claimed identity and the actual existence of the user presenting the evidence. Acceptable methods for validating and verifying identity evidence are consistent with the risks to the systems, roles, and privileges associated with the users account.

    <ins>Related Controls</ins>: None.

* (4) IDENTITY PROOFING / IN-PERSON VALIDATION AND VERIFICATION<br>
**Require that the validation and verification of identity evidence be conducted in person before a designated registration authority.**

    <ins>Discussion</ins>: In-person proofing reduces the likelihood of fraudulent credentials being issued because it requires the physical presence of individuals, the presentation of physical identity documents, and actual face-to-face interactions with designated registration authorities.

    <ins>Related Controls</ins>: None.

* (5) IDENTITY PROOFING / ADDRESS CONFIRMATION<br>
**Require that a [ Selection: registration code; notice of proofing ] be delivered through an out-of-band channel to verify the users address (physical or digital) of record.**

    <ins>Discussion</ins>: To make it more difficult for adversaries to pose as legitimate users during the identity proofing process, organizations can use out-of-band methods to ensure that the individual associated with an address of record is the same individual that participated in the registration. Confirmation can take the form of a temporary enrollment code or a notice of proofing. The delivery address for these artifacts is obtained from records and not self- asserted by the user. The address can include a physical or digital address. A home address is an example of a physical address. Email addresses and telephone numbers are examples of digital addresses.

    <ins>Related Controls</ins>: IA-12.

* (6) IDENTITY PROOFING / ACCEPT EXTERNALLY-PROOFED IDENTITIES<br>
**Accept externally-proofed identities at [ _Assignment: organization-defined identity assurance level_ ].**

    <ins>Discussion</ins>: To limit unnecessary re-proofing of identities, particularly of non-PIV users, organizations accept proofing conducted at a commensurate level of assurance by other agencies or organizations. Proofing is consistent with organizational security policy and the identity assurance level appropriate for the system, application, or information accessed. Accepting externally-proofed identities is a fundamental component of managing federated identities across agencies and organizations.

    <ins>Related Controls</ins>: IA-3, IA-4, IA-5, IA-8.

<ins>References</ins>: [FIPS 201-2], [SP 800-63-3], [SP 800-63A], [SP 800-79-2].
