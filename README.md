## Key Enhancements

This update extends the interoperability documentation between **EMR systems and NPCA’s Digital Payment Certification System** with the following key components:

### 1. Clinical Data Forms

Defines standardized clinical data forms, field structures, data types, required fields, reference values, and validation rules to ensure consistent clinical data exchange between EMR systems and NPCA.

### 2. Reference Data

Defines standardized reference data and coding standards, including services, diagnoses, medications, facilities, providers, procedures, and other master data required for interoperability. EMR systems should use the approved NPCA reference codes to maintain data consistency.

### 3. Submission & Processing Workflow

Documents the end-to-end data submission and processing workflow, including request validation, submission acceptance, asynchronous processing, processing statuses, success/partial success/failure handling, monitoring, and resubmission rules.

These enhancements provide a common implementation standard for EMR vendors and improve **data consistency, interoperability, validation, processing transparency, and integration reliability**.

### 4. Changes in Prescription Quantity Calculation

The system no longer automatically calculates the medication quantity when the EMR does not provide it. The EMR is responsible for providing the correct medication quantity and unit in the submission payload.

Important: EMR systems must ensure that the quantity value and unit is correctly provided before submitting the prescription data.
