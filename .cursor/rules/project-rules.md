# Cursor Project Rules

## General Philosophy

This project follows professional software engineering workflows.

Priorities:
1. Stability
2. Readability
3. Small safe iterations
4. Clear architecture
5. Maintainability

Avoid unnecessary complexity.

---

## Before Making Changes

Always:
- read relevant docs
- inspect existing architecture
- understand affected files
- avoid assumptions

Never start coding blindly.

---

## Change Rules

- Make small focused changes only.
- Do not modify unrelated files.
- Do not rewrite architecture without approval.
- Do not introduce unnecessary abstractions.
- Prefer explicit readable code.

---

## AI Workflow

ChatGPT:
- brainstorming
- architecture
- specifications

Claude Code:
- implementation
- refactoring
- testing

Cursor:
- inspection
- editing
- navigation
- review assistance

Human:
- final approval
- architecture decisions
- production decisions

---

## Testing Rules

When changing logic:
- update tests if needed
- run tests before completion
- avoid breaking existing functionality

---

## Documentation Rules

Important engineering changes should update:
- TASKS.md
- PROJECT_STATE.md
- relevant specs

Documentation is part of development.

---

## Never

- Never commit secrets.
- Never bypass validation intentionally.
- Never deploy directly to production.
- Never delete unrelated code.
- Never perform large rewrites without approval.

---

## Preferred Engineering Style

Prefer:
- simple architecture
- explicit logic
- modularity
- readability
- deterministic behavior

Avoid:
- magic behavior
- overengineering
- premature optimization
- hidden side effects