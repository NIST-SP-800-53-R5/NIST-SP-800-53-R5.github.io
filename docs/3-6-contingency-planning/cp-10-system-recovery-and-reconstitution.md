---
layout: page
title: -- CP-10 SYSTEM RECOVERY AND RECONSTITUTION 
parent: . 3.6 CONTINGENCY PLANNING 
nav_order: 36100 
---

## CP-10 SYSTEM RECOVERY AND RECONSTITUTION

<ins>Control</ins>: Provide for the recovery and reconstitution of the system to a known state within [ _Assignment: organization-defined time period consistent with recovery time and recovery point objectives_ ] after a disruption, compromise, or failure.

<ins>Discussion</ins>: Recovery is executing contingency plan activities to restore organizational mission and business functions. Reconstitution takes place following recovery and includes activities for returning systems to fully operational states. Recovery and reconstitution operations reflect mission and business priorities; recovery point, recovery time, and reconstitution objectives; and organizational metrics consistent with contingency plan requirements. Reconstitution includes the deactivation of interim system capabilities that may have been needed during recovery operations. Reconstitution also includes assessments of fully restored system capabilities, reestablishment of continuous monitoring activities, system reauthorization (if required), and activities to prepare the system and organization for future disruptions, breaches, compromises, or failures. Recovery and reconstitution capabilities can include automated mechanisms and manual procedures. Organizations establish recovery time and recovery point objectives as part of contingency planning.

<ins>Related Controls</ins>: CP-2, CP-4, CP-6, CP-7, CP-9, IR-4, SA-8, SC-24, SI-13.

<ins>Control Enhancements</ins>:

* (1) SYSTEM RECOVERY AND RECONSTITUTION / CONTINGENCY PLAN TESTING<br>
[Withdrawn: Incorporated into CP-4.]

* (2) SYSTEM RECOVERY AND RECONSTITUTION / TRANSACTION RECOVERY<br>
**Implement transaction recovery for systems that are transaction-based.**

    <ins>Discussion</ins>: Transaction-based systems include database management systems and transaction processing systems. Mechanisms supporting transaction recovery include transaction rollback and transaction journaling.

    <ins>Related Controls</ins>: None.

* (3) SYSTEM RECOVERY AND RECONSTITUTION / COMPENSATING SECURITY CONTROLS<br>
[Withdrawn: Addressed through tailoring procedures.]

* (4) SYSTEM RECOVERY AND RECONSTITUTION / RESTORE WITHIN TIME PERIOD<br>
**Provide the capability to restore system components within [_ Assignment: organization-defined restoration time periods_ ] from configuration-controlled and integrity-protected information representing a known, operational state for the components.**

    <ins>Discussion</ins>: Restoration of system components includes reimaging, which restores the components to known, operational states.

    <ins>Related Controls</ins>: CM-2, CM-6.

* (5) SYSTEM RECOVERY AND RECONSTITUTION / FAILOVER CAPABILITY<br>
[Withdrawn: Incorporated into SI-13.]

* (6) SYSTEM RECOVERY AND RECONSTITUTION / COMPONENT PROTECTION<br>
**Protect system components used for recovery and reconstitution.**

    <ins>Discussion</ins>: Protection of system recovery and reconstitution components (i.e., hardware, firmware, and software) includes physical and technical controls. Backup and restoration components used for recovery and reconstitution include router tables, compilers, and other system software.

    <ins>Related Controls</ins>: AC-3, AC-6, MP-2, MP-4, PE-3, PE-6.

<ins>References</ins>: [SP 800-34].
