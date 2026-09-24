# STATE

**Updated:** 2026-09-24 08:17 America/New_York

## Goal

Build the Chat On Steroids fork into the AIOS execution/control layer, starting with the Phase 1 Core integration. Do not substitute stock-app installation/configuration for product implementation.

## Current Truth

- Canonical repository: `thecravenfoodie-rgb/chat-on-steroids`
- Canonical memory path: `.aios/`
- AIOS package version: `2026.09.22.5`
- Governing AIOS ref used for initialization: `6ca314c3897060b66223b51078a61322f69732e3`
- All 12 required `.aios/` records exist in live GitHub.
- Product package metadata identifies `chat-on-steroids` version `2.1.14`.
- Owner-selected visible product brand: **Sidecar**. Published connector names are **Sidecar Core**, **Sidecar Desktop**, and **Sidecar Plugins**.
- Compatibility-sensitive technical identities remain unchanged by design: repository/package slug `chat-on-steroids`, app id `com.chatonsteroids.app`, MCP server ids `chat-on-steroids-*`, browser wire id `chat-on-steroids`, existing storage/userData keys, and native/internal `cos` names.
- The local `aios/phase-1-core-integration` worktree contains the Sidecar branding migration across app/extension/connectors/docs/locales/packaging/release metadata. Previous connector display names remain accepted as transitional read compatibility for existing conversations.
- Update/release lookup now targets the canonical fork `thecravenfoodie-rgb/chat-on-steroids`; no Sidecar binary release exists in the fork yet, and a missing latest release is treated as "no update" rather than falling back to upstream.
- Branding migration validation passed: `npm run verify` completed with 5,772 tests passed and 129 skipped across both phases, and `npm run build` succeeded.
- The Sidecar source migration is not yet committed, installed, or published; the currently running connector may therefore continue to show its previous installed display name until a Sidecar build is run and the connector is refreshed/recreated.
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

The Sidecar branding migration is prepared and fully validated in the local `aios/phase-1-core-integration` worktree. Review/commit that implementation when the owner wants it made durable on the product branch; do not publish or install merely to complete the source-editing task.

When runtime verification of the new visible name is desired, run/install the modified Sidecar build and refresh or recreate the ChatGPT connectors so their provider-visible names become Sidecar Core/Desktop/Plugins. Preserve the compatibility identities listed above.

Phase 1 Core integration remains the active product-development track after this branding checkpoint.
