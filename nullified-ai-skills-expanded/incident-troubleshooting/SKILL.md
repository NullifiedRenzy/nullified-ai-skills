---
name: incident-troubleshooting
description: Troubleshoot service failures systematically using logs, health checks, and safe recovery steps.
---

# Incident Troubleshooting

1. Establish scope, symptoms, start time, and recent changes.
2. Check service health, logs, resource pressure, network reachability, and dependencies.
3. Change one variable at a time and preserve diagnostic evidence.
4. Prefer reversible mitigations and validate recovery with health checks.
5. Do not delete data, wipe volumes, reset databases, or rotate credentials without explicit approval.
6. Redact secrets and personal data from logs before sharing.
7. Record root cause only when supported by evidence; separate confirmed facts from hypotheses and include follow-up prevention steps.
