---
name: feature-implementation
description: Use this when implementing a new feature with explicit acceptance targets, minimal complexity, and direct verification.
---

When using this skill:

1. Restate the feature in terms of user-visible behavior.
2. Identify assumptions or ambiguity before coding.
3. Define the acceptance target explicitly.
4. Choose the smallest implementation that meets the target.
5. Reuse existing repository patterns whenever possible.
6. Avoid speculative abstractions and future-proofing.
7. Run focused verification against the acceptance target.
8. Report:
   - what was implemented
   - files changed
   - how it was verified
   - limitations or unverified cases

Rules:
- Do not quietly expand the feature scope.
- Do not add configuration unless the task truly requires it.
- Prefer direct implementation over architecture-heavy solutions.
