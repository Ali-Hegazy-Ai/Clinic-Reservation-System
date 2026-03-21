# Clinic Reservation System

A software engineering academic project for managing clinic appointments. This system allows patients to book, view, and cancel appointments with doctors through a structured reservation workflow.

## Scope

This project focuses on the **Book Appointment** use case, covering:

- Patient registration and login
- Viewing available appointment slots
- Booking an appointment with a selected doctor
- Receiving a confirmation

## Artifacts

| Artifact | Location | Description |
| --- | --- | --- |
| Software Requirements Specification (SRS) | `docs/clinic-srs.pdf` | Full functional and non-functional requirements |
| Use Case Diagram | `diagrams/export/use-case-diagram.svg` | System actors and use cases |
| Sequence Diagram – Book Appointment | `diagrams/export/sequence-booking.svg` | Step-by-step flow for booking an appointment |
| Traceability Matrix | `docs/traceability-matrix.md` | Maps requirements → use cases → sequence steps |

## Folder Structure

```
Clinic-Reservation-System/
├── docs/
│   ├── clinic-srs.pdf
│   └── traceability-matrix.md
├── diagrams/
│   ├── use-case-diagram.drawio
│   ├── sequence-booking.drawio
│   └── export/
│       ├── use-case-diagram.svg
│       └── sequence-booking.svg
├── notes/
│   └── assumptions.md
├── .gitignore
└── README.md
```

## Naming Conventions

- Diagrams (editable): `<name>.drawio` inside `diagrams/`
- Diagrams (exported): `<name>.svg` or `<name>.pdf` inside `diagrams/export/`
- Documents: `<name>.pdf` inside `docs/`

## Team Members

| Name | Role |
| --- | --- |
| [Team Member 1] | [Role] |
| [Team Member 2] | [Role] |
| [Team Member 3] | [Role] |

## Suggested Commit Messages

1. `docs: add initial repository structure and README`
2. `docs: add SRS document and use case diagram`
3. `docs: add sequence diagram for Book Appointment use case`