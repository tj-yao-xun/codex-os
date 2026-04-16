---
name: frontend-bugfix
description: Use this when fixing a frontend bug while minimizing UI regressions and preserving existing behavior outside the failing path.
---

When using this skill:

1. Describe the bug in terms of visible behavior.
2. Identify the route, component, and state path involved.
3. Reproduce or trace the failing interaction.
4. Make the smallest viable fix.
5. Check adjacent frontend risks such as responsiveness, focus behavior, and visual regression.
6. Verify the bug path directly.

Rules:
- Do not refactor surrounding frontend architecture unless required.
- Do not redesign the UI while fixing a bug unless explicitly requested.
