# Exercise 2 - Laboratory Result (General Result) Records

## [E5P2Q1] What is the best place to include the description for requesting a test or profile (Panel description)?

(A) DiagnosticReport.category.coding.display

(B) DiagnosticReport.code.coding.display

(C) Observation.category.coding.display

(D) Observation.code.coding.display


Answer: &lt;PUT YOUR ANSWER HERE&gt;

## [E5P2Q2] Which of the following is the best way to upload multiple Image files (PDF) using FHIR message(s)?

(A) Create multiple items in `DiagnosticReport.presentedForm`.

(B) Create multiple DiagnosticReport along with the items in `Composition.section.entry`.

(C) Uploading multiple Image files (PDF) is not supported.

(D) Upload two FHIR message with the same record key but with different Image file (PDF).

Answer: &lt;PUT YOUR ANSWER HERE&gt;

## [E5P2Q3] If there is an amended record that needs to be updated in eHR with identifier A (record key: A), which of the following is NOT a method for doing so?

(A) Upload record with transaction type "U", record key B, and a newer message generation time

(B) Upload record with transaction type "U", record key A, and a newer message generation time

(C) Upload record with transaction type "D" and record key A, then upload another record (record key A) to eHR again in the next day

(D) Upload record with transaction type "D" and record key A, then change the record identifier to B (record key: B) and upload it to eHR 

Answer: &lt;PUT YOUR ANSWER HERE&gt;
