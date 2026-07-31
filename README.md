# Engineering Lab

A long-term, family-friendly engineering lab for learning embedded systems, 3D printing, woodworking, and practical engineering by building understandable, documented projects.

**Founded:** 2026-07-23  
**Status:** Active  
**Current platform:** Arduino Uno

> Understand first. Build second. Optimize third.

GitHub is the source of truth. ChatGPT, Codex, and other conversations are interfaces used to read and maintain this repository.

## Start here

Every new assistant session working on an existing Engineering-Lab workstream must:

1. Open `vladimir-sulima/Engineering-Lab` through the connected GitHub app.
2. Read [`AGENTS.md`](AGENTS.md) and [`PROJECT_STATE.md`](PROJECT_STATE.md) from the current `main` branch.
3. Read [`docs/AI_OPERATING_MODEL.md`](docs/AI_OPERATING_MODEL.md), [`docs/DECISIONS.md`](docs/DECISIONS.md), and [`docs/KNOWLEDGE_MAP.md`](docs/KNOWLEDGE_MAP.md).
4. Read the affected inventory, project, lesson, platform, or standards files before answering or publishing changes.
5. Continue from the recorded state instead of reconstructing the project from chat memory.

## Mobile prompt

Use this at the beginning of a new mobile conversation when repository selection is not automatic:

> Synchronize with `vladimir-sulima/Engineering-Lab`. Read `AGENTS.md` and `PROJECT_STATE.md` from `main`, then perform my request and publish the completed change according to the repository rules. GitHub is the source of truth; do not rely on remembered or unrelated local files.

A shorter version is maintained in [`docs/CHATGPT_PROJECT_INSTRUCTIONS.md`](docs/CHATGPT_PROJECT_INSTRUCTIONS.md).

## What belongs here

- Lessons that teach one clear engineering idea.
- Reproducible projects with code, wiring, parts, drawings, measurements, and notes.
- A living inventory of electronics, workshop tools, materials, consumables, and fabrication equipment.
- 3D-printing, woodworking, maintenance, safety, and lessons-learned documentation.

## Repository map

| Location | Purpose |
| --- | --- |
| [`AGENTS.md`](AGENTS.md) | Mandatory assistant operating rules. |
| [`PROJECT_STATE.md`](PROJECT_STATE.md) | Current work, known facts, open questions, and next actions. |
| [`docs/`](docs/) | Standards, roadmap, decisions, knowledge map, inventory, wishlist, and operating documentation. |
| [`platforms/arduino/`](platforms/arduino/) | Arduino lessons, projects, and reusable libraries. |
| [`templates/`](templates/) | Starting points for new lessons and projects. |
| [`shared/`](shared/) | Cross-project datasheets, diagrams, and images. |
| [`scripts/`](scripts/) | Small automation tools, added only when genuinely useful. |

## Operating rules

- Routine inventory additions, corrections, project updates, and documentation clarifications may be committed directly to `main`.
- Structural changes, bulk moves, and deletions require explicit approval and normally use a branch and pull request.
- Unknown brands, models, quantities, measurements, dates, or storage locations must be marked as `unknown` or `needs confirmation` rather than guessed.
- A durable change is complete only after it has been committed or published through the required pull-request flow.

## Getting started

1. Read the [engineering standards](docs/ENGINEERING_STANDARDS.md).
2. Check the [project state](PROJECT_STATE.md), [roadmap](docs/ROADMAP.md), and [knowledge map](docs/KNOWLEDGE_MAP.md).
3. Read the affected source-of-truth files before beginning work.
4. Begin the next planned lesson or project from the recorded state.

## Project status

Foundation project `FP-001 • Engineering Lab Foundation` is in progress. The GitHub-first operating model is now established; the next priority is reconciling and completing the workshop and electronics inventory.
