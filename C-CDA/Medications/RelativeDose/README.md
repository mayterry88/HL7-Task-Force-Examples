This example illustrates an example of a medication order with the following characteristics:
* an IV drug with a relative dose quantity that is based on weight, 
* a drug vehicle used for preparation, 
* and indications for the medication.

This example was created to address the following Use Case:
An oncologist is ordering a drug as part of a chemotherapy regimen. Chemotherapy regimens consist of orders could be administered weeks or months in advance.  Moreover their preparation is based on the patient's weight at the time of administration.  Because of these constraints, the C-CDA medications section needs to be represented in a way that reflects this.

Additional Notes and Assumptions:
* the /entry/substanceAdministration/effectiveTime/@value is meant to be set at a future date relative to the date of the encounter.  The date of the encounter would have been represented in a separate section outside of this example.
