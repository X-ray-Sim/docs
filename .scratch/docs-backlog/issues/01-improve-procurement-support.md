# Improve Procurement Support Hub

Status: ready-for-agent
Priority: P0
Area: Procurement
Page: Procurement/Introduction.mdx

## Problem

The procurement hub has three cards with `href="href"` placeholders, and the intended child pages are empty. This creates a broken experience for procurement, IT, and vendor approval users.

## Proposed Change

Turn `Procurement/Introduction.mdx` into a Faculty Approval Packet hub with clear cards for:

- IT and Security Review
- Purchasing and Equipment
- Vendor and Legal Review
- Sales/procurement help through `mailto:sales@vitasim.dk`

Add a top-level `Procurement` tab in `docs.json` containing only the hub and the three recipient pages. Recipient pages should be self-contained review overviews that link to canonical supporting docs rather than duplicating detailed setup, hardware, MDM, or security FAQ content.

## Acceptance Criteria

- All card links point to real pages or real external destinations.
- The page explains who it is for and what each path helps with.
- Empty child pages are either filled or kept out of the user journey.
- Internal links pass a local reference check.

## Notes

Related pages:

- `Procurement/Equipment and purchasing.mdx`
- `Procurement/Security and IT approval.mdx`
- `Procurement/Vendor approval.mdx`

Approved design decisions:

- Hub reader is faculty/program directors.
- Hub format is a forwarding checklist, not a process guide or email template library.
- Recipient pages cover both Desktop and VR together, with product-specific callouts only where needed.
- Tone is low-sales and factual.
- License pricing is per student and quoted through `sales@vitasim.dk`.
- Hardware is a one-time purchase; institutions can buy hardware themselves from recommended lists or request VitaSim procurement with a 20% hardware procurement markup.
- Vendor/legal page publishes only stable public facts and routes non-public documents to sales.

## Comments
