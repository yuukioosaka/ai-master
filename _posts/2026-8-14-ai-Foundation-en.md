---
layout: default
title: AGENT Foundation (Basic Level)
lang: en
date: 2026-8-13 23:00:00 +0900
excerpt: AGENT foundation understanding
---
**AGENT Foundation Understanding**

**LLM Basics**
- [ ] Understands that an LLM is probabilistic token prediction and may structurally include hallucination
- [ ] Understands that training data has a cutoff date and may lack or misstate the latest information
- [ ] Knows the concept of tokens and context windows (input/output limits, cost-billing units)
- [ ] Understands that prompt writing (clear instructions, concrete examples, constraints) affects output quality
- [ ] Understands that models have strengths and weaknesses and are not universal (e.g., exact arithmetic, recent facts, long consistency)
- [ ] Understands that the same instruction can produce slightly different outputs each time (non-determinism)
- [ ] Knows that models come in multiple grades (speed/cost/accuracy tradeoffs) and can be selected per task

**Agent Basics**
- [ ] Understands the difference between chat (dialogue only) and agents (tool execution, autonomous loops)
- [ ] Knows that agents can use tools such as file read/write and bash command execution
- [ ] Knows that agents autonomously iterate plan, execute, verify
- [ ] Knows the existence and use of Plan Mode (a mode to confirm the approach before implementation)
- [ ] Understands the permission model (allow/deny/ask) as a mechanism to prevent runaway behavior
- [ ] Understands that memory may be lost when a session/context is cut off (need for summarization and handoff)
- [ ] Knows that a concept called compact (context compression) exists
- [ ] Knows that instruction files such as AGENT.md influence agent behavior
- [ ] Knows at least the names of Subagent/Skills/Hooks/MCP
- [ ] Knows there is a mode that answers based on tool-call results (web search, code execution, etc.)

**Risk Awareness**
- [ ] Knows there are copyright/licensing considerations for generated code
- [ ] Understands the risk that auto-executed commands may unintentionally perform destructive operations
- [ ] Understands the risk of using generated content in production/publication without verification

**Practical Application (Programming Work)**
- [ ] Can instruct the agent to perform a single clear task (function fix, bug fix, small feature addition)
- [ ] Can read and verify the generated diff to confirm it matches intent, then apply it
- [ ] Can have the agent run unit tests for the changed code and confirm pass/fail
- [ ] Can make the judgment not to use the agent's output (code, tests) in production without verification
- [ ] Can at least confirm after a fix that existing functionality still works (startup, main operations)
