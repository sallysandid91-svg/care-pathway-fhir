# Diabetes Care Pathway

## Objective

Represent a diabetes care pathway using HL7 FHIR resources.

## Actors

- Patient
- General Practitioner
- Laboratory

## Workflow

1. Patient attends a medical consultation.
2. Physician orders an HbA1c laboratory test.
3. Laboratory performs the test.
4. Result is returned to the physician.
5. Follow-up consultation is scheduled.

## FHIR Resources Used

- Patient
- Encounter
- ServiceRequest
- Observation

## Terminologies

- LOINC 4548-4 : Hemoglobin A1c
