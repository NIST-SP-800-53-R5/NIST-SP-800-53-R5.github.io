---
layout: page
title: -- SI-19 DE-IDENTIFICATION 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319190 
---

## SI-19 DE-IDENTIFICATION

<ins>Control</ins>:
   
* a. Remove the following elements of personally identifiable information from datasets: [ _Assignment: organization-defined elements of personally identifiable information_ ]; and
* b. Evaluate [ _Assignment: organization-defined frequency_ ] for effectiveness of de-identification.

<ins>Discussion</ins>: De-identification is the general term for the process of removing the association between a set of identifying data and the data subject. Many datasets contain information about individuals that can be used to distinguish or trace an individual’s identity, such as name, social security number, date and place of birth, mother’s maiden name, or biometric records. Datasets may also contain other information that is linked or linkable to an individual, such as medical, educational, financial, and employment information. Personally identifiable information is removed from datasets by trained individuals when such information is not (or no longer) necessary to satisfy the requirements envisioned for the data. For example, if the dataset is only used to produce aggregate statistics, the identifiers that are not needed for producing those statistics are removed. Removing identifiers improves privacy protection since information that is removed cannot be inadvertently disclosed or improperly used. Organizations may be subject to specific de-identification definitions or methods under applicable laws, regulations, or policies. Re-identification is a residual risk with de-identified data. Re-identification attacks can vary, including combining new datasets or other improvements in data analytics. Maintaining awareness of potential attacks and evaluating for the effectiveness of the de-identification over time support the management of this residual risk.

<ins>Related Controls</ins>: MP-6 , PM-22 , PM-23 , PM-24 , RA-2 , SI-12.

<ins>Control Enhancements</ins>:
   
* (1) DE-IDENTIFICATION / COLLECTION<br>
**De-identify the dataset upon collection by not collecting personally identifiable information.**

    <ins>Discussion</ins>: If a data source contains personally identifiable information but the information will not be used, the dataset can be de-identified when it is created by not collecting the data elements that contain the personally identifiable information. For example, if an organization does not intend to use the social security number of an applicant, then application forms do not ask for a social security number.
    
    <ins>Related Controls</ins>: None.
   
* (2) DE-IDENTIFICATION / ARCHIVING<br>
**Prohibit archiving of personally identifiable information elements if those elements in a dataset will not be needed after the dataset is archived.**

    <ins>Discussion</ins>: Datasets can be archived for many reasons. The envisioned purposes for the archived dataset are specified, and if personally identifiable information elements are not required, the elements are not archived. For example, social security numbers may have been collected for record linkage, but the archived dataset may include the required elements from the linked records. In this case, it is not necessary to archive the social security numbers.

    <ins>Related Controls</ins>: None.
   
* (3) DE-IDENTIFICATION / RELEASE<br>
**Remove personally identifiable information elements from a dataset prior to its release if those elements in the dataset do not need to be part of the data release.**

    <ins>Discussion</ins>: Prior to releasing a dataset, a data custodian considers the intended uses of the dataset and determines if it is necessary to release personally identifiable information. If the personally identifiable information is not necessary, the information can be removed using de-identification techniques.

    <ins>Related Controls</ins>: None.
   
* (4) DE-IDENTIFICATION / REMOVAL, MASKING, ENCRYPTION, HASHING, OR REPLACEMENT OF DIRECT IDENTIFIERS<br>
**Remove, mask, encrypt, hash, or replace direct identifiers in a dataset.**

    <ins>Discussion</ins>: There are many possible processes for removing direct identifiers from a dataset. Columns in a dataset that contain a direct identifier can be removed. In masking, the direct identifier is transformed into a repeating character, such as XXXXXX or 999999. Identifiers can be encrypted or hashed so that the linked records remain linked. In the case of encryption or hashing, algorithms are employed that require the use of a key, including the Advanced Encryption Standard or a Hash-based Message Authentication Code. Implementations may use the same key for all identifiers or use a different key for each identifier. Using a different key for each identifier provides a higher degree of security and privacy. Identifiers can alternatively be replaced with a keyword, including transforming “George Washington” to “PATIENT” or replacing it with a surrogate value, such as transforming “George Washington” to “Abraham Polk.”

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (5) DE-IDENTIFICATION / STATISTICAL DISCLOSURE CONTROL<br>
**Manipulate numerical data, contingency tables, and statistical findings so that no individual or organization is identifiable in the results of the analysis.**

    <ins>Discussion</ins>: Many types of statistical analyses can result in the disclosure of information about individuals even if only summary information is provided. For example, if a school that publishes a monthly table with the number of minority students enrolled, reports that it has 10-19 such students in January, and subsequently reports that it has 20-29 such students in March, then it can be inferred that the student who enrolled in February was a minority.

    <ins>Related Controls</ins>: None.

* (6) DE-IDENTIFICATION / DIFFERENTIAL PRIVACY<br>
**Prevent disclosure of personally identifiable information by adding non-deterministic noise to the results of mathematical operations before the results are reported.**

    <ins>Discussion</ins>: The mathematical definition for differential privacy holds that the result of a dataset analysis should be approximately the same before and after the addition or removal of a single data record (which is assumed to be the data from a single individual). In its most basic form, differential privacy applies only to online query systems. However, it can also be used to produce machine-learning statistical classifiers and synthetic data. Differential privacy comes at the cost of decreased accuracy of results, forcing organizations to quantify the trade-off between privacy protection and the overall accuracy, usefulness, and utility of the de-identified dataset. Non-deterministic noise can include adding small, random values to the results of mathematical operations in dataset analysis.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (7) DE-IDENTIFICATION / VALIDATED ALGORITHMS AND SOFTWARE<br>
**Perform de-identification using validated algorithms and software that is validated to implement the algorithms.**

    <ins>Discussion</ins>: Algorithms that appear to remove personally identifiable information from a dataset may in fact leave information that is personally identifiable or data that is re-identifiable. Software that is claimed to implement a validated algorithm may contain bugs or implement a different algorithm. Software may de-identify one type of data, such as integers, but not de-identify another type of data, such as floating point numbers. For these reasons, de-identification is performed using algorithms and software that are validated.

    <ins>Related Controls</ins>: None.
   
* (8) DE-IDENTIFICATION / MOTIVATED INTRUDER<br>
**Perform a motivated intruder test on the de-identified dataset to determine if the identified data remains or if the de-identified data can be re-identified.**

    <ins>Discussion</ins>: A motivated intruder test is a test in which an individual or group takes a data release and specified resources and attempts to re-identify one or more individuals in the de-identified dataset. Such tests specify the amount of inside knowledge, computational resources, financial resources, data, and skills that intruders possess to conduct the tests. A motivated intruder test can determine if the de-identification is insufficient. It can also be a useful diagnostic tool to assess if de-identification is likely to be sufficient. However, the test alone cannot prove that de-identification is sufficient.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130, Appendix II], [SP 800-188].
