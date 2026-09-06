---
name: to-spec
description: Turn the current conversation and codebase understanding into a technical spec.
disable-model-invocation: true
---

Synthesize what has already been discussed; do not interview the user. Explore the repository, use its domain glossary and respect relevant ADRs. Identify the highest useful testing seams and confirm them with the user before writing the spec. Produce a spec covering Problem Statement, Solution, User Stories, Implementation Decisions, Testing Decisions, Out of Scope, and Further Notes. Avoid brittle file paths and implementation snippets unless a precise prototype shape is itself the decision.
