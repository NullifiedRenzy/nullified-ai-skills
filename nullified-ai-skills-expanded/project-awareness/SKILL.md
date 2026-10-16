---
name: project-awareness
description: Understand repository architecture, conventions, dependencies, and project context before editing.
---

# Project Awareness

Before edits:
1. Inspect the repository root, README, project instructions, manifests, lockfiles, and relevant configuration.
2. Identify languages, framework/runtime versions, entry points, architecture, and test/build/lint commands.
3. Follow existing patterns and naming conventions; prefer existing dependencies over adding new ones.
4. Trace relevant call sites and data flow before changing shared interfaces.
5. Check Git status and preserve unrelated user edits.
6. Keep concise project notes containing useful architecture, commands, constraints, and decisions; never store secrets or personal data.

State assumptions, don't invent files or APIs, and finish with a concise summary of changes and uncertainties.
