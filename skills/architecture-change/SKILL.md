---
name: architecture-change
description: Use this when a task may require architectural or design-level changes.
---

When using this skill:

1. Explain why the current architecture is insufficient.
2. Propose the minimal architectural change required.
3. Compare alternatives and tradeoffs.
4. Do not proceed with large architectural changes silently.
5. Explicitly state blast radius and migration risk.

Rules:
- Prefer the smallest structural change that solves the current problem.
- Do not add new layers, frameworks, or abstractions without clear justification.
- If a local change is sufficient, prefer it over a system-wide redesign.
