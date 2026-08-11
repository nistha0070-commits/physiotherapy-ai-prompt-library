# Prompt 10 – Internal Administrative Handover Summary

## Version 1 – v1.0

Summarise physiotherapy clinic administration notes.

## Version 2 – v1.1

Create a structured administrative handover summary including outstanding appointments, patient follow-ups, referrals, billing tasks and priorities.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a concise internal administrative handover summary using only the authorised administrative notes provided.

Organise information under these headings where relevant:

- Outstanding Appointments
- Patient Communications Requiring Follow-Up
- Referrals or Documents Awaiting Action
- Billing and Invoice Follow-Up
- Other Administrative Tasks
- Priority Actions for the Next Staff Member

Use concise bullet points.

Keep the summary factual, professional and easy to scan.

Do not:
- Provide diagnoses
- Interpret clinical information
- Recommend treatment
- Invent tasks
- Invent priorities
- Add information not contained in the source notes

Avoid unnecessary sensitive patient information.

Clearly identify incomplete tasks or items requiring staff confirmation.

Only include dates, deadlines or priorities when they appear in the supplied notes.

Produce only the final structured handover summary.

## Intended Workflow or Task

This prompt supports shift or staff handovers within the clinic administration team.

## Problem Being Solved

Unstructured handover notes can result in missed tasks, duplicated work, delays and poor continuity between administration staff. Preparing summaries manually also takes time.

## Automation Potential

Moderate to high. AI can reorganise approved administrative notes into a consistent structure. A staff member must compare the summary with the original notes before relying on it.

## Risks and Limitations

AI could omit an important task, change priority or expose excessive patient information.

Mitigation:
- Use authorised administrative notes only.
- Restrict AI from clinical interpretation.
- Staff compare the generated summary with source notes.
- Avoid unnecessary identifying information.

## Example Input

Administrative notes:

- Sarah requires appointment confirmation for 25 August at 2:00 pm.
- Michael's GP referral has not yet been received.
- Invoice INV-3021 for Daniel requires payment follow-up.
- Reception needs to confirm Rachel's updated Medicare details.
- Priority: Contact Michael's GP clinic before 12:00 pm tomorrow.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Broad summary request | Output lacked structure and priorities | Administrative summaries require categories |
| v1.1 | Added workflow categories | Output became easier to scan but could still infer information | Add factuality and privacy controls |
| v1.2 | Added no-invention rule, privacy restrictions and staff confirmation | Output became more reliable for handover | Structured constraints improve operational consistency |- Added safeguards against generating information that is not contained in the original notes.
- Unnecessary sensitive patient information should be removed from the handover.
- Staff should verify all outstanding tasks, dates, and priorities against clinic records.
- Main risks identified include inaccurate summaries, omitted tasks, privacy exposure, or invented priorities.
- Human review is required before the handover is relied upon for operational decisions.
