---
name: frontend-ui-change
description: Use this when modifying existing UI while minimizing visual regressions and preserving design consistency.
---

When using this skill:

1. Restate the requested UI change in user-visible terms.
2. Identify the smallest set of components, styles, and routes involved.
3. Inspect existing design patterns before editing.
4. Reuse existing components, tokens, spacing, and interaction patterns whenever possible.
5. Avoid changing unrelated layout, styling, or behavior.
6. Check for responsiveness, accessibility, interaction states, and visual consistency.
7. Report changed components, visible behavior changes, and verification performed.

Rules:
- Do not introduce a new visual pattern unless explicitly requested.
- Do not silently change spacing, colors, or interactions outside scope.
