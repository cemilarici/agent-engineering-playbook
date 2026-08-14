# Reusable Research Prompts

## Repository orientation
Analyze this repository as a senior agent-systems engineer. Identify the problem it solves, core abstractions, runtime model, major components, execution path, extension points, persistence model, operational assumptions and explicit non-goals. Separate evidence from inference.

## Architecture review
Trace one representative request/job from entry point to completion. Map control flow, state transitions, model calls, tools, persistence, queues/events, retries, HITL, observability and failure handling. Identify tight coupling and replaceable boundaries.

## Issue mining
Find high-signal Issues that reveal production pain, architectural limitations, recurring bugs, scaling problems, security concerns or developer-experience failures. Cluster by root cause rather than by issue title. Extract lessons, not anecdotes.

## PR mining
Find consequential PRs that changed architecture, reliability, persistence, concurrency, security, observability or APIs. Explain the problem before the PR, the chosen design, rejected/implicit alternatives and migration consequences.

## Pattern extraction
From the collected evidence, propose reusable engineering patterns. For each: context, problem, forces, solution, consequences, failure modes, when to use, when not to use, evidence, and Agent OS relevance. Reject patterns that are merely framework-specific syntax.

## Technology decision
Answer: In which concrete situations would I choose this technology? In which situations would I reject it? What operational burden does it introduce? What would replace it? What lock-in exists? What must be benchmarked before adoption?

## Business translation
Translate technical capabilities into customer problems without inventing demand. Identify plausible enterprise use cases, integration burden, deployment constraints, governance requirements, recurring operational work, and where a repeatable service/product pattern may exist.

## Weekly synthesis
Summarize what changed in my mental model this week. List the strongest evidence, patterns accepted/rejected, unresolved questions, one implementation experiment, and implications for the Agent OS reference architecture.