<p align="center">
  <img src="assets/logo.png" width="120" />
</p>

![Codex OS Banner](assets/banner.png)

# Codex OS

> Production-grade workflow rules, skills, and guardrails for Codex-powered development.

Transform Codex from a code generator into a disciplined engineering agent.

[Installation](#installation) • [Philosophy](#philosophy) • [Included Skills](#included-skills) • [Roadmap](#roadmap)

---

## Why Codex OS Exists

Most AI coding failures are not caused by weak models.

They are caused by weak workflows.

Common failure modes:
- Hidden assumptions
- Overengineering
- Scope creep
- Unsafe command execution
- Unverified "fixes"
- Temporary workarounds disguised as completed solutions

Codex OS addresses these with production-oriented workflow engineering.

---

## Philosophy

Codex OS is built around these principles:

### Think Before Coding
Never silently assume.

### Simplicity First
Solve the present problem only.

### Surgical Changes
Minimize blast radius.

### Goal-Driven Execution
Never claim success without verification.

### Avoid Temporary Workarounds
Prefer proper, maintainable solutions over hacks, placeholder logic, and short-term patches.

### Match Repository Conventions
Consistency beats generic elegance.

### Escalate Before Architecture Changes
Do not silently introduce large abstractions or structural shifts.

### Prefer Testable Changes
Favor changes with direct verification paths.

### Respect Existing Boundaries
Do not merge unrelated concerns into the same change.

### Hotfix Awareness
Emergency fixes may optimize for restoration first, but tradeoffs must be explicit.

### Report Clearly
Always state what changed, why, what was verified, and what remains unverified.

---

## Architecture

```text
AGENTS.md   -> Global behavioral defaults
rules/      -> Execution guardrails
skills/     -> Task-specific workflows
examples/   -> Example prompts and workflow usage
```

---

## Installation

### Global setup

```bash
mkdir -p ~/.codex
```

Then place:
- `AGENTS.md` in `~/.codex/`
- `.rules` files in `~/.codex/rules/`
- skill folders in `~/.codex/skills/`

---

## Included Skills

### Core skills
- `surgical-bugfix`
- `safe-refactor`
- `repo-explainer`
- `code-review`
- `feature-implementation`

### Advanced engineering skills
- `architecture-change`
- `hotfix-mode`
- `test-first`

### Frontend pack
- `frontend-ui-change`
- `frontend-component-design`
- `frontend-state-management`
- `frontend-bugfix`
- `frontend-refactor`

---

## Example Usage

### Core bugfix
```text
Fix the login redirect bug using surgical-bugfix.
```

### Architecture-sensitive task
```text
Evaluate whether this task requires architecture-change before implementation.
```

### Emergency fix
```text
Apply this rollback patch using hotfix-mode.
```

### Frontend work
```text
Implement this settings modal using frontend-ui-change.
```

---

## Roadmap

- [x] Core workflow pack
- [x] Frontend workflow pack
- [ ] Backend workflow pack
- [ ] Infra / DevOps workflow pack
- [ ] Team / Enterprise presets

---

## License

MIT

