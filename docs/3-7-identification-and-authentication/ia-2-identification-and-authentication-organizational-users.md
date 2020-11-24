---
layout: page
title: -- IA-2 IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS)
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 3720 
---

## IA-2 IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS)

<ins>Control</ins>: Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

<ins>Discussion</ins>: Organizations can satisfy the identification and authentication requirements by complying with the requirements in [HSPD 12]. Organizational users include employees or individuals who organizations consider to have an equivalent status to employees (e.g., contractors and guest researchers). Unique identification and authentication of users applies to all accesses other than those that are explicitly identified in AC-14 and that occur through the authorized use of group authenticators without individual authentication. Since processes execute on behalf of groups and roles, organizations may require unique identification of individuals in group accounts or for detailed accountability of individual activity.

Organizations employ passwords, physical authenticators, or biometrics to authenticate user identities or, in the case of multi-factor authentication, some combination thereof. Access to organizational systems is defined as either local access or network access. Local access is any access to organizational systems by users or processes acting on behalf of users, where access is obtained through direct connections without the use of networks. Network access is access to organizational systems by users (or processes acting on behalf of users) where access is obtained through network connections (i.e., nonlocal accesses). Remote access is a type of network access that involves communication through external networks. Internal networks include local area networks and wide area networks.

The use of encrypted virtual private networks for network connections between organization- controlled endpoints and non-organization-controlled endpoints may be treated as internal networks with respect to protecting the confidentiality and integrity of information traversing the network. Identification and authentication requirements for non-organizational users are described in IA-8.

<ins>Related Controls</ins>: AC-2, AC-3, AC-4, AC-14, AC-17, AC-18, AU-1, AU-6, IA-4, IA-5, IA-8, MA-4, MA- 5, PE-2, PL-4, SA-4, SA-8.

<ins>Control Enhancements</ins>:

* (1) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / MULTI-FACTOR AUTHENTICATION TO PRIVILEGED ACCOUNTS<br>
**Implement multi-factor authentication for access to privileged accounts.**

    <ins>Discussion</ins>: Multi-factor authentication requires the use of two or more different factors to achieve authentication. The authentication factors are defined as follows: something you know (e.g., a personal identification number [PIN]), something you have (e.g., a physical authenticator such as a cryptographic private key), or something you are (e.g., a biometric). Multi-factor authentication solutions that feature physical authenticators include hardware authenticators that provide time-based or challenge-response outputs and smart cards such as the U.S. Government Personal Identity Verification (PIV) card or the Department of Defense (DoD) Common Access Card. In addition to authenticating users at the system level (i.e., at logon), organizations may employ authentication mechanisms at the application level, at their discretion, to provide increased security. Regardless of the type of access (i.e., local, network, remote), privileged accounts are authenticated using multi-factor options appropriate for the level of risk. Organizations can add additional security measures, such as additional or more rigorous authentication mechanisms, for specific types of access.

    <ins>Related Controls</ins>: AC-5, AC-6.

* (2) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / MULTI-FACTOR AUTHENTICATION TO NON-PRIVILEGED ACCOUNTS<br>
**Implement multi-factor authentication for access to non-privileged accounts.**

    <ins>Discussion</ins>: Multi-factor authentication requires the use of two or more different factors to achieve authentication. The authentication factors are defined as follows: something you know (e.g., a personal identification number [PIN]), something you have (e.g., a physical authenticator such as a cryptographic private key), or something you are (e.g., a biometric). Multi-factor authentication solutions that feature physical authenticators include hardware authenticators that provide time-based or challenge-response outputs and smart cards such as the U.S. Government Personal Identity Verification card or the DoD Common Access Card. In addition to authenticating users at the system level, organizations may also employ authentication mechanisms at the application level, at their discretion, to provide increased information security. Regardless of the type of access (i.e., local, network, remote), non- privileged accounts are authenticated using multi-factor options appropriate for the level of risk. Organizations can provide additional security measures, such as additional or more rigorous authentication mechanisms, for specific types of access.

    <ins>Related Controls</ins>: AC-5.

* (3) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / LOCAL ACCESS TO PRIVILEGED ACCOUNTS<br>
[Withdrawn: Incorporated into IA -2(1).]

* (4) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / LOCAL ACCESS TO NON-
PRIVILEGED ACCOUNTS<br>
[Withdrawn: Incorporated into IA -2(2).]

* (5) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / INDIVIDUAL AUTHENTICATION
WITH GROUP AUTHENTICATION<br>
**When shared accounts or authenticators are employed, require users to be individually authenticated before granting access to the shared accounts or resources.**

    <ins>Discussion</ins>: Individual authentication prior to shared group authentication mitigates the risk of using group accounts or authenticators.

    <ins>Related Controls</ins>: None.

* (6) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / ACCESS TO ACCOUNTS — SEPARATE DEVICE<br>
**Implement multi-factor authentication for [ _Selection (one or more): local; network; remote_ ] access to [ _Selection (one or more): privileged accounts; non-privileged accounts_ ] such that:**
    * **(a) One of the factors is provided by a device separate from the system gaining access; and**
    * **(b) The device meets [ _Assignment: organization-defined strength of mechanism requirements_ ].**

    <ins>Discussion</ins>: The purpose of requiring a device that is separate from the system to which the user is attempting to gain access for one of the factors during multi-factor authentication is to reduce the likelihood of compromising authenticators or credentials stored on the system. Adversaries may be able to compromise such authenticators or credentials and subsequently impersonate authorized users. Implementing one of the factors on a separate device (e.g., a hardware token), provides a greater strength of mechanism and an increased level of assurance in the authentication process.

    <ins>Related Controls</ins>: AC-6.

* (7) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / ACCESS TO NON-PRIVILEGED ACCOUNTS — SEPARATE DEVICE<br>
[Withdrawn: Incorporated into IA -2(6).]

* (8) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / ACCESS TO ACCOUNTS — REPLAY RESISTANT<br>
**Implement replay-resistant authentication mechanisms for access to [ _Selection (one or more): privileged accounts; non-privileged accounts_ ].**

    <ins>Discussion</ins>: Authentication processes resist replay attacks if it is impractical to achieve successful authentications by replaying previous authentication messages. Replay-resistant techniques include protocols that use nonces or challenges such as time synchronous or cryptographic authenticators.

    <ins>Related Controls</ins>: None.

* (9) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / NETWORK ACCESS TO NON-PRIVILEGED ACCOUNTS — REPLAY RESISTANT<br>
[Withdrawn: Incorporated into IA -2(8).]

* (10) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / SINGLE SIGN-ON<br>
**Provide a single sign-on capability for [ _Assignment: organization-defined system accounts and services_ ].**

    <ins>Discussion</ins>: Single sign-on enables users to log in once and gain access to multiple system resources. Organizations consider the operational efficiencies provided by single sign-on capabilities with the risk introduced by allowing access to multiple systems via a single authentication event. Single sign-on can present opportunities to improve system security, for example by providing the ability to add multi-factor authentication for applications and systems (existing and new) that may not be able to natively support multi-factor authentication.

    <ins>Related Controls</ins>: None.

* (11) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / REMOTE ACCESS — SEPARATE DEVICE<br>
[Withdrawn: Incorporated into IA -2(6).]

* (12) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / ACCEPTANCE OF PIV CREDENTIALS<br>
**Accept and electronically verify Personal Identity Verification-compliant credentials.**

    <ins>Discussion</ins>: Acceptance of Personal Identity Verification (PIV)-compliant credentials applies to organizations implementing logical access control and physical access control systems. PIV-compliant credentials are those credentials issued by federal agencies that conform to FIPS Publication 201 and supporting guidance documents. The adequacy and reliability of PIV card issuers are authorized using [SP 800-79-2]. Acceptance of PIV-compliant credentials includes derived PIV credentials, the use of which is addressed in [SP 800-166]. The DOD Common Access Card (CAC) is an example of a PIV credential.

    <ins>Related Controls</ins>: None.

* (13) IDENTIFICATION AND AUTHENTICATION (ORGANIZATIONAL USERS) / OUT-OF-BAND AUTHENTICATION<br>
**Implement the following out-of-band authentication mechanisms under [ _Assignment: organization-defined conditions_ ]: [ _Assignment: organization-defined out-of-band authentication_ ].**

    <ins>Discussion</ins>: Out-of-band authentication refers to the use of two separate communication paths to identify and authenticate users or devices to an information system. The first path (i.e., the in-band path) is used to identify and authenticate users or devices and is generally the path through which information flows. The second path (i.e., the out-of-band path) is used to independently verify the authentication and/or requested action. For example, a user authenticates via a notebook computer to a remote server to which the user desires access and requests some action of the server via that communication path. Subsequently, the server contacts the user via the user’s cell phone to verify that the requested action originated from the user. The user may confirm the intended action to an individual on the telephone or provide an authentication code via the telephone. Out-of-band authentication can be used to mitigate actual or suspected “man-in the-middle” attacks. The conditions or criteria for activation include suspicious activities, new threat indicators, elevated threat levels, or the impact or classification level of information in requested transactions.

    <ins>Related Controls</ins>: IA-10, IA -11, SC-37.

<ins>References</ins>: [FIPS 140-3], [FIPS 201-2], [FIPS 202], [SP 800-63-3], [SP 800-73-4], [SP 800-76-2], [SP 800-78-4], [SP 800-79-2], [SP 800-156], [SP 800-166], [IR 7539], [IR 7676], [IR 7817], [IR 7849], [IR 7870], [IR 7874], [IR 7966].

