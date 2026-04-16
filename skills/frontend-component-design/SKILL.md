---
name: frontend-component-design
description: Use this when creating or reshaping a reusable frontend component with explicit attention to reuse boundaries and API simplicity.
---

When using this skill:

1. Define the component purpose in one sentence.
2. Identify whether an existing component can be extended instead of creating a new one.
3. Design the smallest API that satisfies the current use case.
4. Prefer composition over configuration-heavy props.
5. Match existing naming, file layout, styling, and prop conventions.
6. Keep accessibility and semantic HTML in scope by default.

Rules:
- Do not create “universal” components for hypothetical future use.
- Avoid prop explosion.
- Avoid component abstraction when a local component is enough.
