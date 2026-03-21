# Traceability Matrix

Maps SRS Functional Requirements → Use Cases → Sequence Diagram Steps.

## Book Appointment

| Req. ID | Functional Requirement | Use Case | Sequence Diagram Step |
| --- | --- | --- | --- |
| FR-01 | The system shall allow a registered patient to log in | UC-01: Patient Login | 1. Patient submits credentials → 2. System validates credentials → 3. System grants access |
| FR-02 | The system shall display available appointment slots | UC-02: View Available Slots | 1. Patient requests slots → 2. System queries database → 3. System returns available slots |
| FR-03 | The system shall allow a patient to select a doctor and time slot | UC-03: Book Appointment | 1. Patient selects doctor → 2. Patient selects time slot → 3. System checks availability |
| FR-04 | The system shall confirm the booked appointment | UC-03: Book Appointment | 4. System saves appointment → 5. System sends confirmation to patient |
| FR-05 | The system shall prevent double-booking of the same slot | UC-03: Book Appointment | 3a. System detects conflict → 3b. System notifies patient of unavailability |
| FR-06 | The system shall allow a patient to cancel an existing appointment | UC-04: Cancel Appointment | 1. Patient selects appointment → 2. Patient requests cancellation → 3. System removes booking → 4. System confirms cancellation |

## Notes

- All functional requirements are derived from the SRS document (`docs/clinic-srs.pdf`).
- Use case identifiers (UC-XX) correspond to the Use Case Diagram (`diagrams/export/use-case-diagram.svg`).
- Sequence diagram steps correspond to `diagrams/export/sequence-booking.svg`.
