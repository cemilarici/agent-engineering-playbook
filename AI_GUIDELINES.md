# AI Research Guidelines

AI is an accelerator and critic, not the source of truth.

## Use AI for
- repository orientation and code-path tracing
- clustering Issues/PRs by root cause
- generating hypotheses to verify
- comparing architecture alternatives
- extracting candidate patterns
- challenging conclusions
- converting findings into structured templates

## Verification
Important claims must be verified against primary project evidence. If evidence is unavailable, mark the statement as a hypothesis.

## Required modes
For meaningful reviews, examine the system through: architecture, implementation, production operations, security, performance/cost, enterprise adoption, business translation, and Agent OS integration.

## Anti-bias checks
Before finalizing a recommendation ask:
- Am I confusing popularity with quality?
- Am I repeating documentation marketing language?
- Did I inspect failure reports as well as happy-path examples?
- Did I consider operational ownership?
- Did I state when this technology should not be used?
- Is the extracted pattern actually portable?