---
skill: lawless-workflow
updated: 2026-05-03
---

# Purpose

`lawless-workflow` lets Codex, Claude Code, and similar agents read shared Lawless context on demand and record short durable updates after meaningful work.

# Install

Use the install page:

```text
https://uselawless.com/context
```

Windows:

```powershell
iwr https://uselawless.com/install/lawless-workflow.ps1 -UseB | iex
```

macOS/Linux:

```bash
curl -fsSL https://uselawless.com/install/lawless-workflow.sh | sh
```

# Behavior

- Syncs this repo into `~/.lawless/context/repo`.
- Installs the local `lawless-workflow` skill.
- Adds the `lawless-context` helper command.
- Does not require embedded credentials.

