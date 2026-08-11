# Prompt 7 – Appointment Preparation and Arrival Instructions

## Version 1 – v1.0

Write appointment preparation instructions for a physiotherapy patient.

## Version 2 – v1.1

Write clear arrival instructions including appointment details, location, arrival time and items the patient should bring.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a clear and friendly appointment preparation and arrival message using only instructions supplied by authorised clinic staff.

Include:
- Patient first name
- Appointment date
- Appointment time
- Clinic location
- Recommended arrival time
- Documents or items the patient has been asked to bring
- Other approved administrative instructions

Keep the message concise, professional and easy to follow.

Do not independently create:
- Medical preparation advice
- Medication instructions
- Exercise recommendations
- Fasting requirements
- Treatment changes
- Clinical advice

Only include clinical preparation information if the exact instruction has been supplied by authorised clinic staff.

Do not invent missing information.

If an instruction is unclear, state that staff confirmation is required.

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports pre-appointment administrative communication after an appointment has been booked.

## Problem Being Solved

Patients may arrive late or without necessary documents because instructions are inconsistent or unclear. Staff also spend time repeatedly communicating routine arrival information.

## Automation Potential

High for standard administrative instructions. AI drafts the message while clinic staff remain responsible for any clinical preparation advice.

## Risks and Limitations

The largest risk is AI generating inappropriate clinical advice.

Mitigation:
- Explicitly prohibit independent clinical recommendations.
- Only use staff-approved instructions.
- Human review before sending.

## Example Input

Patient first name: Amanda
Appointment date: 24 August 2026
Appointment time: 9:30 am
Clinic location: Central Physiotherapy Clinic
Arrival time: Please arrive 10 minutes early
Items to bring: Referral letter and Medicare card
Other instructions: Check in at reception.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic preparation instruction | AI could generate clinical advice | Separate administrative and clinical preparation |
| v1.1 | Added arrival and document information | More practical but clinical boundaries were unclear | Add explicit exclusions |
| v1.2 | Added authorised-information rule and clinical safeguards | Output became safer for patient communication | Clear boundaries reduce healthcare risk |- Unclear preparation instructions must be referred back to staff.
- Main risks identified include AI-generated clinical advice, incorrect preparation information, or missing appointment instructions.
- Human verification is required before the message is provided to the patient.
