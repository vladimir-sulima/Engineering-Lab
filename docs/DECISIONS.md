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

## 2026-08-02 — Aquarium cave uses replaceable standardized modules

**Status:** Accepted

The aquarium cave project will use interchangeable rooms, passages, junctions, vertical entrances, and end caps rather than one permanent monolithic facade.

Modules will share a standardized passage connection so parts can be replaced or rearranged when the aquarium is dismantled for periodic cleaning. Viewing rooms will sit along the front glass, top entrances will use raised rims to limit substrate intrusion, and the baseline visual style will be a natural textured cave.

Exact dimensions, connector geometry, material, coating, and circulation method remain open until measurement and prototype testing.

## 2026-08-03 — Engineering Lab uses four parallel learning tracks

**Status:** Accepted

The family program develops Electronics, Software, Fabrication, and Engineering Thinking in parallel. Arduino is the current entry platform, not the final scope of the laboratory.

The target cadence is approximately three sessions per week, with four sessions possible during school breaks. Repetition, testing, fabrication, and documentation count as learning sessions and should not be displaced by constant introduction of new topics.

Canonical concept: `docs/ENGINEERING_LAB_VISION.md`.

## 2026-08-03 — Projects use Prototype, Permanent, and Product levels

**Status:** Accepted

Substantial projects should have an explicit completion level:

1. **Prototype** — temporary breadboard or mechanical proof of concept with working code and basic documentation.
2. **Permanent** — durable soldered or otherwise stable implementation that survives normal handling and has been electrically tested.
3. **Product** — finished physical form with enclosure or mounting where appropriate, final documentation, test notes, and a documented repository milestone or release.

Projects may intentionally stop at Prototype, but selected projects should be carried through Product. Roughly every third suitable project should be evaluated for full completion.

## 2026-08-03 — Soldering starts early and is taught incrementally

**Status:** Accepted

Soldering is not reserved for a late advanced module. Short, supervised low-voltage exercises will be introduced early and gradually integrated into real projects.

The progression begins with safe workstation setup, tinning, wire joints, simple through-hole components, inspection, and continuity testing, then advances to transferring a proven breadboard circuit to perfboard.

Direct adult supervision, ventilation, eye protection, a stable iron stand, and electrical testing before power-up are mandatory.

## 2026-08-03 — Reaction Game is the first full-lifecycle candidate

**Status:** Accepted

The current Arduino button-and-LED game will be developed as the first candidate to progress from Prototype through Permanent to Product.

The intended result includes stable gameplay, debounce and reaction-time logic, a soldered durable implementation, a serviceable 3D-printed enclosure, and complete project documentation.

Before creating a new project folder, the existing Arduino lesson and project records must be synchronized so the current work is extended rather than duplicated.