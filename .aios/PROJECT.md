# PROJECT

**Project name:** AIOS Execution Layer • Chat On Steroids • Sept 22  
**Status:** Active  
**Owner:** project owner  
**Canonical repository:** thecravenfoodie-rgb/chat-on-steroids  
**Canonical memory path:** `.aios/`  
**Project category:** App

## Purpose

Build and evolve the owner's Chat On Steroids fork into the **AIOS execution/control layer**. Chat On Steroids is the runtime foundation to adapt and extend; installing or configuring the unmodified stock app is not the project objective.

The target architecture keeps AI Project OS / Mission Control as the authority layer while Chat On Steroids supplies the local execution runtime: approved-file access, terminal/Git/test execution, worker/session continuity, and other bounded execution capabilities.

## Scope

- **Current phase:** Phase 1 Core integration on branch `aios/phase-1-core-integration`.
- Phase 1 focuses on the Core execution path and AIOS control contracts before broader Desktop/Plugins expansion.
- Preserve useful upstream CoS behavior while adding AIOS-specific execution receipts, project identity protection, worker handoff/resume behavior, and lifecycle/control-plane hooks required by the Phase 1 design.
- Canonical AI-assisted project memory lives under `.aios/`.
- Executable/product source remains outside `.aios/` in this repository.
- Stock CoS installation/setup is not a substitute for implementing the fork.

## Architecture / Authority

- `thecravenfoodie-rgb/chat-on-steroids` = canonical project repository.
- `.aios/` = durable project memory.
- Normal source tree = executable/product truth.
- `thecravenfoodie-rgb/ai-project-os` = canonical reusable AIOS governance/defaults.
- Notion is authoritative only for explicitly assigned operational surfaces.
- Chat history, uploads, Project Sources, saved memory, and Drive copies do not outrank live canonical GitHub state.
- The verified existing repository is reused; no duplicate repository is created.

## Repository Identity

- Branch: `main`
- Product package: `chat-on-steroids`
- Product version observed at initialization: `2.1.14`
- Repository visibility: public — intentionally accepted as the canonical existing repository. Public visibility is not an identity failure and must not be reopened solely because new dedicated AIOS repositories default to private.
- Public `.aios/` exposure: reviewed for this package update; current project-memory records contain project metadata/governance state, not secrets or private credentials. Reassess only if future admitted memory would expose confidential material.
- AIOS package version: `2026.09.22.5`

## Definition of Done

Phase work is complete only when the intended AIOS execution-layer behavior is implemented in the fork, tests/verification appropriate to the changed surface pass, relevant `.aios/` memory is reconciled when durable truth changes, and unfinished work is explicitly recorded.

Downloading or installing the upstream/stock Chat On Steroids release does not satisfy this project's implementation Definition of Done.
