---
layout: page
title: -- IA-5 AUTHENTICATOR MANAGEMENT 
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 3750 
---

## IA-5 AUTHENTICATOR MANAGEMENT

<ins>Control</ins>: Manage system authenticators by:
* a. Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, service, or device receiving the authenticator;
* b. Establishing initial authenticator content for any authenticators issued by the organization;
* c. Ensuring that authenticators have sufficient strength of mechanism for their intended use;
* d. Establishing and implementing administrative procedures for initial authenticator distribution, for lost or compromised or damaged authenticators, and for revoking authenticators;
* e. Changing default authenticators prior to first use;
* f. Changing or refreshing authenticators [ _Assignment: organization-defined time period by authenticator type_ ] or when [ _Assignment: organization-defined events_ ] occur;
* g. Protecting authenticator content from unauthorized disclosure and modification;
* h. Requiring individuals to take, and having devices implement, specific controls to protect authenticators; and
* i. Changing authenticators for group or role accounts when membership to those accounts
changes.

<ins>Discussion</ins>: Authenticators include passwords, cryptographic devices, biometrics, certificates, one-time password devices, and ID badges. Device authenticators include certificates and passwords. Initial authenticator content is the actual content of the authenticator (e.g., the initial password). In contrast, the requirements for authenticator content contain specific criteria or characteristics (e.g., minimum password length). Developers may deliver system components with factory default authentication credentials (i.e., passwords) to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant risk. The requirement to protect individual authenticators may be implemented via control PL-4 or PS-6 for authenticators in the possession of individuals and by controls AC-3, AC-6, and SC-28 for authenticators stored in organizational systems, including passwords stored in hashed or encrypted formats or files containing encrypted or hashed passwords accessible with administrator privileges.

Systems support authenticator management by organization-defined settings and restrictions for various authenticator characteristics (e.g., minimum password length, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication). Actions can be taken to safeguard individual authenticators, including maintaining possession of authenticators, not sharing authenticators with others, and immediately reporting lost, stolen, or compromised authenticators. Authenticator management includes issuing and revoking authenticators for temporary access when no longer needed.

<ins>Related Controls</ins>: AC-3, AC-6, CM-6, IA-2, IA-4, IA-7, IA-8, IA-9, MA-4, PE-2, PL-4, SC-12, SC-13.

<ins>Control Enhancements</ins>:

* (1) AUTHENTICATOR MANAGEMENT / PASSWORD-BASED AUTHENTICATION<br>
**For password-based authentication:**
    * **(a) Maintain a list of commonly-used, expected, or compromised passwords and update the list [ _Assignment: organization-defined frequency_ ] and when organizational passwords are suspected to have been compromised directly or indirectly;**
    * **(b) Verify, when users create or update passwords, that the passwords are not found on the list of commonly-used, expected, or compromised passwords in IA-5(1)(a);**
    * **(c) Transmit passwords only over cryptographically-protected channels;**
    * **(d) Store passwords using an approved salted key derivation function, preferably using a keyed hash;**
    * **(e) Require immediate selection of a new password upon account recovery;**
    * **(f) Allow user selection of long passwords and passphrases, including spaces and all printable characters;**
    * **(g) Employ automated tools to assist the user in selecting strong password authenticators; and**
    * **(h) Enforce the following composition and complexity rules: [ Assignment: organization-defined composition and complexity rules ].**

    <ins>Discussion</ins>: Password-based authentication applies to passwords regardless of whether they are used in single-factor or multi-factor authentication. Long passwords or passphrases are preferable over shorter passwords. Enforced composition rules provide marginal security benefits while decreasing usability. However, organizations may choose to establish certain rules for password generation (e.g., minimum character length for long passwords) under certain circumstances and can enforce this requirement in IA-5(1)(h). Account recovery can occur, for example, in situations when a password is forgotten. Cryptographically protected passwords include salted one-way cryptographic hashes of passwords. The list of commonly used, compromised, or expected passwords includes passwords obtained from previous breach corpuses, dictionary words, and repetitive or sequential characters. The list includes context-specific words, such as the name of the service, username, and derivatives thereof.

    <ins>Related Controls</ins>: IA-6.

* (2) AUTHENTICATOR MANAGEMENT / PUBLIC KEY-BASED AUTHENTICATION<br>
    * **(a) For public key-based authentication:**
        * **(1) Enforce authorized access to the corresponding private key; and**
        * **(2) Map the authenticated identity to the account of the individual or group; and**
    * **(b) When public key infrastructure (PKI) is used:**
        * **(1) Validate certificates by constructing and verifying a certification path to an accepted trust anchor, including checking certificate status information; and**
        * **(2) Implement a local cache of revocation data to support path discovery and validation.**

    <ins>Discussion</ins>: Public key cryptography is a valid authentication mechanism for individuals, machines, and devices. For PKI solutions, status information for certification paths includes certificate revocation lists or certificate status protocol responses. For PIV cards, certificate validation involves the construction and verification of a certification path to the Common Policy Root trust anchor, which includes certificate policy processing. Implementing a local cache of revocation data to support path discovery and validation also supports system availability in situations where organizations are unable to access revocation information via the network.

    <ins>Related Controls</ins>: IA-3, SC-17.

* (3) AUTHENTICATOR MANAGEMENT / IN-PERSON OR TRUSTED EXTERNAL PARTY REGISTRATION<br>
[Withdrawn: Incorporated into IA-12(4).]

* (4) AUTHENTICATOR MANAGEMENT / AUTOMATED SUPPORT FOR PASSWORD STRENGTH DETERMINATION<br>
[Withdrawn: Incorporated into IA -5(1).]

* (5) AUTHENTICATOR MANAGEMENT / CHANGE AUTHENTICATORS PRIOR TO DELIVERY<br>
**Require developers and installers of system components to provide unique authenticators or change default authenticators prior to delivery and installation.**

    <ins>Discussion</ins>: Changing authenticators prior to the delivery and installation of system components extends the requirement for organizations to change default authenticators upon system installation by requiring developers and/or installers to provide unique authenticators or change default authenticators for system components prior to delivery and/or installation. However, it typically does not apply to developers of commercial off-the- shelf information technology products. Requirements for unique authenticators can be included in acquisition documents prepared by organizations when procuring systems or system components.

    <ins>Related Controls</ins>: None.

* (6) AUTHENTICATOR MANAGEMENT / PROTECTION OF AUTHENTICATORS<br>
**Protect authenticators commensurate with the security category of the information to which use of the authenticator permits access.**

    <ins>Discussion</ins>: For systems that contain multiple security categories of information without reliable physical or logical separation between categories, authenticators used to grant access to the systems are protected commensurate with the highest security category of information on the systems. Security categories of information are determined as part of the security categorization process.

    <ins>Related Controls</ins>: RA-2.

* (7) AUTHENTICATOR MANAGEMENT / NO EMBEDDED UNENCRYPTED STATIC AUTHENTICATORS<br>
**Ensure that unencrypted static authenticators are not embedded in applications or other forms of static storage.**

    <ins>Discussion</ins>: In addition to applications, other forms of static storage include access scripts and function keys. Organizations exercise caution when determining whether embedded or stored authenticators are in encrypted or unencrypted form. If authenticators are used in the manner stored, then those representations are considered unencrypted authenticators.

    <ins>Related Controls</ins>: None.

* (8) AUTHENTICATOR MANAGEMENT / MULTIPLE SYSTEM ACCOUNTS<br>
**Implement [ _Assignment: organization-defined security controls_ ] to manage the risk of compromise due to individuals having accounts on multiple systems.**

    <ins>Discussion</ins>: When individuals have accounts on multiple systems and use the same authenticators such as passwords, there is the risk that a compromise of one account may lead to the compromise of other accounts. Alternative approaches include having different authenticators (passwords) on all systems, employing a single sign-on or federation mechanism, or using some form of one-time passwords on all systems. Organizations can also use rules of behavior (see PL-4) and access agreements (see PS-6) to mitigate the risk of multiple system accounts.

    <ins>Related Controls</ins>: PS-6.

* (9) AUTHENTICATOR MANAGEMENT / FEDERATED CREDENTIAL MANAGEMENT<br>
**Use the following external organizations to federate credentials: [ Assignment: organization-defined external organizations ].**

    <ins>Discussion</ins>: Federation provides organizations with the capability to authenticate individuals and devices when conducting cross-organization activities involving the processing, storage, or transmission of information. Using a specific list of approved external organizations for authentication helps to ensure that those organizations are vetted and trusted.

    <ins>Related Controls</ins>: AU-7, AU-16.

* (10) AUTHENTICATOR MANAGEMENT / DYNAMIC CREDENTIAL BINDING<br>
**Bind identities and authenticators dynamically using the following rules: [ Assignment: organization-defined binding rules ].**

    <ins>Discussion</ins>: Authentication requires some form of binding between an identity and the authenticator that is used to confirm the identity. In conventional approaches, binding is established by pre-provisioning both the identity and the authenticator to the system. For example, the binding between a username (i.e., identity) and a password (i.e., authenticator) is accomplished by provisioning the identity and authenticator as a pair in the system. New authentication techniques allow the binding between the identity and the authenticator to be implemented external to a system. For example, with smartcard credentials, the identity and authenticator are bound together on the smartcard. Using these credentials, systems can authenticate identities that have not been pre-provisioned, dynamically provisioning the identity after authentication. In these situations, organizations can anticipate the dynamic provisioning of identities. Pre-established trust relationships and mechanisms with appropriate authorities to validate identities and related credentials are essential.

    <ins>Related Controls</ins>: AU-16, IA-5.

* (11) AUTHENTICATOR MANAGEMENT / HARDWARE TOKEN-BASED AUTHENTICATION<br>
[Withdrawn: Incorporated into IA -2(1) and IA -2(2).]

* (12) AUTHENTICATOR MANAGEMENT / BIOMETRIC AUTHENTICATION PERFORMANCE<br>
**For biometric-based authentication, employ mechanisms that satisfy the following biometric quality requirements [ _Assignment: organization-defined biometric quality requirements_ ].**

    <ins>Discussion</ins>: Unlike password-based authentication, which provides exact matches of user-input passwords to stored passwords, biometric authentication does not provide exact matches. Depending on the type of biometric and the type of collection mechanism, there is likely to be some divergence from the presented biometric and the stored biometric that serves as the basis for comparison. Matching performance is the rate at which a biometric algorithm correctly results in a match for a genuine user and rejects other users. Biometric performance requirements include the match rate, which reflects the accuracy of the biometric matching algorithm used by a system.

    <ins>Related Controls</ins>: AC-7.

* (13) AUTHENTICATOR MANAGEMENT / EXPIRATION OF CACHED AUTHENTICATORS<br>
**Prohibit the use of cached authenticators after [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: Cached authenticators are used to authenticate to the local machine when the network is not available. If cached authentication information is out of date, the validity of the authentication information may be questionable.

    <ins>Related Controls</ins>: None.

* (14) AUTHENTICATOR MANAGEMENT / MANAGING CONTENT OF PKI TRUST STORES<br>
**For PKI-based authentication, employ an organization-wide methodology for managing the content of PKI trust stores installed across all platforms, including networks, operating systems, browsers, and applications.**

    <ins>Discussion</ins>: An organization-wide methodology for managing the content of PKI trust stores helps improve the accuracy and currency of PKI-based authentication credentials across the organization.

    <ins>Related Controls</ins>: None.

* (15) AUTHENTICATOR MANAGEMENT / GSA-APPROVED PRODUCTS AND SERVICES<br>
**Use only General Services Administration-approved products and services for identity, credential, and access management.**

    <ins>Discussion</ins>: General Services Administration (GSA)-approved products and services are products and services that have been approved through the GSA conformance program, where applicable, and posted to the GSA Approved Products List. GSA provides guidance for teams to design and build functional and secure systems that comply with Federal Identity, Credential, and Access Management (FICAM) policies, technologies, and implementation patterns.

    <ins>Related Controls</ins>: None.

* (16) AUTHENTICATOR MANAGEMENT / IN-PERSON OR TRUSTED EXTERNAL PARTY AUTHENTICATOR ISSUANCE<br>
**Require that the issuance of [ _Assignment: organization-defined types of and/or specific authenticators_ ] be conducted [ _Selection: in person; by a trusted external party_ ] before [ _Assignment: organization-defined registration authority_ ] with authorization by [ _Assignment: organization-defined personnel or roles_ ].**

    <ins>Discussion</ins>: Issuing authenticators in person or by a trusted external party enhances and reinforces the trustworthiness of the identity proofing process.

    <ins>Related Controls</ins>: IA-12.

* (17) AUTHENTICATOR MANAGEMENT / PRESENTATION ATTACK DETECTION FOR BIOMETRIC AUTHENTICATORS<br>
**Employ presentation attack detection mechanisms for biometric-based authentication.**

    <ins>Discussion</ins>: Biometric characteristics do not constitute secrets. Such characteristics can be obtained by online web accesses, taking a picture of someone with a camera phone to obtain facial images with or without their knowledge, lifting from objects that someone has touched (e.g., a latent fingerprint), or capturing a high-resolution image (e.g., an iris pattern). Presentation attack detection technologies including liveness detection, can mitigate the risk of these types of attacks by making it difficult to produce artifacts intended to defeat the biometric sensor.

    <ins>Related Controls</ins>: AC-7.

* (18) AUTHENTICATOR MANAGEMENT / PASSWORD MANAGERS<br>
    * **(a) Employ [ _Assignment: organization-defined password managers_ ] to generate and manage passwords; and**
    * **(b) Protect the passwords using [ _Assignment: organization-defined controls_ ].**

    <ins>Discussion</ins>: For systems where static passwords are employed, it is often a challenge to ensure that the passwords are suitably complex and that the same passwords are not employed on multiple systems. A password manager is a solution to this problem as it automatically generates and stores strong and different passwords for various accounts. A potential risk of using password managers is that adversaries can target the collection of passwords generated by the password manager. Therefore, the collection of passwords requires protection including encrypting the passwords (see IA-5(1)(d)) and storing the collection offline in a token.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3], [FIPS 180-4], [FIPS 201-2], [FIPS 202], [SP 800-63-3], [SP 800-73-4], [SP 800-76-2], [SP 800-78-4], [IR 7539], [IR 7817], [IR 7849], [IR 7870], [IR 8040].
