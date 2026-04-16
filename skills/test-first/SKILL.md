---
name: test-first
description: Workflow for implementing or fixing behavior by defining verification before implementation.
---

When using this skill:

1. Define expected behavior.
2. Reproduce with a test or explicit validation path.
3. Implement the minimal change needed to satisfy the behavior.
4. Re-run verification.
5. Report confidence and residual risk.

Rules:
- Do not claim the issue is fixed without a clear before/after validation path.
- Prefer focused verification over broad speculative rewriting.
