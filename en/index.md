---
layout: default
title: AI MASTER
lang: en
permalink: /en/
---
# What is the AI MASTER Standard?

## Definition

The **AI MASTER Standard** is an in-house reskilling / HR evaluation framework that measures how practically a developer can use AI coding agents (such as Claude Code) across **four levels: Basic, Practitioner, Expert, and Steward**.

Rather than merely asking "have you used an AI tool?", it gauges **the complexity of work you can delegate, the ability to design autonomy, and the capacity to scale it across the organization** in stages.

---

## Why it is needed

- As generative AI shifts from an "efficiency tool" to "foundational infrastructure," the AI industry in 2026 has moved beyond one-off productivity tools and is becoming infrastructure embedded directly into business structures.
- Meanwhile, the in-house "level of AI adoption" varies greatly between individuals, and without an evaluation standard, it is difficult to plan training.
- Existing AI talent standards (such as METI's Digital Skills Standard) stay at generic DX person categories and do not reach the **practical granularity of agent operations** (Subagent design, parallel execution, CLAUDE.md maintenance, etc.).

## What is new (differences from existing models)

The AI MASTER Standard integrates two axes.

1. **Personal skill axis** (Basic to Steward) — "what can this person delegate to an agent"
2. **Organizational maturity axis**, inspired by **[ACMM](https://arxiv.org/abs/2604.093889) (AI Codebase Maturity Model)** — how far the infrastructure around the codebase (instruction files, tests, metrics, feedback loops) has been built out.

Most existing maturity models focus on "how much AI can replace humans (autonomy)". ACMM differs by defining maturity through feedback-loop structures — whether the concrete mechanisms enabling the next stage (tests, acceptance rates, monitoring, self-adjustment settings) exist — rather than autonomy itself. The AI MASTER Standard applies this thinking to individual evaluation, distinguishing "people who use AI well" from "people who can mature the organization's mechanisms."

## The four levels at a glance

| Level | In one phrase |
|---|---|
| Basic | Can delegate one task to AI and verify the result |
| Practitioner | Can delegate research and maintenance, and ask questions that lead to system improvement |
| Expert | Can build foundations (CLAUDE.md/Skills/Hooks) and design parallelism and automation |
| Steward | Can oversee organizational-wide AI operations and design governance |

## Expected benefits

- Training plans become concrete around "what one must be able to do, and to what degree."
- AI adoption can be objectively incorporated into hiring, placement, and evaluation.
- Like the NTT Data four-level generative AI certification or IBM digital badges, companies that combine measurement and evaluation can gain an advantage in productivity and talent acquisition.

---

## Knowledge Areas
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.lang == 'en' %}
      <li>
        <a href="{{ post.url | relative_url }}">
          <strong>{{ post.title }}</strong>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
---

## The AI MASTER Standard (4 levels)
### Overview (one-page summary)

| Level | Competency asked | ACMM transition | Human role |
|---|---|---|---|
| Basic | Delegation & verification | Stays at L1 | Executor |
| Practitioner | Research & context design | L1→L2 | Rule-writer |
| Expert | Foundation building, parallelism, measurement | L2→L3→L4 | Analyst→Governor |
| Steward | Governance & organizational design | L4→L5 | Strategist |

The levels reflect individual operational skill, while the transition trigger corresponds to ACMM organizational maturity, distinguishing "people who use AI well" from "people who mature an organization."

---
