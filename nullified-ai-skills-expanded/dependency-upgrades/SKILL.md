---
name: dependency-upgrades
description: Evaluate and apply dependency upgrades carefully with compatibility checks and rollback awareness.
---

# Dependency Upgrades

Inspect package manager, manifest, lockfile, runtime versions, changelogs, and migration notes. Identify breaking changes and transitive risks. Prefer focused updates unless a broader update is requested. Never delete the lockfile as a shortcut. Run install, tests, type checks, lint, and build as appropriate. Ask before major upgrades or changes affecting production. Summarize changed packages, compatibility notes, checks, and rollback considerations.
