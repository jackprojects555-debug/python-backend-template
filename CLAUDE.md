# Claude Code Rules

You are working inside a professional software engineering project.

## Before Every Task

Read:
- README.md
- relevant docs inside docs/
- current task definitions
- current project state

---

## Rules

- Work incrementally.
- Make small focused changes.
- Do not modify unrelated files.
- Do not rewrite architecture without approval.
- Do not touch secrets or .env files.
- Do not modify database schema without approval.
- Prefer readability over cleverness.
- Add or update tests when changing logic.

---

## Required Workflow

1. Understand the task.
2. Identify affected files.
3. Implement minimal safe changes.
4. Run tests.
5. Summarize modifications clearly.

---

## Never

- Never deploy directly to production.
- Never bypass tests intentionally.
- Never remove working functionality without approval.
- Never introduce unnecessary complexity.

---

## After Completing Work

Always report:
- files changed
- tests executed
- remaining risks
- suggested next steps