# Requirements

## Project Name
CareTrack Healthcare Portal

## End User
Clinic admin / care coordinator

## Functional Requirements

### Patient Management
The admin should be able to:
- Add a new patient
- View all patients
- Update patient details
- Delete a patient

### Patient Fields
Each patient should have:
- id
- firstName
- lastName
- age
- email
- phone
- condition
- appointmentDate
- appointmentStatus

### Appointment Status
Allowed values:
- Scheduled
- Completed
- Cancelled

### Dashboard
The system should show:
- Total patients
- Number of scheduled appointments
- Number of completed visits
- Number of cancelled visits

## Non-Functional Requirements

- Responsive UI
- Clean healthcare-themed design
- REST API backend
- PostgreSQL database
- Proper layered backend architecture
- Basic validation
- Meaningful error handling
- Git commits after major features

## Acceptance Criteria

- User can create a patient from UI
- User can see patient list
- User can update a patient
- User can delete a patient
- Data persists in PostgreSQL
- Dashboard numbers update based on patient data
