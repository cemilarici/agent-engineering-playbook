# CLAUDE.md

Read `AGENT.md`, `LEARNING_RULES.md`, and `OUTPUT_STANDARDS.md` before research or edits.

## Project context
This is a practical research and learning repository for extracting reusable agent-engineering patterns from ten selected open-source projects. It is not a generic notes repository and not a framework popularity ranking.

## Working method
For each project, use the relevant templates and preserve evidence links/references. Distinguish:
- observed project behavior
- maintainer-stated design intent
- our engineering interpretation
- Agent OS implications
- business implications

## Pattern taxonomy
Store durable patterns under `patterns/` using these categories: orchestration, state, memory, tools, observability, evaluation, security, deployment. Add a new category only when existing categories are structurally inadequate.

## Change discipline
Do not silently rewrite previous conclusions when new evidence appears. Update the conclusion and record why it changed. Prefer small, reviewable documentation changes.