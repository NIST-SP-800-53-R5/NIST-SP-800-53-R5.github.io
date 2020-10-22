---
layout: default
title:  -- AC-7 UNSUCCESSFUL LOGON ATTEMPTS
parent: . 3.1 ACCESS CONTROL 
nav_order: 1570
---

## AC-7 UNSUCCESSFUL LOGON ATTEMPTS

<ins>Control</ins>: 
* a. Enforce a limit of [ _Assignment: organization-defined number_ ] consecutive invalid logon attempts by a user during a [ _Assignment: organization-defined time period_ ]; and
* b. Automatically [ _Selection (one or more): lock the account or node for an [ Assignment: organization-defined time period ]; lock the account or node until released by an administrator; delay next logon prompt per [ Assignment: organization-defined delay algorithm ]; notify system administrator; take other [ Assignment: organization-defined action ]_] when the maximum number of unsuccessful attempts is exceeded.

<ins>Discussion</ins>: The need to limit unsuccessful logon attempts and take subsequent action when the maximum number of attempts is exceeded applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by systems are usually temporary and automatically release after a predetermined, organization-defined time period. If a delay algorithm is selected, organizations may employ different algorithms for different components of the system based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at the operating system and the application levels. Organization-defined actions that may be taken when the number of allowed consecutive invalid logon attempts is exceeded include prompting the user to answer a secret question in addition to the username and password, invoking a lockdown mode with limited user capabilities (instead of full lockout), allowing users to only logon from specified Internet Protocol (IP) addresses, requiring a CAPTCHA to prevent automated attacks, or applying user profiles such as location, time of day, IP address, device, or Media Access Control (MAC) address. If automatic system lockout or execution of a delay algorithm is not implemented in support of the availability objective, organizations consider a combination of other actions to help prevent brute force attacks. In addition to the above, organizations can prompt users to respond to a secret question before the number of allowed unsuccessful logon attempts is exceeded. Automatically unlocking an account after a specified period of time is generally not permitted. However, exceptions may be required based on operational mission or need.

<ins>Related Controls</ins>: AC-2, AC-9, AU-2, AU-6, IA-5.

<ins>Control Enhancements</ins>:

* (1) UNSUCCESSFUL LOGON ATTEMPTS / AUTOMATIC ACCOUNT LOCK<br>
    [Withdrawn: Incorporated into AC-7.]

* (2) UNSUCCESSFUL LOGON ATTEMPTS / PURGE OR WIPE MOBILE DEVICE<br>
**Purge or wipe information from [ _Assignment: organization-defined mobile devices_ ] based on [ _Assignment: organization-defined purging or wiping requirements and techniques_ ] after [ _Assignment: organization-defined number_ ] consecutive, unsuccessful device logon attempts.**

    <ins>Discussion</ins>:  A mobile device is a computing device that has a small form factor such that it can be carried by a single individual; is designed to operate without a physical connection; possesses local, non-removable or removable data storage; and includes a self-contained power source. Purging or wiping the device applies only to mobile devices for which the organization-defined number of unsuccessful logons occurs. The logon is to the mobile device, not to any one account on the device. Successful logons to accounts on mobile devices reset the unsuccessful logon count to zero. Purging or wiping may be unnecessary if the information on the device is protected with sufficiently strong encryption mechanisms.

    <ins>Related Controls</ins>: AC-19, MP-5, MP-6.

* (3) UNSUCCESSFUL LOGON ATTEMPTS / BIOMETRIC ATTEMPT LIMITING<br>
**Limit the number of unsuccessful biometric logon attempts to [ _Assignment: organization-defined number_ ].**

    <ins>Discussion</ins>: Biometrics are probabilistic in nature. The ability to successfully authenticate can be impacted by many factors, including matching performance and presentation attack detection mechanisms. Organizations select the appropriate number of attempts for users based on organizationally-defined factors.

    <ins>Related Controls</ins>: IA-3.

* (4) UNSUCCESSFUL LOGON ATTEMPTS / USE OF ALTERNATE AUTHENTICATION FACTOR<br>
    * **(a) Allow the use of [ _Assignment: organization-defined authentication factors_ ] that are different from the primary authentication factors after the number of organization-defined consecutive invalid logon attempts have been exceeded; and**
    * **(b) Enforce a limit of [ _Assignment: organization-defined number_ ] consecutive invalid logon attempts through use of the alternative factors by a user during a [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: The use of alternate authentication factors supports the objective of availability and allows a user who has inadvertently been locked out to use additional authentication factors to bypass the lockout.

    <ins>Related Controls</ins>: IA-3.

<ins>References</ins>: [SP 800-63-3], [SP 800-124 ].

