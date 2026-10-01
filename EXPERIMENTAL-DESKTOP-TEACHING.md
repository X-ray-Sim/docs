---
title: "Experimental Desktop teaching draft: approval required"
noindex: true
---

# EXPERIMENTAL — DO NOT MERGE WITHOUT EXPLICIT USER APPROVAL

Approval status: **NOT APPROVED FOR MERGE OR PUBLICATION**

Branch: `experimental/desktop-course-rollout-do-not-merge`

Base: locally available `origin/main` at `ae5b7d0`.

This experiment drafts a faculty-facing path for planning a Desktop X-ray Simulator course or cohort rollout. It is authorized for writing, local preview, and review only. Approval must be explicit and specific to this experiment before merging, cherry-picking into a release/default branch, publishing, or removing the experimental labels. Validation passing does not grant approval. Agents must not push this repository.

## Review scope

- Three new pages under `Guides/Teaching-with-Desktop/`: rollout planning, preparation, and activities/templates.
- A current-version navigation group marked experimental, plus entry links from Welcome and the Desktop quick start.
- A visible warning and `noindex: true` on each new page.
- A copyable cohort plan, course activity map, student announcement, and assignment brief.

The dates, lesson formats, and review criteria are proposals to adapt with faculty. Activities have been checked against the documentation, not rehearsed in a running simulator. Faculty must confirm case availability, controls, image behavior, timing, and teaching criteria in their Desktop installation before using the material with a cohort.

Customer names, dates, account details, and completed institutional plans belong in the institution's own working documents. The public draft contains only generic examples and blank templates. It does not introduce a promised curriculum-design or onboarding service.

## Approval checklist for a later review

- Review educational content and ownership with the user.
- Rehearse the selected activities in Desktop and confirm limitations.
- Confirm that the guidance and support responsibilities match the service VitaSim intends to offer.
- Review all three pages, the Welcome/quick-start links, and `docs.json` navigation.
- Record explicit user approval before preparing any merge or publication. A human performs any push.

These notices are a documented approval requirement, not a server-enforced Git branch protection rule.

## Local verification — 2026-10-01

- Mintlify build validation passed.
- All 23 local link targets in the five edited/new MDX pages exist; all three new navigation paths resolve to files.
- The three teaching pages and Welcome rendered in the local browser. The Welcome entry, page navigation, and both cross-page section anchors were checked. No browser console errors were reported during these checks.
- `git diff --check` passed.
- The native Mintlify broken-link command reported 122 links across 29 files, including existing routes and new routes that loaded successfully in the browser. That checker is not clean; the scoped file-target and browser checks above are the verification for this draft.
- The activities have not been rehearsed in the simulator, and user approval remains pending.

Local review entry: `http://localhost:3000/Guides/Teaching-with-Desktop/plan-your-course-rollout`.
