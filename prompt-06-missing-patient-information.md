# Prompt 6 – Request for Missing Patient Information

## Version 1 – v1.0

Write a message asking a patient for missing information.

## Version 2 – v1.1

Write a polite message requesting missing administrative information. Include what is required, the reason, deadline and how it can be provided.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a polite and professional message requesting missing administrative information or documentation from a patient.

Use only the information provided.

Include:
- Patient first name
- Information or document required
- Reason it is required, if supplied
- Instructions for providing it
- Deadline, if supplied
- Clinic contact details, if provided

Keep the message simple, respectful and easy to understand.

Only request information specifically listed.

Do not request unnecessary medical or sensitive information.
Do not invent reasons or deadlines.
Do not assume why information is missing.

If the request is incomplete or unclear, state that staff confirmation is required.

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports patient-registration, billing and administrative record-completion workflows when information is missing.

## Problem Being Solved

Staff may spend time repeatedly drafting requests for missing information. Poorly written requests can also lead to delays, additional calls and collection of unnecessary data.

## Automation Potential

High for drafting routine requests. AI can create a standard message based on the missing field. Human staff determine what information is genuinely required and verify the message.

## Risks and Limitations

Risks include excessive collection of personal information, unclear requests and privacy concerns.

Mitigation:
- Minimum-data principle.
- Staff identify required fields.
- AI cannot decide independently what information to collect.
- Human review before sending.

## Example Input

Patient first name: Rachel
Information required: Medicare card details
Reason: Required to complete billing records
Instructions: Please contact reception using the clinic's approved communication method.
Deadline: 21 August 2026

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic information request | Output could ask for unnecessary information | The request must specify exactly what is required |
| v1.1 | Added reason, deadline and submission method | Output became clearer but lacked privacy safeguards | Data minimisation is necessary |
| v1.2 | Added privacy constraints and no-assumption rule | Output became safer and more focused | AI should not decide what patient data to collect |- The final message should be checked to ensure it follows clinic privacy procedures.
- Main risks identified include excessive data collection, unclear requests, privacy issues, or incorrect deadlines.
- Human review is required before requesting personal information from a patient.
