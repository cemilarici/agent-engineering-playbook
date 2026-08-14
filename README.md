# Agent Engineering Playbook

A practical, evidence-driven learning repository for studying production-grade agent systems through real open-source projects.

## Purpose

This repository is not a framework tutorial collection. Its purpose is to extract reusable engineering knowledge from mature agent projects: architecture decisions, failure modes, operational patterns, business implications, and technology trade-offs.

The central question is:

> What engineering knowledge from this project can be reused in the next agent system?

## Core learning loop

Each project is studied with the same loop:

1. Read the README, architecture docs, examples, and recent releases.
2. Run at least one representative demo where practical.
3. Map the architecture: runtime, state, memory, tools, orchestration, persistence, observability, security, deployment.
4. Study high-signal Issues, Pull Requests, Discussions, and release notes.
5. Extract reusable patterns and anti-patterns.
6. Record technology-selection decisions and trade-offs.
7. Translate findings into implications for an enterprise Agent OS / AgentMine-style platform.
8. Produce a weekly review and concrete next actions.

## Ten core repositories

| Week | Project | Primary learning focus |
|---|---|---|
| 01 | LangGraph | Stateful orchestration, graphs, persistence, HITL |
| 02 | Agno | Agent runtime, teams, memory, production services |
| 03 | OpenHands | Autonomous coding agents, sandboxing, action loops |
| 04 | Langfuse | Tracing, evaluation, observability, feedback |
| 05 | Browser Use | Browser agents, tool reliability, web execution |
| 06 | LiveKit Agents | Realtime and voice-agent runtime |
| 07 | Pipecat | Realtime multimodal pipelines and voice orchestration |
| 08 | LlamaIndex | Knowledge, retrieval, data/agent integration |
| 09 | n8n | Workflow orchestration and integration patterns |
| 10 | Mastra | TypeScript agent/workflow runtime and production patterns |
| 11 | Cross-project comparison | Technology and architecture comparison |
| 12 | Reference architecture | Synthesize an Agent OS reference architecture |

## Required output per repository

A repository is not considered studied until it produces:

- Repository review
- Architecture review
- At least one demo report where practical
- High-signal Issue/PR findings
- Reusable patterns and anti-patterns
- Decision record: when to use / when not to use
- Business and enterprise implications
- Agent OS / AgentMine implications
- Weekly review

## Repository structure

```text
.
├── README.md
├── ROADMAP.md
├── CURRICULUM.md
├── RESOURCES.md
├── AGENT.md
├── CLAUDE.md
├── PROMPTS.md
├── AI_GUIDELINES.md
├── LEARNING_RULES.md
├── OUTPUT_STANDARDS.md
├── templates/
├── repositories/
├── patterns/
├── demos/
├── business-patterns/
└── weekly/
```

## Definition of Done

A project review is complete only when the documentation has been inspected, its architecture can be explained independently, at least one meaningful execution path has been traced or run, high-signal engineering discussions have been reviewed, reusable patterns have been extracted, and a technology decision has been recorded.

## Learning principle

Do not optimize for the number of frameworks learned. Optimize for the number of durable engineering decisions that can be made correctly without framework-specific guidance.
