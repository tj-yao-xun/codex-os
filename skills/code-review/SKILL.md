---
name: code-review
description: Use this when reviewing code changes for correctness, regression risk, scope control, and maintainability.
---

When using this skill:

1. Read the change with the requested scope in mind.
2. Prioritize findings in this order:
   - correctness
   - regression risk
   - security / safety risk
   - scope creep
   - maintainability
   - style consistency

3. For each important finding, state:
   - what the issue is
   - why it matters
   - how confident you are
   - the smallest reasonable fix

4. Distinguish must-fix issues from optional improvements.
5. Do not invent problems without code evidence.
6. Say clearly if no material issue was found in the reviewed scope.

Review output format:
- Summary
- Must fix
- Should fix
- Nice to have
- Unverified areas
