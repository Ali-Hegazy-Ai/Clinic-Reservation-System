# Design Assumptions & Decisions

This file documents assumptions made during analysis and design of the Clinic Reservation System.

## General Assumptions

1. **Single Clinic**: The system is designed for a single clinic with multiple doctors. Multi-clinic support is out of scope.
2. **Registered Patients Only**: Only registered patients can book appointments. Walk-in booking is not supported.
3. **Doctor Availability**: Doctor schedules are pre-configured by an administrator and not self-managed by doctors.
4. **Appointment Duration**: All appointments have a fixed duration of 30 minutes.
5. **No Payment Processing**: The system does not handle payments or insurance claims.
6. **Notifications**: Confirmation is shown on screen. Email/SMS notifications are out of scope for this iteration.

## Design Decisions

1. **Focus on Book Appointment Use Case**: The sequence diagram and traceability matrix prioritize this core workflow as it demonstrates the most interactions between system components.
2. **draw.io for Diagrams**: All editable diagram sources use the `.drawio` format for portability (works offline and with the draw.io web app).
3. **SVG Export Format**: Diagrams are exported as SVG for lossless quality and easy rendering in browsers and documents.
