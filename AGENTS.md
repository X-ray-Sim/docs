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

## Release work with agents

- Look up the matching Linear issue before starting. Create new agent work in **Codex and Claude (AIX)**. Keep historical issue references. Add the issue to [X-ray Simulator 2.0.0](https://linear.app/vitasim/pipeline/x-ray-simulator/release/200-20262-3963bce5cfd6) when its outcome belongs to that release.
- Check the working tree, the fetch and push destinations of `origin` (GitHub `X-ray-Sim/docs`), and the intended PR base. Use a named worktree branch based on `origin/main`. After local review, a human publishes the branch under the collaboration rules below.
- Include the actual AIX issue ID in new agent plans, branch names, fixing commits and PR titles. Link each contributing PR to the issue. Use a closing reference only when the PR completes the whole issue.
- At handoff, update the Linear issue with the repo, branch and commit, whether it was pushed, PR or **no PR**, merge destination, checks and results, deployed environment and revision (or **not deployed**), and the next step. For local-only work, include the worktree path. For a merge, link the PR and merge commit. Record shared release decisions in the [release overview](https://linear.app/vitasim/document/x-ray-simulator-200-release-overview-and-readiness-e5859ef15b07).

## Collaboration Rules

- Keep edits scoped to the requested documentation change.
- Preserve the existing tone and information architecture unless the user asks to restructure it.
- For change work, create or use an isolated git worktree unless the user explicitly asks to work in the current checkout.
- Run `npm run validate`, launch the local Mintlify preview with `npm run dev:no-open`, and share the localhost review URL before marking the change ready for review. On Windows use `npm.cmd` when needed.
- Never push changes from an agent session. Pushing to any remote is a manual human gate after review.
- When changing navigation, update `docs.json` and verify page paths match actual files.
- For production-facing content changes, summarize what changed and call out any pages or config areas that should be reviewed before pushing.

## Agent skills

### Issue tracker

Use the matching Linear issue for active documentation work. See `docs/agents/issue-tracker.md` for the historical backlog.

### Triage labels

Use the current AIX team workflow for active issues. See `docs/agents/triage-labels.md` for historical labels.

### Domain docs

This is a single-context documentation repo for the X-ray Simulator Mintlify support site. See `docs/agents/domain.md`.
