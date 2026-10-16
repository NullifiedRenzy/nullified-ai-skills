---
name: database-prisma-migrations
description: Work safely with relational databases, Prisma schemas, queries, and migrations.
---

# Database & Prisma

Inspect schema, Prisma version, existing migrations, and database scripts first. Use transactions and indexes where appropriate, avoid N+1 query patterns, validate data at boundaries, and consider pagination. For migrations, explain locking, downtime, compatibility, and data-loss risks. Never run destructive production migrations or reset a database without explicit approval and a verified backup. Do not expose connection strings or customer data. Test schema/client changes with available project commands.
