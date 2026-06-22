# Data Quality Rules

## Patient

- Identifier must not be null.
- Birth date must be valid.

## Encounter

- Start date must be before end date.

## Observation

- HbA1c value must be between 0 and 20%.

## Condition

- Diagnosis must use SNOMED CT terminology.
