# Documentation Backlog

Status: active
Owner: local

## Purpose

Maintain a local Markdown backlog for production-facing Mintlify documentation improvements.

## Scope

Use this backlog for:

- Single-page rewrites and cleanup
- Navigation and `docs.json` improvements
- Mintlify component and structure fixes
- Missing support content discovered during documentation reviews
- Follow-up work that should be reviewed before production deployment

Do not use this backlog for source-code changes outside the documentation repo unless the user explicitly asks.

## Workflow

1. Add backlog items under `.scratch/docs-backlog/issues/`.
2. Keep each item focused on one page, one navigation change, or one small documentation workflow.
3. Move `Status:` from `needs-triage` to `ready-for-agent` when the issue is specific enough for implementation.
4. Before pushing documentation changes, review the related issue and summarize what changed.

## Issue Statuses

- `needs-triage`: needs a decision or scope refinement
- `needs-info`: blocked on missing user, product, or business information
- `ready-for-agent`: clear enough for an agent to implement
- `ready-for-human`: requires human judgment, credentials, or business approval
- `wontfix`: intentionally not actioned
