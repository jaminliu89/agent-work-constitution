# Project Agent Instructions

Project: [verified project name]

Before making project-state changes, read this file and `MEMORY.md`. If a required file is missing, create it from an available approved template or a minimal safe structure. No other project write operations until both exist.

## User outcome
[Describe actual user task and success criterion]

## Boundaries
- Scope: [authorized files/functions]
- Invariants: [interfaces/decisions/data contracts that must not change]
- Out of scope: [explicit exclusions]
- Permissions: [external publication, destructive operations, secrets, money]

## Engineering discipline
Think before coding. Prefer the smallest sufficient change. Do not edit unrelated code. Define tests/acceptance evidence and run them before claiming results.

## Project commands
- Test: [verified command, if any]
- Build: [verified command, if any]

## Durable decisions
Record meaningful architecture choices, failures and key corrections in `MEMORY.md`; never store credential values or duplicate code-derived facts.
