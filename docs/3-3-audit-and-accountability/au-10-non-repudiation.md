---
layout: page
title: --  AU-10 NON-REPUDIATION 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 33100 
---

## AU-10 NON-REPUDIATION

<ins>Control</ins>: Provide irrefutable evidence that an individual (or process acting on behalf of an individual) has performed [ _Assignment: organization-defined actions to be covered by non- repudiation_ ].

<ins>Discussion</ins>: Types of individual actions covered by non-repudiation include creating information, sending and receiving messages, and approving information. Non-repudiation protects against claims by authors of not having authored certain documents, senders of not having transmitted messages, receivers of not having received messages, and signatories of not having signed documents. Non-repudiation services can be used to determine if information originated from an individual or if an individual took specific actions (e.g., sending an email, signing a contract, approving a procurement request, or receiving specific information). Organizations obtain non- repudiation services by employing various techniques or mechanisms, including digital signatures and digital message receipts.

<ins>Related Controls</ins>: AU-9, PM-12, SA-8, SC-8, SC-12, SC-13, SC-16, SC-17, SC-23.

<ins>Control Enhancements</ins>:

* (1) NON-REPUDIATION / ASSOCIATION OF IDENTITIES<br>
    * **(a) Bind the identity of the information producer with the information to [ _Assignment: organization-defined strength of binding_ ]; and**
    * **(b) Provide the means for authorized individuals to determine the identity of the producer of the information.**

    <ins>Discussion</ins>: Binding identities to the information supports audit requirements that provide organizational personnel with the means to identify who produced specific information in the event of an information transfer. Organizations determine and approve the strength of attribute binding between the information producer and the information based on the security category of the information and other relevant risk factors.

    <ins>Related Controls</ins>: AC-4, AC-16.

* (2) NON-REPUDIATION / VALIDATE BINDING OF INFORMATION PRODUCER IDENTITY<br>
    * **(a) Validate the binding of the information producer identity to the information at [ _Assignment: organization-defined frequency_ ]; and**
    * **(b) Perform [ Assignment: organization-defined actions ] in the event of a validation error.**

    <ins>Discussion</ins>: Validating the binding of the information producer identity to the information prevents the modification of information between production and review. The validation of bindings can be achieved by, for example, using cryptographic checksums. Organizations determine if validations are in response to user requests or generated automatically.

    <ins>Related Controls</ins>: AC-3, AC-4, AC-16.

* (3) NON-REPUDIATION / CHAIN OF CUSTODY<br>
**Maintain reviewer or releaser credentials within the established chain of custody for information reviewed or released.**

    <ins>Discussion</ins>: Chain of custody is a process that tracks the movement of evidence through its collection, safeguarding, and analysis life cycle by documenting each individual who handled the evidence, the date and time the evidence was collected or transferred, and the purpose for the transfer. If the reviewer is a human or if the review function is automated but separate from the release or transfer function, the system associates the identity of the reviewer of the information to be released with the information and the information label. In the case of human reviews, maintaining the credentials of reviewers or releasers provides the organization with the means to identify who reviewed and released the information. In the case of automated reviews, it ensures that only approved review functions are used.

    <ins>Related Controls</ins>: AC-4, AC-16.

* (4) NON-REPUDIATION / VALIDATE BINDING OF INFORMATION REVIEWER IDENTITY<br>
    * **(a) Validate the binding of the information reviewer identity to the information at the transfer or release points prior to release or transfer between [ _Assignment: organization-defined security domains_ ]; and**
    * (b) **Perform [ _Assignment: organization-defined actions_ ] in the event of a validation error.**

    <ins>Discussion</ins>: Validating the binding of the information reviewer identity to the information at transfer or release points prevents the unauthorized modification of information between review and the transfer or release. The validation of bindings can be achieved by using cryptographic checksums. Organizations determine if validations are in response to user requests or generated automatically.

    <ins>Related Controls</ins>: AC-4, AC-16.

* (5) NON-REPUDIATION / DIGITAL SIGNATURES<br>
[Withdrawn: Incorporated into SI-7.]

<ins>References</ins>: [FIPS 140-3], [FIPS 180-4], [FIPS 186-4], [FIPS 202], [SP 800-177].
