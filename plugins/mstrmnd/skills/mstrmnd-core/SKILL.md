---
name: mstrmnd-core
description: Design and extend mstrmnd as a portable intelligence layer for agentic systems with explicit context, memory, orchestration, policy, and evaluation boundaries.
---

# mstrmnd core

## Purpose

Use this skill when defining or extending the intelligence layer that sits between product vision and day-to-day execution.

## Operating loop

1. Assemble scoped context.
2. Retrieve and rank relevant memory.
3. Form a plan tied to goals and constraints.
4. Orchestrate the right agents, skills, tools, and connectors.
5. Execute with explicit permissions and runtime boundaries.
6. Evaluate outcomes, cost, and quality.
7. Learn from results and feed them back into future runs.

## Required design rules

1. Keep models replaceable and provider-agnostic.
2. Treat context, memory, orchestration, tools, and policy as separate concerns.
3. Require explicit identity and scope for memory, credentials, artifacts, and actions.
4. Deny cross-scope access by default.
5. Add approval gates for destructive, financial, publishing, or externally visible actions.
6. Prefer durable workflows and auditable execution history over hidden automation.
7. Measure business outcomes and evaluation quality, not just activity volume.

## Expected outputs

- a clearly scoped runtime design
- required agents, tools, and connectors
- policy and approval boundaries
- evaluation and observability requirements
- follow-up implementation steps grounded in the mstrmnd operating loop
