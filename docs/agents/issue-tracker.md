# Issue Tracker: Local Markdown

Issues, PRDs, and documentation backlog items for this repo live as Markdown files in `.scratch/`.

## Primary Backlog

The standing documentation backlog is:

```text
.scratch/docs-backlog/
```

Use this backlog for production documentation improvements, page rewrites, navigation cleanup, Mintlify configuration work, and follow-up tasks discovered during documentation reviews.

## Conventions

- One feature or workstream per directory: `.scratch/<feature-slug>/`
- The workstream overview or PRD is `.scratch/<feature-slug>/PRD.md`
- Implementation issues are `.scratch/<feature-slug>/issues/<NN>-<slug>.md`, numbered from `01`
- Triage state is recorded as a `Status:` line near the top of each issue file
- Priority is recorded as a `Priority:` line near the top of each issue file
- Comments and conversation history append to the bottom of the file under a `## Comments` heading

## Issue Format

Use this shape for local backlog items:

```markdown
# Short imperative title

Status: needs-triage
Priority: P2
Area: Documentation
Page: path/to/page.mdx

## Problem

What is wrong or missing?

## Proposed Change

What should change?

## Acceptance Criteria

- Concrete outcome
- Verification step

## Notes

Extra context, links, or dependencies.

## Comments
```

## When A Skill Says "Publish To The Issue Tracker"

Create a new file under `.scratch/<feature-slug>/` or `.scratch/docs-backlog/issues/`, creating directories if needed.

## When A Skill Says "Fetch The Relevant Ticket"

Read the file at the referenced path. The user will normally pass the path or the issue number directly.
