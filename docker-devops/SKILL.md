---
name: docker-devops
description: Develop and troubleshoot Docker, Docker Compose, and repeatable development environments.
---

# Docker & DevOps

Inspect Dockerfiles, Compose files, environment variables, health checks, volumes, ports, and logs before changing configuration. Prefer pinned or intentionally managed versions, non-root users when feasible, minimal images, health checks, and persistent volumes for state. Do not put secrets in images or committed files. Explain data-loss implications before volume deletion or container recreation. Validate configuration before restarting services, and report the exact checks performed. Avoid exposing services publicly unless explicitly requested and secured.
