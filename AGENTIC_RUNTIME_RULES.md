# Agentic Runtime Rules

These values are expected to be easy to edit without touching the main instruction file.

## Escalation thresholds
- `max_execution_cycles_before_escalation`: 25

## Notes
- If execution or verification loops reach this threshold without success, escalate according to the main instructions.
- Adjust this file when you want to change operational limits without rewriting role definitions.
