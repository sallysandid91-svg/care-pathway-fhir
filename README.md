# care-pathway-fhir
Healthcare care pathway modeled with FHIR resources and healthcare terminologies.
# Diabetes Care Pathway using HL7 FHIR

## Business Context

This project illustrates how a diabetes patient care pathway can be represented using HL7 FHIR resources and healthcare terminologies.

## Use Case

A patient diagnosed with Type 2 Diabetes follows the following care pathway:

1. Medical consultation
2. Laboratory test prescription (HbA1c)
3. Laboratory analysis
4. Follow-up consultation

## Main Actors

- Patient
- General Practitioner
- Laboratory

## Main FHIR Resources

- Patient
- Practitioner
- Encounter
- ServiceRequest
- Observation
## Healthcare Terminologies

This project uses healthcare terminologies to ensure semantic interoperability.

### SNOMED CT

- 44054006 : Type 2 diabetes mellitus

### LOINC

- 4548-4 : Hemoglobin A1c
