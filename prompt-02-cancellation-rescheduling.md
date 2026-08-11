# Prompt 2 – Appointment Cancellation or Rescheduling

## Version 1 – v1.0

Write a message about a changed physiotherapy appointment.

## Version 2 – v1.1

Write a polite appointment cancellation or rescheduling message including the patient's first name, original appointment details and new appointment details if available.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a professional and courteous appointment cancellation or rescheduling message using only the information provided.

Include:
- Patient first name
- Original appointment date
- Original appointment time
- Whether the appointment is cancelled or rescheduled
- New appointment date and time, if confirmed
- Practitioner name, if provided
- Contact or rebooking instructions

Use a polite, respectful and concise tone.

Do not invent a reason for the appointment change.
Do not invent a replacement appointment date or time.
Do not include unnecessary medical or clinical information.

If a replacement appointment has not been confirmed, clearly state that staff confirmation is required.

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports clinic scheduling when an existing appointment must be cancelled or moved. Administration staff enter confirmed booking information and use the generated draft to communicate the change to the patient.

## Problem Being Solved

Manual rescheduling messages take staff time and may communicate incomplete or inconsistent information. Poor communication can lead to confusion, increased phone calls and missed appointments.

## Automation Potential

High for drafting standard communications. AI can create the message once appointment information is supplied. Human staff must confirm the booking change and check the final message before sending.

## Risks and Limitations

AI could provide an unconfirmed replacement appointment or invent a reason for cancellation. Incorrect information could inconvenience the patient and create scheduling problems.

Mitigation:
- Use confirmed booking data only.
- Explicitly prohibit invented appointment details.
- Require staff verification before sending.

## Example Input

Patient first name: Michael
Original appointment date: 20 August 2026
Original appointment time: 10:00 am
Action: Rescheduled
New appointment date: 22 August 2026
New appointment time: 11:30 am
Practitioner: Emma Jones
Instructions: Contact reception if this time is unsuitable.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Broad appointment-change instruction | Output lacked important booking details | The task needs clearer variables |
| v1.1 | Added original and replacement appointment details | Output became more useful but could still invent explanations | Add strict factual constraints |
| v1.2 | Added no-assumption rules and staff confirmation | Output became safer and more reliable | Controlled inputs reduce scheduling risk |
