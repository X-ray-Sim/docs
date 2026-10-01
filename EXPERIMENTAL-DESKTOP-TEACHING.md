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

- Three pages under `Guides/Teaching-with-Desktop/`: Use the simulator in your course, Get ready for your first class, and Teaching activities.
- A current-version navigation group marked experimental, plus entry links from Welcome and the Desktop quick start.
- A visible warning and `noindex: true` on each new page.
- A worked wrist radiography course example, a short preparation guide, an adaptable student announcement, and specific instructions for a wrist collimation activity.

The course sequence, lesson format, and timing are proposals to review with faculty. The wrist activity is based on the documented healthy wrist case, PA projection, Desktop collimation controls, and image export. It has not been rehearsed in a running simulator. Before publication, VitaSim must confirm exact case/view labels, starting setup, control behavior, and resulting images; capture a real wrist comparison pair; and obtain a radiography educator's review. The activity warning makes this verification gap visible. Instructor preparation is not a substitute for that product review.

Customer names, dates, account details, and completed institutional plans belong in the institution's own working documents. The public draft contains an illustrative course sequence and a student message with four local details to fill in. It does not introduce a promised curriculum-design or onboarding service.

## Approval checklist for a later review

- Review educational content and ownership with the user.
- Rehearse the selected activities in Desktop and confirm limitations.
- Confirm that the guidance and support responsibilities match the service VitaSim intends to offer.
- Review all three pages, the Welcome/quick-start links, and `docs.json` navigation.
- Record explicit user approval before preparing any merge or publication. A human performs any push.

These notices are a documented approval requirement, not a server-enforced Git branch protection rule.

## Local verification — faculty revision, 2026-10-01

- Mintlify build validation passed.
- All 22 local link targets in the five edited MDX pages exist; all three teaching navigation paths resolve to files.
- The three revised teaching pages rendered in the local browser with their new titles and experimental labels. Navigation from the course guide to preparation, preparation to the wrist activity, and the activity back to the course review section was checked. No browser console errors were reported. The course page retained its `noindex` metadata.
- `git diff --check` passed.
- On the initial draft, the native Mintlify broken-link command reported 122 links across 29 files, including existing routes and new routes that loaded successfully in the browser. That checker has not been resolved or rerun for this editorial revision; scoped file-target and browser checks were used instead.
- The wrist activity has not been rehearsed in the simulator, and user approval remains pending. Permission to revise the draft does not grant merge/publication approval.

Local review entry: `http://localhost:3000/Guides/Teaching-with-Desktop/plan-your-course-rollout`.
