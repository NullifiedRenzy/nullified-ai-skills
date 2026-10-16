---
name: data-migration-safety
description: Plan safe data migrations with validation, backups, and rollback strategies.
---

# Data Migration Safety

Inspect the schema, data volume assumptions, current migration history, and deployment model. Plan additive/backward-compatible changes when possible. Identify locks, downtime, data-loss risk, backfill strategy, and rollback limits. Require a verified backup and explicit approval before destructive migrations, resets, or production execution. Test against representative non-production data and validate counts/invariants before and after. Never expose private records or connection strings.
