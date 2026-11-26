---
name: explain
description: Explain current uncommitted changes in one grouped overview, then explain a selected component, file, or block in detail on request.
---

# Explain

Inspect the current uncommitted changes, including relevant new files, and enough surrounding code to understand them. Explain the changes; do not modify code or commit.

Explain all changes in one response, grouped by responsibility and ordered by the flow from the user action or entry point. Give each group a clear heading, clickable file links, and a short explanation of what changed, why, and how it connects to the next group. Keep method-level detail out of this overview. Use a concrete example when helpful.

Keep each group concise and easy to scan. Do not pause between groups or require the user to say "next." Skip test files for this walkthrough; this does not mean tests should be skipped during implementation.

When the user points to a component or file, focus on that part: explain its job, what each method does, and how the methods connect in the flow. Link to the relevant code and use plain language. For a selected block, explain that block and the context needed to understand it. Do not repeat the full overview.

If the changes have no runtime sequence, use the simplest logical order and briefly explain it. Do not invent reasons for changes that the code and conversation do not establish.
