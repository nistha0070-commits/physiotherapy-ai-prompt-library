# Prompt 3 – Invoice and Payment Request

## Version 1 – v1.0

Write an invoice payment email to a physiotherapy patient.

## Version 2 – v1.1

Write a professional payment email including the patient's name, invoice number, invoice date, amount due and payment instructions.

## Final Prompt Text – v1.2

You are an administrative assistant supporting a physiotherapy clinic.

Create a concise, professional and polite invoice or payment request email using only the information provided.

Include:
- Recipient name
- Invoice number, if provided
- Invoice date
- Service date, if provided
- Amount due
- Due date, if provided
- Approved payment instructions
- Request for payment confirmation or receipt, if required

Use a clear and respectful tone.

Do not invent:
- Invoice numbers
- Payment amounts
- Due dates
- Bank details
- Payment methods
- Late fees or penalties

Do not include unnecessary clinical information.

If essential billing information is missing, state:
"Staff confirmation is required before this email is sent."

Produce a suitable subject line and final email body only.

## Intended Workflow or Task

This prompt supports billing administration after an invoice has been generated or when payment follow-up is required.

## Problem Being Solved

Manually preparing routine payment emails consumes administrative time and may create inconsistent wording. Billing errors can also affect cash flow and patient satisfaction.

## Automation Potential

High for message drafting but low for financial decision-making. AI can create a standardised draft from approved invoice details. Staff must verify the invoice against the clinic billing system before sending.

## Risks and Limitations

Incorrect amounts, bank details or payment deadlines could create financial and reputational risk.

Mitigation:
- AI must never generate financial details independently.
- Use billing system data as the source of truth.
- Require staff verification before sending.

## Example Input

Recipient name: Daniel Smith
Invoice number: INV-2045
Invoice date: 15 August 2026
Service date: 14 August 2026
Amount due: $95.00
Due date: 25 August 2026
Payment instructions: Use the secure payment link included with the invoice.
Additional request: Please provide payment confirmation once completed.

## Final Test Output

Subject: Invoice INV-2045 – Payment Request

Dear Daniel Smith,

Please find your invoice **INV-2045**, dated **15 August 2026**, for the service provided on **14 August 2026**.

The amount due is **$95.00**, with payment requested by **25 August 2026**.

Please use the secure payment link included with the invoice to complete payment.

Once payment has been completed, please send confirmation for our records.

Kind regards,
Physiotherapy Clinic Administration

## Test Evaluation

The final prompt produced a clear and professional invoice payment email.

All supplied billing information was included accurately.

The AI did not invent bank details, payment methods, penalties or additional fees.

The wording remained polite and suitable for patient communication.

Human verification is still required to ensure the invoice information matches the clinic billing system before sending.

## Audit Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
|---|---|---|---|
| v1.0 | Generic invoice email request | Output could invent billing information | Financial prompts require strict controls |
| v1.1 | Added required invoice fields | Output was clearer but still lacked safeguards | Financial data must be explicitly protected |
| v1.2 | Prohibited invented amounts, fees and payment details | Output became safer and more usable | Source-data validation is essential |- Clinical information is excluded unless required for basic invoice identification.
- Missing billing details must be referred back to clinic staff.
- Staff must verify the invoice against the clinic billing system before sending.
- Main risks identified include incorrect financial information, privacy issues, or inappropriate payment requests.
- Human verification is required because AI should not independently make billing decisions.
