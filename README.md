# reffi-agentic-scrum-squad-v1

OpenClaw-ready boilerplate for running an agentic scrum squad.

## Includes
- role instructions for PO, Scrum Master, Story Maker, Task Master, Implementer, Verifier, and Guard Master
- staged handoff lifecycle written in pseudocode
- runtime rules for escalation thresholds
- workspace guidance for file-based scrum artifacts under `.agile/`

## Key files
- `AGENTIC_INSTRUCTIONS.md` — main squad rules, roles, and staged pseudocode
- `AGENTIC_RUNTIME_RULES.md` — editable operational thresholds
- `AGENTS.md` / `SOUL.md` / `USER.md` — workspace and persona scaffolding
- `instructions/` — channel-oriented instruction bundle

## Notes
- backlog and sprint artifacts are intended to live under `.agile/`
- session memory and local runtime state are excluded from version control
- this repo is meant to be copied/adapted into new agent workspaces or new project-bound agents
