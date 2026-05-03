---
project: lawless-web-app
updated: 2026-05-03
---

# Current State

`lawless-web-app` is the future official web app for `uselawless.com`. It owns routing, auth, account/case state, billing, product navigation, and deployment.

# Important Boundaries

- Product-specific intelligence belongs under typed product modules.
- The webapp repo should host the `lawless-workflow` skill and install page, but not the shared company context itself.
- Shared context lives in this separate `lawless-context` repo.

# Next Work

- Keep `/context` as the simple install surface for teammates.
- Verify Vercel deployment after build blockers are cleared.

