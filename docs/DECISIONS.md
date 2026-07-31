# Decisions

This file records accepted long-lived decisions for Engineering-Lab.

## 2026-07-31 — GitHub is the source of truth

**Status:** Accepted

Engineering-Lab is maintained in `vladimir-sulima/Engineering-Lab`. ChatGPT, Codex, and other conversations are interfaces, not authoritative storage.

A durable change is incomplete until it is committed to GitHub or published through the required pull-request flow.

## 2026-07-31 — Mandatory repository synchronization

**Status:** Accepted

Every assistant session working on an existing Engineering-Lab workstream must read `AGENTS.md`, `PROJECT_STATE.md`, the AI operating model, decisions, knowledge map, and affected records before answering or changing anything.

The user should not have to repeat information already stored in the repository.

## 2026-07-31 — Routine updates may go directly to main

**Status:** Accepted

Small inventory additions, corrections, project-state updates, lesson notes, and documentation clarifications may be committed directly to `main`.

Structural changes, bulk moves, deletions, and source-of-truth migrations require explicit approval and normally use a branch and pull request.

## 2026-07-31 — Preserve uncertainty

**Status:** Accepted

Unknown brands, models, quantities, prices, measurements, dates, capabilities, and storage locations must be recorded as `unknown` or `needs confirmation`. They must not be inferred merely from appearance or memory.

## 2026-07-31 — Platform-specific organization

**Status:** Accepted

Lessons, projects, code, and reusable assets for different platforms should live in platform-specific folders where practical.

Lessons and projects should be numbered, dated, understandable, and reproducible.

## 2026-07-31 — Documentation is part of the work

**Status:** Accepted

Inventory, project status, code, wiring, drawings, safety notes, and lessons learned should be updated as part of normal engineering work rather than postponed indefinitely.

## 2026-07-31 — Family lab participants

**Status:** Accepted

The core participants are Vova, Alexandr, and Daria. Documentation should remain family-friendly while preserving correct English technical terminology where useful.
