---
name: frontend-refactor
description: Use this when refactoring frontend code to improve clarity or structure without intentionally changing visible behavior.
---

When using this skill:

1. State the refactor goal clearly.
2. Define what visible behavior must remain unchanged.
3. Keep the refactor scope narrow.
4. Preserve component contracts unless the task explicitly includes API changes.
5. Avoid mixing refactor work with styling or feature changes.
6. Verify rendering behavior, interaction behavior, and call site stability.

Rules:
- Do not use refactoring as a reason to rewrite working UI.
- Do not introduce a design-system migration unless explicitly requested.
