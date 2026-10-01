# Experimental Desktop course rollout documentation

Status: draft for user review

Approval: not approved for merge or publication

## Customer need

A faculty customer needs help planning a course or cohort rollout of the Desktop X-ray Simulator. Installation instructions and the simulation catalog already exist; the missing guidance connects access, course scheduling, teaching activities, responsibilities, and review.

## Scope and language

Use **Teaching** as the shared faculty-facing top tab, visibly marked **Experimental** during review. A short overview identifies the available resources by product, with the current guides grouped under **Desktop**. State that VR teaching resources are not available yet; link to existing VR usage instructions without presenting them as teaching activities or promising future resources. A **course rollout plan** is the institution's working plan for cohort scope, scheduled activities, responsibilities, access, feedback, and review. It is separate from technical software deployment. Keep product facts in existing canonical setup, account, and simulator reference pages.

Keep the three Desktop guides at their existing URLs and move their navigation from Docs into the Teaching tab in the current version. Add a short shared overview at `Teaching/overview`, linked from Welcome. Keep the Desktop quick-start link pointing directly to the course guide. Lead the guides with a worked course example, specific student instructions, and an adaptable student announcement. Do not promise automated grading, LMS integration, reporting, validated learning outcomes, or a new VitaSim service.

## Faculty-first revision

The primary reader is a faculty member introducing Desktop to a course. They know teaching and radiography but may be unfamiliar with the simulator. Each section must help them decide, act, interpret a result, or resolve a likely difficulty.

- Main guide: show how demonstration, paired practice, independent work, and feedback can fit into an existing wrist radiography topic. Help faculty plan access, timing, work, and feedback for the first group.
- Preparation: try the activity, arrange computers/logins, and tell students what to expect. Put technical setup detail behind an IT handoff link.
- Activities: use the five applications supplied by the user: live error correction, homework with manual image submission, paired image-making, kVp/mAs/distance exploration, and creating controlled image sequences for teaching slides. Add peer feedback/revision and early/later comparisons as optional extensions. Give each activity concrete actions and an educational purpose without turning every idea into a full lesson plan.
- Distinguish instructor-only use from student practice so a demonstration or slide preparation does not imply a student installation project.
- Treat installation, receipt of the intended simulator login, and opening a case on the actual computers as prerequisites. Put a session 0 before student practice: demonstrate the necessary controls in short steps, let every student try, and finish with an independent adjustment and image export. Link this preparation from both the course plan and activity page.
- Replace repeated planning tables and blank forms with an example and short decisions faculty can keep in their existing course plan.
- Preserve experimental status and the explicit merge/publication approval requirement. Concise page warnings carry review status; detailed governance stays in AGENTS.md and the experiment note.

The teaching ideas are grounded in the user's practice and the catalog/Desktop control documentation. They have not been run in the simulator during this work. Before publication, VitaSim must verify the exact case/view labels, control behavior, starting setups, and comparisons, capture real example images, and have a radiography educator review the activities. The inverse-square-law calculation is separate from observing an image; no quantitative simulator validation or brightness-based measurement is claimed. Do not ask faculty to compensate for unverified product instructions or present the examples as tested.

## Completion criteria

- Isolated experimental branch/worktree, with explicit user approval required for merge/publication.
- Visible experimental warning on each new page and navigation entry.
- Useful course rollout plan, faculty/student readiness guidance, and practical activities.
- Mintlify validation, link checks, and local browser verification.
- Running localhost preview shared for user review.
