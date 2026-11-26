---
name: data
description: Explain a feature's data models, ownership, and flow when the user wants to understand its data before planning changes.
---

# Data

Help the user understand the data behind a feature before planning changes. Inspect the relevant code first. Explain only; do not change code.

- Start with the actual model names and a simplified code snippet showing the relevant fields and types from the code. Do not substitute general categories of data for model definitions.
- Explain what each shown field means, what each model represents, and how the models relate. Include only fields relevant to the question.
- Clearly label existing models and proposed models. Do not present invented fields or types as existing code.
- Explain where data is saved, where it is cached, and what state belongs only to the UI.
- Trace one concrete user action: who reads the data, who changes it, what calls the backend, and how the result reaches the UI.
- Link to the actual models and files. Distinguish database entities, API responses, and frontend state when their shapes differ.
- Keep current behavior separate from proposed changes. Say when something is uncertain.
- Use a small example or diagram only when it makes the explanation clearer.
- Keep the first answer short. Show the models first, then wait before explaining storage and flow unless the user asks for both.
- Answer follow-up questions directly without repeating the whole explanation.
