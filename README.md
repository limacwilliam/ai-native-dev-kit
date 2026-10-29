# AI-Native Dev Kit

A practical kit for spec-driven, AI-assisted software delivery. It provides reusable artifacts, not a substitute for human ownership.

```mermaid
flowchart LR
  PRD[PRD] --> Plan[Plan]
  Plan --> Build[Implementation]
  Build --> Verify[Tests and review]
  Verify --> Runbook[Runbook]
  Runbook --> Release[Release]
```

## Use it

1. Copy the relevant template to your project.
2. Assign a human owner for every decision and acceptance criterion.
3. Use the review prompts to challenge generated changes.
4. Retain a runbook before release.

See [workflow.md](workflow.md) and the fictional [example](examples/appointment-reminder/).

MIT License © William Lima
