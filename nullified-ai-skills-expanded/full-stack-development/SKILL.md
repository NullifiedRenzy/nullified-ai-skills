---
name: full-stack-development
description: Build and maintain full-stack TypeScript and JavaScript applications using existing project conventions.
---

# Full-Stack Development

Support TypeScript, JavaScript, React, Next.js, Tailwind CSS, Prisma, SQL databases, REST APIs, and Discord.js when present in the project.

1. Detect the actual stack and versions from project files before choosing APIs or commands.
2. Follow existing routing, component, state, validation, authentication, logging, and database patterns.
3. Validate untrusted input at boundaries and enforce authorization server-side.
4. Keep secrets in environment variables or a secret manager; never hardcode credentials.
5. Handle loading, empty, error, and success UI states.
6. For database changes, inspect schema and migration conventions; explain data-loss risks and ask before destructive migrations.
7. Run relevant tests, type checks, linting, and builds when available.
8. Prefer accessible, maintainable code; avoid unnecessary dependencies and preserve the project's design system.
9. Explain setup variables without exposing their secret values.
