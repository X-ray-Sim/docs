---
title: "Teaching release review"
noindex: true
---

# Teaching release review

Approval: **Approved for removing experimental labels, merging, and pushing on 2026-10-01.**

The user explicitly instructed: "Thats great. lets remove the \"experimental\" flags, merge and push it."

This instruction authorizes publication of this Teaching change and a push to `origin/main`, overriding the repository's general manual-push rule for this release only. The general rule in `AGENTS.md` remains unchanged for future work.

## Approved scope

- A Teaching top tab and product overview, with three Desktop guides for course planning, preparation/session 0, and teaching activities.
- A clear statement that VR teaching resources are not available yet, with links to existing VR usage instructions and no promise of future material.
- Entry links from Welcome and the Desktop quick start. Existing Desktop guide URLs and historical-version navigation are preserved.
- Removal of public experimental badges, draft warnings, and temporary `noindex` settings from the four teaching pages.

## Content basis and limits

The five teaching applications come from the user's practice and the catalog/Desktop control documentation. Peer feedback/revision and early/later image comparisons are proposed extensions. Technical details remain in the canonical setup, account, and simulator-reference pages.

The agent has not rehearsed the activities in a running simulator. Publication approval does not establish simulator validation. The guides retain instructor preparation and controlled comparisons; they do not claim validated learning outcomes or guaranteed ideal images. The inverse-square calculation remains separate from image observation, and screen brightness is not treated as a measurement of beam intensity.

Image submission uses manual file export and upload to the institution's assignment system. No LMS integration, grading, curriculum-design service, or onboarding service is promised.

Editorial references: [Cornell on flipped classrooms](https://teaching.cornell.edu/teaching-resources/active-collaborative-learning/flipping-classroom), [AAPM Report 116](https://www.aapm.org/pubs/reports/detail.asp?docid=111), and [IAEA Diagnostic Radiology Physics, section 6.2.3.3](https://pub.iaea.org/mtcd/publications/pdf/pub1564webnew-74666420.pdf). These inform the wording, not validation of the simulator.

## Earlier verification

Draft revisions passed Mintlify build validation, scoped local-link checks, and browser checks of all four pages and key navigation paths. The prior native Mintlify broken-link run reported 122 links across 29 files, including existing routes and routes that loaded in the browser; that broad-checker limitation was not resolved. Subsequent checks used scoped file and browser verification. The full draft review history remains in Git.

## Release verification — 2026-10-01

- Mintlify build validation and `git diff --check` passed.
- All four Teaching navigation pages and 29 distinct local link destinations across the six affected public MDX pages resolve to files. Historical-version navigation is unchanged.
- Browser checks confirmed all four Teaching pages render without experimental wording or `noindex` metadata. The overview retains the statement that VR teaching resources are not yet available. No browser console errors were reported.
- The production release consists of these approved documentation changes; unrelated untracked files in the primary checkout are outside its scope.
