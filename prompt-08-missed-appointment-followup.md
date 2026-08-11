# Prompt 8 – Missed Appointment Follow-Up

## Version 1 – v1.0

Write a message to a patient who missed an appointment.

## Version 2 – v1.1

Write a polite missed-appointment message including the appointment date, time, rescheduling instructions and clinic policy if supplied.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a courteous and professional follow-up message for a patient who did not attend a scheduled appointment.

Use only the information supplied.

Include:
- Patient first name
- Missed appointment date
- Missed appointment time
- Neutral statement noting the missed appointment
- Instructions for contacting the clinic to reschedule
- Approved non-attendance or cancellation policy information, if supplied

Use a respectful and non-judgemental tone.

Do not:
- Assume why the patient missed the appointment
- Blame or criticise the patient
- Invent fees
- Invent penalties
- Invent clinic policies
- Include unnecessary clinical information

If policy information has not been provided, do not mention fees or penalties.

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports follow-up after the booking system records a patient as not attending an appointment.

## Problem Being Solved

Manual follow-ups use staff time, while inconsistent or judgemental wording can negatively affect patient relationships. Missed appointments also reduce clinic utilisation.

## Automation Potential

High for drafting. A no-show status could trigger a draft message. Staff verify the attendance record and any applicable policy before sending.

## Risks and Limitations

AI may wrongly apply a fee, use an inappropriate tone or assume why the patient did not attend.

Mitigation:
- Policy must be supplied explicitly.
- Neutral language.
- Human verification of appointment records and fees.

## Example Input

Patient first name: Liam
Missed appointment date: 17 August 2026
Missed appointment time: 4:00 pm
Rescheduling instructions: Please contact reception to arrange another appointment.
Clinic policy: A cancellation fee may apply where the approved clinic cancellation policy applies.

## Final Test Output

Hi Liam,

We noticed that you were unable to attend your appointment scheduled for **17 August 2026 at 4:00 pm**.

If you would like to arrange another appointment, please contact reception.

Please note that a cancellation fee may apply where the clinic's approved cancellation policy applies.

Thank you.

## Test Evaluation

The final prompt produced a respectful and non-judgemental missed-appointment follow-up.

The message did not assume why the patient missed the appointment.

It included the supplied clinic policy without inventing a specific fee or penalty.

The tone remained neutral and appropriate for patient communication.

Staff should confirm the attendance record and applicable cancellation policy before sending.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic missed-appointment message | Tone could sound judgemental | Tone must be explicitly controlled |
| v1.1 | Added scheduling and policy information | More useful but could invent reasons or fees | Policy constraints are required |
| v1.2 | Added neutral language and strict fee controls | Output became more appropriate | Responsible communication protects patient relationships |- Staff should check the appointment record and relevant clinic policy before sending.
- Main risks identified include incorrect fees, inappropriate tone, inaccurate policy information, and negative patient experience.
- Human oversight is required before the follow-up message is sent.
