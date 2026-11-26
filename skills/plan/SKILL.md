---
name: plan
description: Plan a requested code change as simple commit phases before implementation, with a brief explanation of the overall approach.
---

# Plan

Plan the whole requested change before writing code. First inspect the relevant code and callers. Choose the simplest approach that fully meets the requirement:

- Reuse existing components, helpers, and patterns.
- Prefer existing platform features or installed dependencies over new code.
- Avoid extra features, abstractions, and dependencies.
- Keep the code easy to read.
- Preserve validation, error handling, and security. Include tests where needed.

Follow the current repo's architecture guidelines. Keep feature and state ownership clear, reuse shared logic, and give each part a clear responsibility. Do not add layers a small change does not need.

Explain the overall approach simply. Split it into commit phases, with one or two sentences about what each phase achieves. Keep each phase focused and leave the app working. For a small change, one phase is enough.

Add file or code details only when needed to explain the approach. Do not turn each phase into a detailed file checklist. Do not write code or create commits yet.
