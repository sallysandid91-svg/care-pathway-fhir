# Business Requirements to FHIR Mapping

## Use Case

Diabetes patient follow-up

| Business Requirement | FHIR Resource |
|---------------------|--------------|
| Patient identification | Patient |
| Medical consultation | Encounter |
| Diabetes diagnosis | Condition |
| Laboratory test prescription | ServiceRequest |
| HbA1c laboratory result | Observation |

## Healthcare Terminologies

| Clinical Concept | Terminology | Code |
|-----------------|------------|------|
| Type 2 Diabetes Mellitus | SNOMED CT | 44054006 |
| Hemoglobin A1c | LOINC | 4548-4 |

## Data Flow

Patient
→ Consultation
→ Diagnosis
→ Laboratory Prescription
→ Laboratory Result
→ Follow-up Consultation
