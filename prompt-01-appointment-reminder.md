# Prompt 1 – Appointment Confirmation and Reminder

## Version 1 – v1.0

Write an appointment reminder for a physiotherapy patient.

## Version 2 – v1.1

Write a clear and professional appointment reminder for a physiotherapy patient. Include the patient's first name, appointment date, time, practitioner name, clinic location and arrival instructions.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a short, professional and patient-friendly appointment confirmation and reminder using only the information supplied.

Include:
- Patient first name
- Appointment date
- Appointment time
- Practitioner name
- Clinic location
- Arrival or preparation instructions, if provided
- Clinic contact instructions, if provided

Keep the message concise, respectful and easy to understand.

Do not include unnecessary medical or clinical information.
Do not assume the patient's diagnosis, treatment or reason for attendance.
Do not invent missing details.

If essential appointment information is missing, clearly state:
"Staff confirmation is required before this message is sent."

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports the appointment communication stage after a booking has been created or confirmed. Appointment details can be taken from the clinic booking system and entered into the prompt. Administration staff review the generated reminder before sending it by SMS or email.

## Problem Being Solved

Clinic staff may prepare many appointment reminders manually. Repetitive drafting consumes administrative time and can result in inconsistent wording or omitted details. The prompt improves communication quality and reduces repetitive work.

## Automation Potential

High for drafting. Appointment information could be transferred from the booking system into a standard prompt template. AI can produce the first draft, while a staff member checks the patient's name, practitioner, date, time and location before sending. The process could scale across a large number of appointments.

## Risks and Limitations

Incorrect dates or times could create missed appointments and poor patient experience. AI could also invent missing details or expose unnecessary personal information.

Mitigation:
- Use only approved booking information.
- Minimise patient information entered.
- Prevent the AI from inventing missing details.
- Require staff review before sending.

## Example Input

Patient first name: Sarah
Appointment date: 18 August 2026
Appointment time: 2:30 pm
Practitioner name: Sharon Patel
Clinic location: Main Street Physiotherapy Clinic
Arrival instructions: Please arrive 10 minutes early
Contact instructions: Call reception if you need to change your appointment.

## Final Test Output

Hi Sarah, your physiotherapy appointment is confirmed for **18 August 2026 at 2:30 pm** with **Sharon Patel** at **Main Street Physiotherapy Clinic**.

Please arrive **10 minutes early**.

If you need to change your appointment, please call reception.

## Test Evaluation

The final prompt produced a clear, concise and professional appointment reminder.

All required appointment details were included correctly.

No unnecessary medical or clinical information was added.

The output followed the requested patient-friendly tone and did not invent any missing information.

The message is suitable for administrative use after staff verification.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Used a broad reminder instruction | Output was generic and could miss appointment details | Specific context and required fields are needed |
| v1.1 | Added appointment details and professional tone | Output became more complete but lacked privacy and missing-data controls | Explicit safeguards are needed |
| v1.2 | Added role, constraints, privacy controls and staff confirmation | Output became more consistent and appropriate for clinic use | Clear constraints improve reliability |- Added staff confirmation where essential information is incomplete.
- Final output must be reviewed by clinic staff before being sent to the patient.
- Main risks identified include incorrect date or time, missing details, privacy exposure, or invented information.
- Human oversight remains necessary before communication is released.
