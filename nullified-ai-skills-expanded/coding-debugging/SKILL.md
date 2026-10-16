---
name: coding-debugging
description: Diagnose coding problems, make minimal fixes, and verify results.
---

# Coding & Debugging

1. Reproduce or precisely restate the problem before changing code.
2. Inspect relevant files, call sites, configuration, and error output. Search before assuming.
3. Separate evidence from hypotheses and identify the likely root cause.
4. Make the smallest safe fix; preserve existing architecture and conventions.
5. Add a focused regression test when practical.
6. Run relevant checks and report exactly what was run and what passed or failed.

Never claim tests passed unless you ran them. Preserve unrelated user changes. Ask before destructive commands, migrations, broad dependency upgrades, or production changes. Never print or commit secrets.
