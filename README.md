# hemmy-skills

Personal AI coding skills for understanding an app, planning a change, and building it in small steps.

The goal is simple: keep the conversation clear and understand the code you ship.

## Workflow

`$chat` → `$investigate` → `$plan` → `$build` → `$explain` → `$commit`

Repeat build, explain, and commit for each phase. Use map, data, or simple whenever you need a closer look. These are tools to choose from, not required steps for every change.

| Skill | Purpose | Example |
| --- | --- | --- |
| `$chat` | Keep the conversation brief and direct. | `$chat Explain why this behavior exists.` |
| `$map` | Find the relevant files and understand their jobs. | `$map Show the files involved in task creation.` |
| `$data` | Understand models, fields, ownership, and data flow. | `$data Show the task model and how an assignee change is saved.` |
| `$investigate` | Inspect the current behavior and architecture before planning. | `$investigate Find how task notifications open task details.` |
| `$plan` | Plan the whole change in small commit phases. | `$plan Plan adding a file preview panel.` |
| `$build` | Implement the next phase and run relevant checks, without committing. | `$build Implement the next planned phase.` |
| `$explain` | Give a grouped overview of changes, then explore selected code. | `$explain Walk me through the uncommitted changes.` |
| `$simple` | Build intuition for code that is hard to grasp. | `$simple Explain why this store is needed.` |
| `$commit` | Commit one completed phase with a clear title and description. | `$commit Commit the completed phase.` |

## Install

Ask Codex to install the skills you want:

```text
Use skill-installer to install chat, map, data, investigate, plan, build,
explain, simple, and commit from the skills/ directory in
https://github.com/devhemmy/hemmy-skills into my personal skills folder.
```

You can also copy individual folders from `skills/` into your personal `~/.codex/skills/` directory. Keep any existing skills you want to preserve; do not overwrite them without reviewing the differences.

Each skill is a small `SKILL.md` file. Read it before installing. In Codex, type `$` followed by the skill name to invoke it.

These skills follow the current repository's guidance. They do not include a specific framework or company architecture.

## Related

[Ponytail](https://github.com/DietrichGebert/ponytail) is a separate project for choosing the smallest complete solution. It can complement this workflow and is not bundled here.

## License

[MIT](LICENSE).
