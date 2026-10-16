# Nullified AI Skills

A curated library of practical, safety-conscious skills for compatible AI coding agents and the LiteLLM Claude Code Skill Hub.

## Included skills

- **coding-debugging** (`engineering`) — Diagnose coding problems, make minimal fixes, and verify results.
- **project-awareness** (`engineering`) — Understand repository architecture, conventions, dependencies, and project context before editing.
- **security-review** (`security`) — Review code for common security issues and protect secrets while proposing actionable fixes.
- **testing-quality** (`engineering`) — Choose and run appropriate tests, linting, type checks, and builds, then report results honestly.
- **full-stack-development** (`engineering`) — Build and maintain full-stack TypeScript and JavaScript applications using existing project conventions.
- **react-nextjs-best-practices** (`web-development`) — Apply practical React and Next.js performance, architecture, and implementation best practices.
- **ui-accessibility-review** (`design`) — Review interfaces for usability, responsive layout, accessibility, and consistent design systems.
- **api-design-validation** (`backend`) — Design and review APIs with clear contracts, validation, authorization, and predictable errors.
- **database-prisma-migrations** (`backend`) — Work safely with relational databases, Prisma schemas, queries, and migrations.
- **git-pull-request-review** (`workflow`) — Review Git diffs and pull requests for correctness, regressions, security, and maintainability.
- **docker-devops** (`devops`) — Develop and troubleshoot Docker, Docker Compose, and repeatable development environments.
- **ci-cd-release** (`devops`) — Create and troubleshoot CI pipelines and safe release checklists.
- **documentation-readme** (`documentation`) — Write and maintain accurate READMEs, setup instructions, API documentation, and changelogs.
- **performance-profiling** (`engineering`) — Find performance bottlenecks using evidence before optimizing code.
- **incident-troubleshooting** (`operations`) — Troubleshoot service failures systematically using logs, health checks, and safe recovery steps.
- **discordjs-bot-development** (`specialized-development`) — Build and maintain Discord.js bots with secure commands, permissions, and robust interactions.
- **minecraft-plugin-development** (`specialized-development`) — Develop and troubleshoot Minecraft Java server plugins with compatibility and permission safety.
- **proxmox-homelab-operations** (`operations`) — Help operate Proxmox and homelab services with careful checks around storage, networking, and backups.
- **research-documentation** (`research`) — Research technical questions using primary documentation and report source-backed conclusions.
- **dependency-upgrades** (`engineering`) — Evaluate and apply dependency upgrades carefully with compatibility checks and rollback awareness.
- **data-migration-safety** (`backend`) — Plan safe data migrations with validation, backups, and rollback strategies.
- **accessibility-testing** (`testing`) — Create and run practical accessibility checks for web applications.
- **observability-logging** (`operations`) — Improve logs, metrics, traces, and health checks without leaking sensitive information.

## Layout
Each skill is in its own folder with `SKILL.md` and `plugin.json`.

## Publishing
Register each skill from its GitHub subdirectory in your LiteLLM Skills UI/API, then review and enable it for the marketplace. Verify the exact source format supported by your installed LiteLLM version before bulk registration.

## Safety
- No provider keys or secrets belong in this repository.
- Skills instruct the agent; they do not grant tools or permissions by themselves.
- Review skills before publishing or enabling them.
- This repository contains original curated instructions. External collections such as Vercel Agent Skills and Superpowers are references for further review, not copied wholesale into this repository.
