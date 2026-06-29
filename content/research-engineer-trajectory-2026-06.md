+++
date = '2026-06-29'
draft = false
title = 'Research Engineer Trajectory'
+++

> Status: direction, not a plan  
> Horizon: ~6 months, with weekly check-ins against this note

---

## What this is

A reference document capturing a long conversation about how to spend the next ~6 months of personal study time. It is a living note, not a fixed plan. It will be revised as the work reveals what actually matters.

---

## Starting identity

I am becoming someone who understands modern LLMs and transformers across abstraction levels — from the math to the metal. The working title is **research engineer with inference engineer capabilities**, but the exact craft will emerge from the work. The trunk is transformers and inference. Branches may form later.

---

## Why now

- I miss the depth I had during my bachelor/master years.
- My recent production work has been broad and integration-heavy.
- I have flexible personal time at MVF and want to use it deliberately.
- I want to build public evidence of depth, not just consume content.

---

## Priority order

1. **Depth** — real understanding, from-scratch implementation, derivation.
2. **Feeling of understanding** — the satisfaction of owning a concept.
3. **Artifacts** — public code, notes, blog posts, experiments.
4. **Career positioning** — becoming credible for the roles I want.

This order protects against chasing hot topics or status.

---

## Structure: core + satellites + horizon

### Layer 1 — Core trunk (gets most time)

These are the starting focus. They are not separate; they connect.

- Transformer internals: attention, MLPs, normalization, positional encoding, training dynamics.
- LLM inference: autoregressive generation, KV-cache, sampling, quantization, batching, serving trade-offs.
- Efficient kernels: memory-aware algorithms, Triton, profiling.

### Layer 2 — Satellites (bounded)

One active at a time. Max ~20% of weekly study hours. Must produce a small artifact. Time-boxed. No implementation unless it graduates to a core slice.

- **Agents** — studied through the transformer/inference lens; connects to MVF work.
- **SOTA paper reading** — one paper at a time, one-page note, connects to current core.
- **TypeScript literacy** — enough to read Pi and similar agent-harness code; no porting projects.
- **Public writing / experiments** — distribution and documentation of core work.

### Layer 3 — Horizon (not now)

Interesting, but deferred. Write them down when they appear; do not start them.

- Robotics / embodied AI
- RL / world models as a primary pursuit
- Diffusion / flow models
- CUDA C++ / Tile-Lang / Rust deep dives
- Porting Pi to Python
- Standalone network engineering study

---

## Traversal method: thin vertical slices

Instead of broad courses, take one concept and move it down through abstraction levels:

1. Math / derivation
2. Algorithm / complexity
3. Code from scratch
4. Systems / profiling
5. Metal literacy (enough to understand compiler output and systems code)

A slice is thin if it has one core concept, one layer at each level, and one artifact. It explicitly does *not* include full models, production deployment, SOTA extensions, or multiple domains.

Example first slice: attention mechanism from scratch.

---

## Time and execution

### Weekly schedule (added to Google Calendar for 8 weeks, 2026-06-29 to 2026-08-23)

| Day | Work | Study block | Gym | Expected focused study |
|---|---|---|---|---|
| **Mon** | 7am–3pm (WFH) | 3–7pm | 7–8pm | ~2h |
| **Tue** | 7am–3pm (WFH) | 3–7pm | 7–8pm | ~2h |
| **Wed** | office | none | none | 0 (never-zero maintenance only) |
| **Thu** | office | none | none | 0 (never-zero maintenance only) |
| **Fri** | 7am–3pm (WFH) | 3–7pm | 7–8pm | ~2h |
| **Sat** | free | 10am–3pm | 8–9am | ~3–4h |
| **Sun** | free | 10am–3pm | 8–9am | ~3–4h |

**Total protected time**: ~12–18 hours per week. Realistic focused work: ~10–14 hours per week.

### How to use each block

**Mon/Tue/Fri 3–7pm "Core Study"**:
- 3:00–3:15pm: transition, close work, write today's goal
- 3:15–5:00pm: deep work (derive, implement, debug)
- 5:00–5:30pm: break
- 5:30–7:00pm: lighter work (reading, notes, Tau satellite)

**Sat/Sun 10am–3pm "Deep Study"**:
- 10:00–10:15am: review where you left off, set goal
- 10:15–12:30pm: deep work
- 12:30–1:00pm: break
- 1:00–3:00pm: deep work or writing

### Execution principles

- **Never-zero rule**: on the worst week, do at least one small thing related to the core trunk.
- **Review cadence**: check this note monthly. Adjust based on what is actually happening.
- **Rest is part of the plan**: Wed/Thu are intentionally light. One full day off per week.
- **Public output as accountability**: commit to one artifact per month to keep momentum visible.

---

## Public trajectory

The goal is to become publicly recognizable for a specific kind of work, by doing permissionless, rigorous work in the open. Inspirations: Will Brown, Jino Rohit, Antirez — not to copy their topics, but to copy the pattern of public depth.

Distribution mix (situation-based, not mandatory):
- **GitHub** — code, reproductions, experiments.
- **Blog** — milestone writeups, derivations, lessons learned.
- **X / LinkedIn** — small updates, observations, distribution of longer work.

The public output is an output of depth, not the driver of it.

---

## What was explicitly rejected

- A 6-month rigid curriculum.
- Daily LeetCode as a primary activity. LeetCode may be a maintenance habit later.
- Porting Pi to Python as a personal project.
- Co-authoring an academic paper as the main goal. Replaced with permissionless public experiments + writeups.
- Chasing every interesting domain. The three-layer model decides what is active and what waits.

---

## MVF relationship

MVF is the funding source and an application ground. Current work is building agents with the Anthropic SDK. I want to move toward more provider-agnostic, cost-aware, possibly self-hosted inference. That connects naturally to the inference-study trunk. TypeScript literacy is allowed as a small satellite because Pi is well-designed and provider-agnostic, but no porting project.

---

## Open questions to revisit

- Which part of the transformer/inference stack lights me up most as I go deeper?
- Do I want to stay at MVF long-term, or is this a stepping stone?
- What does my first public artifact look like, and when?
- How much compute do I realistically have, and how does that constrain experiments?

---

## Last updated

2026-06-29
