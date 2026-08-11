# Prompt 4 – GP Referral or Document Request

## Version 1 – v1.0

Write an email asking a GP clinic for patient documents.

## Version 2 – v1.1

Write a professional email requesting specified documents from a GP clinic. Include patient name, date of birth, requested documents and reason.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Draft a concise and professional email to a GP clinic or medical practice requesting specified patient documents.

Use only the information provided.

Include:
- GP clinic or recipient name
- Patient full name
- Patient date of birth, only if required for identification
- Documents being requested
- Administrative reason for the request, if provided
- A polite request for the documents to be forwarded
- Clinic contact information, if provided

Include only the minimum patient information necessary.

Do not add:
- Diagnosis
- Medical history
- Treatment details
- Clinical interpretation

Do not request documents that have not been specified.
Do not invent patient or clinic information.

If essential information is missing, state that staff confirmation is required.

Produce a subject line and final professional email only.

## Intended Workflow or Task

This prompt supports communication between a physiotherapy clinic and an external GP practice when referral or administrative documents are required.

## Problem Being Solved

Staff may repeatedly draft similar document requests. Manual preparation takes time and creates privacy and quality risks if excessive or incorrect information is included.

## Automation Potential

Moderate to high. AI can draft the correspondence using approved patient and document details. Staff must verify patient identity, recipient details and authorisation before sending.

## Risks and Limitations

Main risks include privacy breaches, incorrect recipients, excessive disclosure and requesting the wrong documents.

Mitigation:
- Minimum necessary patient information.
- Confirm recipient before sending.
- Human review is mandatory.
- AI does not determine which clinical documents are required.

## Example Input

Recipient: Greenfield Medical Centre
Patient name: Olivia Brown
Date of birth: 12 March 1985
Documents requested: GP Management Plan and referral letter
Reason: Required for physiotherapy administration
Clinic contact: admin@centralphysio.com.au

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic request for documents | Output lacked privacy controls and document specificity | Healthcare communication needs strict context |
| v1.1 | Added patient identification and required documents | Output became more useful but contained unnecessary detail risk | Apply minimum-data principles |
| v1.2 | Added privacy constraints and prohibited clinical assumptions | Output became more suitable for healthcare administration | Privacy must be designed into the prompt |- Missing patient or document information must be confirmed by staff.
- Staff should verify the recipient before sending patient information.
- Main risks identified include privacy breaches, incorrect recipient details, excessive disclosure, or requesting the wrong documents.
- Human review is required before external healthcare communication is sent.
