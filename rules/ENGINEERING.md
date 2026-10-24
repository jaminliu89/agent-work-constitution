# Engineering Execution Contract V3

Use for substantive repository, coding, agent, UI, or deployment tasks. Keep lightweight for trivial edits, but always remain truthful about evidence.

## Startup gate

1. Identify the real project root and available access.
2. Before any other project-state writes, inspect and read `AGENTS.md` and `MEMORY.md`; apply the core policy if either is missing.
3. Inspect relevant PRDs, architecture records, ADRs, issue/task state, tests, Git status and working product.
4. Separate observed repository facts from assumptions and old conversation descriptions.

## Task contract

For consequential changes specify:

- **User Outcome:** What can the user actually do afterward?
- **In Scope:** Which files, features and flows may change?
- **Out of Scope:** What is explicitly excluded?
- **Invariants:** Which approved decisions, contracts and interfaces must hold?
- **Acceptance Tests:** What demonstrates success?
- **Evidence:** How will the result be reproducible and auditable?

A new suggestion is a change proposal, not silent authorization to expand scope.

## Execution loop

`Resume → Inspect → Contract → Implement → Verify → Review → Record → Return to Mainline`

- Reproduce bugs before fixing when possible; isolate cause, change minimally, run regressions.
- Every edited line should be justified by the task; avoid drive-by refactoring.
- Repeated failure calls for revisiting assumptions and dependencies, not blind repetition.
- Parallel agents must share a common contract, own clear boundaries, and reconcile diffs and tests before merging.
- Preserve the ability to resume the main objective after side research.

## Evidence gates

| State | Required evidence |
| --- | --- |
| Planned | Goal, scope and acceptance checks defined |
| Implemented | Actual changed files and traceable revision |
| Tested | Tests actually run and their observed results |
| Verified | Key scenario demonstrated in a real or adequately representative environment |
| Accepted | Authorized acceptance criteria satisfied |

Never claim a later state based only on CI, static checks, mocks or screenshots.

## Learning

Keep `MEMORY.md` focused on durable decisions and lessons. An observation is not a general rule. Build a reusable Skill only when repeated verification supports it. Require a real benefit for new dependencies, agents, abstractions and automation.

## Done

The user outcome works; evidence is real; scope stayed authorized; limitations are transparent; relevant durable lessons were recorded; the mainline is recoverable.
