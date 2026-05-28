# Domain Docs

How engineering and documentation skills should consume this repo's domain documentation.

## Layout

This is a single-context documentation repository for the X-ray Simulator Mintlify support site.

If present, read these before broad documentation, architecture, or workflow changes:

- `CONTEXT.md` at the repo root
- `docs/adr/` for decision records that affect documentation, publishing, or support workflows

If these files do not exist, proceed silently. Do not create them unless the user asks for domain documentation or a decision record.

## Current Domain Anchors

- The production documentation is a Mintlify site.
- `docs.json` controls site configuration and navigation.
- MDX pages are production-facing support documentation for X-ray Simulator users, IT teams, procurement stakeholders, and educators.
- Shared reusable page content lives in `snippets/`.
- Local backlog work lives in `.scratch/docs-backlog/`.

## Vocabulary Rules

Use the product and audience terms already present in the documentation unless the user asks to rename them:

- X-ray Simulator
- VR X-ray Simulator
- Desktop X-ray Simulator
- VitaSim Launcher
- Meta Quest Link
- support, IT approval, procurement, educator guide, setup guide

When a concept needs a new term, note it in the issue or PRD before spreading the term across pages.
