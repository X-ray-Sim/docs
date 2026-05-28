# Rewrite Technical And Security FAQ

Status: needs-triage
Priority: P1
Area: IT and Security
Page: Tech/technical-and-security-FAQ.mdx

## Problem

The FAQ contains useful security information but is not in navigation and uses rough wording in places. It also uses the phrase "dump users", which should be replaced with clearer customer-facing terminology.

## Proposed Change

Rewrite the FAQ for IT and security reviewers. Clarify data handling, authentication, logging, hosting, deployment, support contacts, and integration boundaries.

## Acceptance Criteria

- Customer-facing terminology is professional and consistent.
- Security claims are precise and do not overstate compliance.
- The page includes practical review details such as endpoints, data categories, and support contact.
- Decide whether to add the page to `docs.json` navigation.

## Notes

Needs product/security confirmation before making strong claims about retention, encryption details, infrastructure, or compliance scope.

## Comments

- 2026-05-28: Partial terminology cleanup completed as part of the accounts/license clarification work. Replaced "dump users" wording with shared station account language and linked to `Guides/Introduction/accounts-and-login.mdx`. Full security FAQ rewrite and navigation decision remain open.
