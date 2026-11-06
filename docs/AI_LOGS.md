# AI Change Log

## User instruction

> Remove the contact form and all contact-submission requirements and architecture. Customers should contact the store directly using only the phone number and social links already in scope. Do not add anything new to customer contact.

## Changes made

- Updated `REQUIREMENTS.md` to remove contact-submission requirements, use cases, validation/data rules, APIs, reporting, and related acceptance criteria. Preserved surviving identifiers rather than renumbering them.
- Restricted the customer-facing contact requirement to the phone number and Facebook/Instagram links already present in the source materials. The official phone number and social URLs remain `[CONFIRMATION REQUIRED]`; no values or additional contact channels were invented.
- Updated `ARCHITECTURE.md` to remove the contact-submission module, request flow, data entity, endpoints, administration workflow, security/privacy design, repository folders, and implementation phase.
- Updated `README.md` to describe direct contact through the existing phone and social-link channels, with no contact form or submission flow.

