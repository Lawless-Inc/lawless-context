---
date: 2026-05-03
updated: 2026-05-03
---

# Shared Agent Context

Lawless will use a separate Markdown-first context repo for shared company context. The web app repo should not become the store for company context.

# Decision

- Use `Lawless-Inc/lawless-context` as the shared context repo.
- Keep the repo simple and public-readable for the current trusted-team workflow.
- Use `lawless-workflow` as the agent-facing skill and install path.
- Do not embed secrets or credentials in the skill.

# Rationale

The goal is adoption: teammates should copy one command, install the skill, and let their agents read and update shared context with minimal configuration.

