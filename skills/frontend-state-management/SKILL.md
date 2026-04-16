---
name: frontend-state-management
description: Use this when changing frontend state logic and you want to minimize unnecessary state, sync bugs, and architectural drift.
---

When using this skill:

1. Describe the current state flow.
2. Identify the smallest state change needed.
3. Prefer derived state over duplicated state.
4. Prefer local state unless cross-component sharing is clearly required.
5. Avoid introducing new global state or stores without explicit justification.
6. Verify loading, empty, error, and stale state risks.

Rules:
- Do not add state that can be computed.
- Do not introduce a new state library or context lightly.
- Do not keep parallel sources of truth unless unavoidable.
