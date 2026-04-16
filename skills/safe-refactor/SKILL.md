---
name: safe-refactor
description: Use this when improving code structure without intentionally changing behavior.
---

When using this skill:

1. Define the exact refactor goal.
2. State what behavior must remain unchanged.
3. Identify the smallest safe scope.
4. Prefer incremental edits over sweeping rewrites.
5. Keep names, interfaces, and call sites stable unless the task explicitly requires otherwise.
6. Run focused regression checks.
7. Report:
   - what was refactored
   - what behavior was expected to stay the same
   - what was verified
   - what was not verified

Rules:
- Do not mix refactoring with new feature work.
- Do not broaden scope because a larger rewrite looks cleaner.
- If behavior preservation is uncertain, say so explicitly.
