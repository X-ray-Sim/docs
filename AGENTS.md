# Project Context

This repository is the Mintlify documentation site for X-ray Simulator support.

Pushed changes are automatically picked up by Mintlify and rendered in production. Treat changes to the default branch as production documentation changes, especially edits to `docs.json`, navigation, shared snippets, and high-traffic pages.

## Mintlify

- `docs.json` is the Mintlify site configuration and navigation source.
- Documentation pages are MDX files in the existing content folders.
- Shared reusable content lives in `snippets/`.
- Images and static assets should stay in the existing asset folders unless a change needs a new structure.
- Before making Mintlify-specific changes to `docs.json`, navigation, frontmatter, components, snippets, redirects, OpenAPI/API docs, or build/validation behavior, check the current official Mintlify documentation or a connected Mintlify documentation MCP. Do not rely only on memory for Mintlify syntax or config.
- Plain wording edits to existing MDX pages can be made from local context, but check Mintlify references before changing page structure or component usage.

Useful references:

- https://www.mintlify.com/docs
- https://www.mintlify.com/docs/llms.txt
- https://www.mintlify.com/docs/organize/settings-reference
- https://www.mintlify.com/docs/organize/navigation
- https://www.mintlify.com/docs/organize/pages
- https://www.mintlify.com/docs/ai/model-context-protocol
- https://www.mintlify.com/docs/ai/mintlify-mcp

## Collaboration Rules

- Keep edits scoped to the requested documentation change.
- Preserve the existing tone and information architecture unless the user asks to restructure it.
- For change work, create or use an isolated git worktree unless the user explicitly asks to work in the current checkout.
- After making changes, run the docs locally with the Mintlify preview server and share the localhost review URL before considering the work ready for review.
- Never push changes from an agent session. Pushing to any remote is a manual human gate after review.
- When changing navigation, update `docs.json` and verify page paths match actual files.
- For production-facing content changes, summarize what changed and call out any pages or config areas that should be reviewed before pushing.

## Agent skills

### Issue tracker

Documentation work is tracked as local Markdown under `.scratch/docs-backlog/` and related `.scratch/<feature-slug>/` folders. See `docs/agents/issue-tracker.md`.

### Triage labels

Local backlog issues use `Status:` values matching the default five triage roles. See `docs/agents/triage-labels.md`.

### Domain docs

This is a single-context documentation repo for the X-ray Simulator Mintlify support site. See `docs/agents/domain.md`.
