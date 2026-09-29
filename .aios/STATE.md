# STATE

**Updated:** 2026-09-29 12:54 America/New_York

## Goal

Build the Chat On Steroids fork into the AIOS execution/control layer, starting with the Phase 1 Core integration. Do not substitute stock-app installation/configuration for product implementation.

## Current Truth

- Canonical repository: `thecravenfoodie-rgb/chat-on-steroids`
- Canonical memory path: `.aios/`
- AIOS package version: `2026.09.22.5`
- Governing AIOS ref used for initialization: `6ca314c3897060b66223b51078a61322f69732e3`
- All 12 required `.aios/` records exist in live GitHub.
- Product package metadata identifies `chat-on-steroids` version `2.1.14`.
- Owner reversed the Sidecar branding decision on 2026-09-29. The visible product brand is **Chat On Steroids**. Published connector names are **Chat On Steroids Core**, **Chat On Steroids Desktop**, and **Chat On Steroids Plugins**.
- Compatibility-sensitive technical identities remain unchanged: repository/package slug `chat-on-steroids`, app id `com.chatonsteroids.app`, MCP server ids `chat-on-steroids-*`, browser wire id `chat-on-steroids`, existing storage/userData keys, and native/internal `cos` names.
- On 2026-09-24 the local `aios/phase-1-core-integration` worktree was documented as containing an uncommitted Sidecar branding migration across app/extension/connectors/docs/locales/packaging/release metadata. That migration was never committed, installed, or published.
- The required source cleanup is therefore local and selective: revert the Sidecar-only branding edits while preserving unrelated Phase 1 implementation work. Do not reset the whole worktree.
- Any update/release behavior changed solely for the Sidecar rename is part of that local cleanup and should return to its pre-brand-migration behavior.
- The existing public repository is intentionally reused as canonical rather than creating a duplicate. That visibility decision is settled unless new confidentiality risk appears.
- Repository memory is `CURRENT / READY` on `main:.aios/`.
- Provider/bootstrap UI state is not currently re-verified; provider verification is deferred maintenance and does not block source implementation.
- Required bootstrap contract remains `2026.09.22.5` for repository `thecravenfoodie-rgb/chat-on-steroids` / `.aios/` when that maintenance is resumed.
- Canonical memory branch: `main`.
- Product implementation branch: `aios/phase-1-core-integration`.
- Live GitHub shows that branch at preserved baseline commit `750fad9378a0cf9e37791916b11f7ed9add645dd`; inspect the local worktree and prior implementation handoff before assuming work has not begun.
- Current implementation intent is **build/modify the fork**, not download/install the upstream release.
- Phase 1 is Core-first: execution path, identity/ownership controls, execution receipts, worker handoff/resume, and lifecycle/control integration before broader capability expansion.
- Provider fresh-chat regression is deferred and non-blocking for product implementation. Keep its status truthful; do not mark it passed without evidence.

## Active Work

**Phase 1 — AIOS Core integration into the Chat On Steroids fork.**

The active implementation surface is the fork/source tree, not provider setup and not stock-app installation.

## Blockers

None for Phase 1 source implementation.

Provider-adapter/bootstrap regression remains deferred maintenance. It does not block coding, tests, branch work, or architecture implementation.

## Next Executable Action

Use Chat On Steroids Core against the local `aios/phase-1-core-integration` worktree. Inspect the current diff, then selectively revert every Sidecar visible-brand change across app/extension/connectors/docs/locales/packaging/release metadata and any Sidecar-only update/release changes. Preserve unrelated Phase 1 work and do not reset the whole worktree.

After the cleanup, verify the diff contains no unintended Sidecar branding, run `git diff --check`, then run the relevant rename-sensitive tests plus the broader verification/build needed for the touched surfaces. Reconcile the resulting local state back into `.aios/` only after that verification succeeds.

Phase 1 Core integration remains the active product-development track.
