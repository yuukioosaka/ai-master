---
layout: default
title: AGENT Practitioner (Intermediate Level)
lang: en
date: 2026-8-13 22:00:00 +0900
excerpt: AGENT intermediate understanding
---
**AGENT Practitioner Understanding**

**Architecture / Execution Model**
- [ ] Understands the mechanism of Subagent role separation and parallel execution
- [ ] Can design which tasks to delegate to a Subagent with an isolated context and receive only summaries
- [ ] Understands the tradeoff of context window usage and can pass only needed information
- [ ] Can judge the timing of compact and create handoff documents across sessions
- [ ] Understands tool use planning, model selection, and cost tradeoffs
- [ ] Can design information handoff between agents to prevent duplicate work

**Structured Delegation**
- [ ] Can consistently delegate large-scale codebase investigation, bug reproduction, and fix proposals
- [ ] Can delegate design document reviews (consistency and non-functional requirement perspectives) and prioritize findings
- [ ] Can ask "why was it not detected" and derive system improvements (new tests, new rules) rather than one-off fixes
- [ ] Can write effective instructions (CLAUDE.md/AGENTS.md) and structure a consistent delegation workflow

**Practical Application (Programming Work)**
- [ ] Can consistently delegate investigation and analysis of an existing codebase (impact scope, root-cause identification, structural understanding) to the agent
- [ ] Can hand off a loop that runs tests, build, and lint in sequence, and let the agent iteratively fix failures
- [ ] Can delegate refactoring and feature additions and verify there is no regression
- [ ] Can ask the agent to back up its presented findings or fixes with evidence (logs, tests, code) and judge their validity
