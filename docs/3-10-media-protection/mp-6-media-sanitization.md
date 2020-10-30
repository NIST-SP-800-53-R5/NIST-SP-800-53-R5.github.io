---
layout: page
title: -- MP-6 MEDIA SANITIZATION 
parent: . 3.10 MEDIA PROTECTION 
nav_order: 31060 
---

## MP-6 MEDIA SANITIZATION

<ins>Control</ins>:
* a. Sanitize [ _Assignment: organization-defined system media_ ] prior to disposal, release out of organizational control, or release for reuse using [ _Assignment: organization-defined sanitization techniques and procedures_ ]; and
* b. Employ sanitization mechanisms with the strength and integrity commensurate with the security category or classification of the information.

<ins>Discussion</ins>: Media sanitization applies to all digital and non-digital system media subject to disposal or reuse, whether or not the media is considered removable. Examples include digital media in scanners, copiers, printers, notebook computers, workstations, network components, mobile devices, and non-digital media (e.g., paper and microfilm). The sanitization process removes information from system media such that the information cannot be retrieved or reconstructed. Sanitization techniques—including clearing, purging, cryptographic erase, de-identification of personally identifiable information, and destruction—prevent the disclosure of information to unauthorized individuals when such media is reused or released for disposal. Organizations determine the appropriate sanitization methods, recognizing that destruction is sometimes necessary when other methods cannot be applied to media requiring sanitization. 

Organizations use discretion on the employment of approved sanitization techniques and procedures for media that contains information deemed to be in the public domain or publicly releasable or information deemed to have no adverse impact on organizations or individuals if released for reuse or disposal. Sanitization of non-digital media includes destruction, removing a classified appendix from an otherwise unclassified document, or redacting selected sections or words from a document by obscuring the redacted sections or words in a manner equivalent in effectiveness to removing them from the document. NSA standards and policies control the sanitization process for media that contains classified information. NARA policies control the sanitization process for controlled unclassified information.

<ins>Related Controls</ins>: AC-3, AC-7, AU-11, MA-2, MA-3, MA-4, MA-5, PM-22, SI-12, SI-18, SI-19, SR-11.

<ins>Control Enhancements</ins>:

* (1) MEDIA SANITIZATION / REVIEW, APPROVE, TRACK, DOCUMENT, AND VERIFY<br>
**Review, approve, track, document, and verify media sanitization and disposal actions.**

    <ins>Discussion</ins>: Organizations review and approve media to be sanitized to ensure compliance with records retention policies. Tracking and documenting actions include listing personnel who reviewed and approved sanitization and disposal actions, types of media sanitized, files stored on the media, sanitization methods used, date and time of the sanitization actions, personnel who performed the sanitization, verification actions taken and personnel who performed the verification, and the disposal actions taken. Organizations verify that the sanitization of the media was effective prior to disposal.

    <ins>Related Controls: None.

* (2) MEDIA SANITIZATION / EQUIPMENT TESTING<br>
**Test sanitization equipment and procedures [ _Assignment: organization-defined frequency_ ] to ensure that the intended sanitization is being achieved.**

    <ins>Discussion</ins>: esting of sanitization equipment and procedures may be conducted by qualified and authorized external entities, including federal agencies or external service providers.

    <ins>Related Controls</ins>: None.

* (3) MEDIA SANITIZATION / NONDESTRUCTIVE TECHNIQUES<br>
**Apply nondestructive sanitization techniques to portable storage devices prior to connecting such devices to the system under the following circumstances: [ _Assignment: organization-defined circumstances requiring sanitization of portable storage devices_ ].**

    <ins>Discussion</ins>: Portable storage devices include external or removable hard disk drives (e.g., solid state, magnetic), optical discs, magnetic or optical tapes, flash memory devices, flash memory cards, and other external or removable disks. Portable storage devices can be obtained from untrustworthy sources and contain malicious code that can be inserted into or transferred to organizational systems through USB ports or other entry portals. While scanning storage devices is recommended, sanitization provides additional assurance that such devices are free of malicious code. Organizations consider nondestructive sanitization of portable storage devices when the devices are purchased from manufacturers or vendors prior to initial use or when organizations cannot maintain a positive chain of custody for the devices.

    <ins>Related Controls</ins>: None.

* (4) MEDIA SANITIZATION / CONTROLLED UNCLASSIFIED INFORMATION<br>
[Withdrawn: Incorporated into MP-6.]

* (5) MEDIA SANITIZATION / CLASSIFIED INFORMATION<br>
[Withdrawn: Incorporated into MP-6.]

* (6) MEDIA SANITIZATION / MEDIA DESTRUCTION<br>
[Withdrawn: Incorporated into MP-6.]

* (7) MEDIA SANITIZATION / DUAL AUTHORIZATION<br>
**Enforce dual authorization for the sanitization of [ _Assignment: organization-defined system media_ ].**

    <ins>Discussion</ins>: Organizations employ dual authorization to help ensure that system media sanitization cannot occur unless two technically qualified individuals conduct the designated task. Individuals who sanitize system media possess sufficient skills and expertise to determine if the proposed sanitization reflects applicable federal and organizational standards, policies, and procedures. Dual authorization also helps to ensure that sanitization occurs as intended, protecting against errors and false claims of having performed the sanitization actions. Dual authorization may also be known as two-person control. To reduce the risk of collusion, organizations consider rotating dual authorization duties to other individuals.

    <ins>Related Controls</ins>: AC-3, MP-2.

* (8) MEDIA SANITIZATION / REMOTE PURGING OR WIPING OF INFORMATION<br>
**Provide the capability to purge or wipe information from [ _Assignment: organization-defined systems or system components_ ] [ _Selection: remotely; under the following conditions: [ Assignment: organization-defined conditions ]_].**

    <ins>Discussion</ins>: Remote purging or wiping of information protects information on organizational systems and system components if systems or components are obtained by unauthorized individuals. Remote purge or wipe commands require strong authentication to help mitigate the risk of unauthorized individuals purging or wiping the system, component, or device. The purge or wipe function can be implemented in a variety of ways, including by overwriting data or information multiple times or by destroying the key necessary to decrypt encrypted data.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [32 CFR 2002], [OMB A-130], [NARA CUI], [FIPS 199], [SP 800-60-1], [SP 800-60-2], [SP 800-88], [SP 800-124], [IR 8023], [NSA MEDIA].
