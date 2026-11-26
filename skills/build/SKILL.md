---
name: build
description: Implement only the next phase of an existing plan, run relevant checks, and stop for review without committing.
---

# Build

Use the existing plan and identify its next unfinished phase. If no plan is available, ask which phase to implement rather than inventing one.

Implement that phase only. Follow existing patterns and run the relevant checks. Keep the solution simple and readable, reuse existing code, and avoid unrelated changes or extra abstractions.

Follow the current repo's architecture guidelines. Keep feature and state ownership clear, reuse shared logic, and give each part a clear responsibility. Do not add layers a small change does not need.

Briefly state what changed and which checks passed, failed, or could not run. Then stop so the user can review it. Do not commit or start the next phase. If the plan needs to change, explain the issue before expanding the scope.
