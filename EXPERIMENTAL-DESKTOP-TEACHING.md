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
- A worked wrist radiography course sequence, a short preparation guide, and an adaptable student announcement.
- Five uses supplied by the user: live error correction (with a flipped-classroom variation), image-making homework, paired practice, exposure/distance comparisons, and creating teaching images for slides.
- Two proposed extensions: peer feedback followed by revision, and an early/later image comparison to discuss learning.

The course sequence and teaching formats are proposals to review with faculty. The draft uses the documented wrist movement controls, exposure settings, displayed SID, raw/digital image modes, and image export. The activities have not been rehearsed in a running simulator. Before publication, VitaSim must confirm the case/view labels, starting setups, control behavior, and resulting comparisons; capture real example images; and obtain a radiography educator's review. The activity warning makes this verification gap visible. Instructor preparation is not a substitute for that product review.

In particular, verify the simulator's quantitative response to distance before promising a numerical inverse-square-law experiment. This draft connects a course calculation to the visible setup and keeps it separate from image observation. It does not treat brightness as a measurement of beam intensity or claim that the simulator has been validated against the formula. Likewise, the slide-making example produces images for an instructor's stated criteria, not guaranteed ideal or diagnostic-quality images.

Customer names, dates, account details, and completed institutional plans belong in the institution's own working documents. The draft contains an illustrative course sequence and adaptable student messages. Image submission is a manual save-and-upload workflow in the institution's existing assignment system. It does not promise LMS integration, grading, or a curriculum-design/onboarding service.

Editorial references: [Cornell on flipped classrooms](https://teaching.cornell.edu/teaching-resources/active-collaborative-learning/flipping-classroom) supports the pre-class preparation variation; [AAPM Report 116](https://www.aapm.org/pubs/reports/detail.asp?docid=111) supports the distinction between displayed brightness and exposure; [IAEA Diagnostic Radiology Physics, section 6.2.3.3](https://pub.iaea.org/mtcd/publications/pdf/pub1564webnew-74666420.pdf) explains the inverse square law. These sources inform the wording; they do not validate this simulator or these proposed activities.

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

## Local verification — user-supplied teaching ideas, 2026-10-01

- Mintlify build validation passed for the revised pages.
- All 24 distinct local link targets across the five edited MDX pages resolve to files. The activity page's in-page anchors resolve in the rendered DOM.
- All three teaching pages rendered locally. Checked navigation from preparation to the course guide, from the course guide to activities, the physics activity jump link, and the link to the catalog's image review section.
- The activity page retains `noindex`, and experimental warnings and navigation labels remain visible. No browser console errors were reported during verification.
- The existing broad Mintlify broken-link checker limitation described above remains; it was not rerun. Scoped file and browser checks were used for this revision.
- The local preview is running on port 3000. Activities still require rehearsal and educational review before publication; explicit user approval is still pending.

Local review entry: `http://localhost:3000/Guides/Teaching-with-Desktop/activities-and-templates`.
