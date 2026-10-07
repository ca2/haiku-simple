# CA2 Haiku Development Rules

## Primary Rule

**Do not overengineer. Ensure core functionality works, then move on.**

For each task:

- Implement the simplest solution that satisfies the requested functionality.
- Prioritize working behavior over polish, abstraction, optimization, or architectural improvements.
- Do not expand the scope beyond the requested task.
- Do not refactor unrelated code unless it is required for the task to work.
- Do not add abstractions, helper systems, fallback layers, or extra features unless they are necessary.
- Do not spend time polishing code that already works sufficiently for the current stage.
- Test the fundamental behavior needed for the task.
- Once the required functionality works, stop and move to the next task.

## CA2 on Haiku

The current goal is to get CA2 framework functionality working correctly on Haiku OS.

Compatibility and basic functionality come first.

Prefer:

**working → verified → move on**

Not:

**working → redesign → refactor → optimize → polish → expand scope**

## Definition of Done

A task is done when:

1. The requested functionality is implemented.
2. It builds or runs as expected.
3. The core behavior has been verified.
4. No known issue prevents the requested functionality from working.

Anything beyond this should be handled as a separate task.