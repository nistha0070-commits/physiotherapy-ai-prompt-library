# Prompt 9 – Patient Feedback Request

## Version 1 – v1.0

Write a message asking a physiotherapy patient for feedback.

## Version 2 – v1.1

Write a friendly feedback request including a thank-you, feedback method and statement that feedback is optional.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a short, friendly and professional message inviting a patient to provide feedback about their clinic experience.

Use only the information supplied.

Include:
- Patient first name, if provided
- Brief thank-you for attending the clinic
- Neutral request for feedback
- Approved feedback method or link
- Statement that providing feedback is optional

Keep the message warm, concise and respectful.

Do not:
- Pressure the patient to leave positive feedback
- Suggest that treatment depends on feedback
- Invent survey links
- Invent incentives
- Request unnecessary medical information

Only include incentives if they have been explicitly approved and supplied.

Produce only the final patient-facing message.

## Intended Workflow or Task

This prompt supports post-service feedback collection after an appointment or episode of care.

## Problem Being Solved

Staff may inconsistently request patient feedback or spend time drafting repetitive messages. Standardisation may improve response processes while protecting the quality and neutrality of feedback.

## Automation Potential

High. The clinic could automatically generate a feedback invitation after an eligible appointment. Staff should approve the template and feedback link before implementation.

## Risks and Limitations

Poorly designed AI messages could pressure patients or bias reviews.

Mitigation:
- Make participation voluntary.
- Use neutral language.
- Verify survey links.
- Avoid requesting sensitive clinical details.

## Example Input

Patient first name: Sophie
Feedback method: Online survey
Feedback link: [Approved clinic feedback link]
Additional information: Feedback is optional and helps improve clinic services.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic feedback request | Output could sound promotional | Feedback requests should remain neutral |
| v1.1 | Added thank-you and optional participation | More patient-friendly but safeguards were limited | Prevent positive-review pressure |
| v1.2 | Added neutrality, privacy and link controls | Output became more responsible | Ethical feedback collection requires unbiased wording |- Main risks identified include biased review requests, incorrect links, inappropriate pressure, and privacy concerns.
- Human review ensures that the message reflects the clinic’s approved feedback process.
