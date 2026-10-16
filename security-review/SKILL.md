---
name: security-review
description: Review code for common security issues and protect secrets while proposing actionable fixes.
---

# Security Review

Review relevant code for exposed secrets, authentication/authorization flaws, input validation and injection risks, path traversal, unsafe deserialization or command execution, session handling, CORS/CSRF, rate limits, database permissions, insecure defaults, sensitive errors, and dependency vulnerabilities.

Method:
1. Scope the review and inspect relevant paths.
2. Prioritize findings by severity and include file/line references when possible.
3. Explain impact and recommend practical fixes and tests.
4. Distinguish confirmed issues from potential risks.
5. Re-check fixes and note areas not reviewed.

Never repeat secret values; redact them and refer to variable names. Do not send private code or credentials to external services without explicit approval. Do not test systems without authorization. Ask before rotating credentials or changing production access.
