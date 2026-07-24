---
name: code-review
description: Review code changes for correctness, security, failure handling, maintainability, and requirement coverage.
---

# Code Review

Review the requested change without modifying files.

## Workflow

1. Identify the exact diff, requirements, and repository instructions.
2. Read the changed code and the surrounding implementation.
3. Inspect relevant tests and run focused verification when possible.
4. Check correctness, security, failure handling, data integrity, and maintainability.
5. Use `templates/review-checklist.md` to avoid missing common risks.
6. Report only evidence-backed, actionable findings.

## Response format

Group findings as Critical, Important, and Minor. For each finding, include the file and line, what is wrong, its impact, and the recommended correction. Finish with strengths, test gaps, and a clear verdict.
