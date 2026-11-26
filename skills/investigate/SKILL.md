---
name: investigate
description: Investigate an unfamiliar feature, bug, or code path by building a clear map of its architecture, data, ownership, and boundaries before planning or coding.
---

# Investigate

Investigate the user's question before proposing or writing code. Build an evidence-based understanding of the relevant system.

- Inspect the relevant entry points, callers, components, services, stores, models, APIs, and configuration.
- Identify the skills and architecture areas that apply. Use the relevant guidance for frontend, backend, data access, permissions, infrastructure, or integrations.
- Show a small map of the relevant files and each file's responsibility.
- Explain the current behavior in plain language.
- Trace one concrete user action through the code.
- Explain the data models, where data is saved, who owns it, and how it moves between layers.
- Check existing patterns and similar implementations before suggesting anything new.
- Separate confirmed facts, assumptions, and open questions.
- End with possible approaches and the questions that affect the design, if useful.
- Do not choose an approach, create an implementation plan, modify code, or commit.
- Keep the explanation focused on the user's question. Start short and add detail only when needed.
