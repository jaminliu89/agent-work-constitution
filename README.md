# Agent Work Constitution

**Less assumption. Less complexity. More verified outcomes.**

[简体中文](README.zh-CN.md) · [Core guidelines](rules/CONSTITUTION.md) · [Engineering contract](rules/ENGINEERING.md)

A small, open-source set of **vendor-neutral instructions for AI agents**. It combines the four well-known Karpathy-inspired coding disciplines with lessons about memory, project constraints, decision authorization, truthful verification, and reusable learning.

> This is an independent community work. It is **not** an official project or endorsement by Andrej Karpathy, Anthropic, Claude, OpenAI, or any other vendor. The text here is newly written; the reference project is credited below.

## Why this exists

Coding standards alone cannot prevent an agent from following the wrong objective, inventing past project state, overbuilding a product, repeatedly abandoning the main task, or reporting simulated results as real success. These guidelines aim to address those failure modes without turning simple tasks into bureaucratic rituals.

## Start in two minutes

**For a personal AI assistant:** Read [the core constitution](rules/CONSTITUTION.md) and use the relevant clauses as your custom instructions. For a short version, use [the compact profile](profiles/COMPACT.md).

**For an existing project:** Keep your project's existing instructions. Add a pointer to the constitution or merge only the relevant clauses into `AGENTS.md` / `CLAUDE.md`. Do **not** overwrite existing project rules. Use [the engineering contract](rules/ENGINEERING.md) for non-trivial development work.

**For a new project:** Start from [AGENTS template](templates/AGENTS.md), [MEMORY template](templates/MEMORY.md), and [task contract](templates/TASK_CONTRACT.md). Fill in real project facts before making changes. These are examples, not a required framework.

### Files

| File | Purpose |
| --- | --- |
| [`rules/CONSTITUTION.md`](rules/CONSTITUTION.md) / [中文](rules/CONSTITUTION.zh-CN.md) | Universal assistant behavior |
| [`rules/ENGINEERING.md`](rules/ENGINEERING.md) / [中文](rules/ENGINEERING.zh-CN.md) | Engineering execution, quality gates, evidence |
| [`profiles/COMPACT.md`](profiles/COMPACT.md) / [中文](profiles/COMPACT.zh-CN.md) | Short copy-and-use personal instructions |
| [`templates/AGENTS.md`](templates/AGENTS.md) | Starter repository rules |
| [`templates/MEMORY.md`](templates/MEMORY.md) | Curated long-term project decisions |
| [`templates/TASK_CONTRACT.md`](templates/TASK_CONTRACT.md) | Scope and acceptance criteria |
| [`CLAUDE.md`](CLAUDE.md) | Repository-specific Claude Code entrypoint |
| [`AGENTS.md`](AGENTS.md) | Repository-specific agent contribution rules |

## Principles

1. **Think before coding** — name consequential assumptions and trade-offs.
2. **Simplicity first** — make the smallest sufficient solution.
3. **Surgical changes** — edit only what the task justifies.
4. **Goal-driven execution** — define success, then verify it.
5. **History and constraints first** — recover relevant prior decisions and real repository state.
6. **Decision discipline** — a suggestion is not an authorized change request.
7. **Truthful status** — implemented, tested, verified, and accepted are different states.
8. **Mainline discipline** — follow the agreed objective instead of drifting into adjacent work.
9. **Compounding learning** — turn confirmed lessons into reusable knowledge, not unnecessary integrations.

## Important boundaries

- A workspace-file setup gate applies **only when editing an accessible project workspace**. It is not a prerequisite for normal questions or prose drafting.
- Check for `AGENTS.md` and `MEMORY.md` when the project requires them. If templates cannot be accessed, make the smallest sensible starting files; do not pretend templates were copied.
- Repetition triggers an **automation evaluation**, not a mandatory abstraction or new system.
- Prefer existing project decisions and evidence, but disclose when historical memory is incomplete or contradicted by the repository.
- External publishing, irreversible edits, secret handling and financial actions need appropriate authorization.

## How to assess improvements

Evaluate with real tasks, not prompt aesthetics: unauthorized scope changes, end-to-end task completion, regressions, unnecessary diff size, false claims of verification, and ability to resume the mainline. The [task contract template](templates/TASK_CONTRACT.md) captures the basic evidence.

## Inspiration and attribution

Inspired by the **four conceptual principles** collected in [Karpathy-Inspired Claude Code Guidelines](https://github.com/multica-ai/andrej-karpathy-skills). Those principles are presented there as a community interpretation of Andrej Karpathy's observations, not as his official authored instructions. This repository extends the ideas independently; it is not a fork or verbatim copy.

## Contributing and license

See [CONTRIBUTING.md](CONTRIBUTING.md). Distributed under the [MIT License](LICENSE).
