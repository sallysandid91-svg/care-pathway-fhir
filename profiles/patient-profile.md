# Patient Profile

## Purpose

This profile defines the minimum information required to identify a patient in a diabetes care pathway.

## Mandatory Elements

| Element | Cardinality |
|----------|------------|
| identifier | 1..* |
| name | 1..* |
| gender | 1..1 |
| birthDate | 1..1 |

## Business Rules

### BR-001

A patient must have at least one identifier.

### BR-002

A patient's birth date is mandatory.

### BR-003

Gender shall use the FHIR AdministrativeGender value set.

## Terminologies

AdministrativeGender

- male
- female
- other
- unknown
