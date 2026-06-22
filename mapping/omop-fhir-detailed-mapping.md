# OMOP to FHIR Detailed Mapping

## Patient Domain

| OMOP | FHIR |
|--------|--------|
| PERSON.person_id | Patient.id |
| PERSON.gender_concept_id | Patient.gender |
| PERSON.birth_datetime | Patient.birthDate |

---

## Visit Domain

| OMOP | FHIR |
|--------|--------|
| VISIT_OCCURRENCE.visit_occurrence_id | Encounter.id |
| VISIT_OCCURRENCE.person_id | Encounter.subject |
| VISIT_OCCURRENCE.visit_start_date | Encounter.period.start |
| VISIT_OCCURRENCE.visit_end_date | Encounter.period.end |

---

## Condition Domain

| OMOP | FHIR |
|--------|--------|
| CONDITION_OCCURRENCE.condition_occurrence_id | Condition.id |
| CONDITION_OCCURRENCE.person_id | Condition.subject |
| CONDITION_OCCURRENCE.condition_concept_id | Condition.code |

---

## Measurement Domain

| OMOP | FHIR |
|--------|--------|
| MEASUREMENT.measurement_id | Observation.id |
| MEASUREMENT.person_id | Observation.subject |
| MEASUREMENT.measurement_concept_id | Observation.code |
| MEASUREMENT.value_as_number | Observation.valueQuantity.value |
