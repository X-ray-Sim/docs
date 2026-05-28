# Fix Desktop Getting Started Structure

Status: ready-for-agent
Priority: P2
Area: Desktop Guides
Page: Guides/Introduction/getting-started-Desktop-x-ray.mdx

## Problem

The page uses the `DesktopXRaySimulatorSteps` snippet before the import statement appears. The content is otherwise useful but could benefit from a clearer first-success workflow.

## Proposed Change

Move the import before usage and add a short workflow overview covering login, case selection, positioning, exposure, and image export.

## Acceptance Criteria

- The MDX import appears before component usage.
- Existing screenshots remain in place.
- The page starts with a concise overview of what the user will learn.
- The setup snippet still renders correctly.

## Comments
