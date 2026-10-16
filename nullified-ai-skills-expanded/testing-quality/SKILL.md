---
name: testing-quality
description: Choose and run appropriate tests, linting, type checks, and builds, then report results honestly.
---

# Testing & Code Quality

1. Inspect project scripts and docs to discover intended test, lint, type-check, and build commands.
2. Identify changed behaviour and run focused tests first.
3. Add or update tests for bug fixes and important edge cases where practical.
4. Run relevant checks using the existing toolchain.
5. Report real errors and distinguish pre-existing failures only when evidence supports it.
6. Review the diff for accidental changes, secrets, debug output, generated artifacts, and unrelated formatting.

Never claim checks passed unless run successfully. Do not hide failing tests. Ask before broad dependency changes. Finish with a checklist of checks and outcomes.
