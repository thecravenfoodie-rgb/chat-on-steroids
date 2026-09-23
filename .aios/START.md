# Project START — GitHub-Native AI Project OS

**Project:** AIOS Execution Layer • Chat On Steroids • Sept 22

## Turn Admission Gate

Classify the turn before loading project state:

- `FAST_CHAT` — answer directly; no project/package/memory preflight.
- `PROJECT_READ` — read only the minimum canonical project record(s) needed.
- `PROJECT_WORK` — run required project-memory/package preflight before material side effects or authoritative state-dependent execution.
- `MAINTENANCE` — package/memory/audit maintenance only when explicitly requested or required by admitted work.

## Canonical Project Home

Repository: `thecravenfoodie-rgb/chat-on-steroids`  
Branch: `main`  
Canonical project-memory path: `.aios/`

GitHub is the canonical persistent project-memory layer. Google Drive and ChatGPT Project Sources are non-authoritative unless this project explicitly records a separate source role.

## Current Execution Directive

- **Product objective:** build the Chat On Steroids fork into the AIOS execution/control layer.
- **Active phase:** Phase 1 Core integration.
- **Canonical memory branch:** `main`; authoritative project memory is `main:.aios/`.
- **Active implementation branch:** `aios/phase-1-core-integration`.
- Product/source commits belong on the implementation branch unless a later project decision changes that branch.
- AIOS memory reconciliation belongs on `main:.aios/`; do not treat a feature branch's missing/stale `.aios/` copy as canonical.
- Installing/downloading the unmodified upstream CoS release is **not** the next project step and is not a substitute for implementation.
- Provider/bootstrap fresh-chat verification is deferred maintenance and **does not block Phase 1 source work**.
- The existing public repository is intentionally canonical. Do not reopen repository visibility without new confidentiality evidence.

## PROJECT_WORK / MAINTENANCE Preflight

1. Read `.aios/MEMORY_SYNC.md`.
2. Read `.aios/PROJECT.md`.
3. Read `.aios/STATE.md`.
4. Read `.aios/PACKAGE_SYNC.md` and canonical `thecravenfoodie-rgb/ai-project-os/defaults/DEFAULTS_MANIFEST.md` only when package compatibility can materially affect the work.
5. Load decisions, sources, changelog, completed work, research, ideas, checkpoints, governance, SOPs, or snippets only when relevant.

## Authority

- Project-specific durable truth: this repository's `.aios/`.
- Reusable AIOS governance/SOPs/snippets/defaults: `thecravenfoodie-rgb/ai-project-os`.
- Operational/task truth: Notion where explicitly assigned.
- Executable software truth: the normal repository source tree.
- Chat history, saved memory, uploads, Project Sources, Drive copies, and caches do not outrank live canonical GitHub state.

## Writeback

Follow canonical `SOPs/PROJECT_MEMORY_SYNC.md`. Routine persistence must not block an otherwise-ready answer. Use durable write-ahead only when correctness, safety, authorization, material external side effects, handoff/interruption safety, or replay protection requires it.

## Deferred Provider Maintenance

Provider/bootstrap verification remains pending and must stay truthful, but it is not part of the active Phase 1 implementation path. Run it only when explicitly resumed as maintenance. Do not let it displace product work.
