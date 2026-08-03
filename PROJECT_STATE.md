# Project State

Last updated: 2026-08-02

## Status

The Engineering-Lab foundation is active. GitHub is the source of truth, and conversations are the interface used to maintain it.

The repository currently covers family engineering education, Arduino work, workshop inventory, 3D printing, woodworking projects, and reusable technical documentation.

## Family participants

- Vova — parent and project lead
- Alexandr — student
- Daria — student

## Current platforms and capabilities

- Arduino Uno
- 3D printing with Bambu P2S
- Woodworking workshop
- Basic electronics bench

## Active workstreams

### Repository operating model

- Adopt the same GitHub-first synchronization model used by Family-Kitchen.
- Require every new assistant session to read the repository before continuing existing work.
- Keep durable decisions and inventory changes out of chat-only state.

### Workshop inventory

Inventory is incomplete and should be expanded as tools and materials are identified.

Recently identified items awaiting or receiving inventory updates:

- Folding metal sawhorses — quantity 2; brand/model unknown.
- Drill press vise — quantity 1; cast-iron appearance; brand/model unknown.

### Woodworking

Active project: floating shelf made from wood strips/blocks with black epoxy-filled voids.

Current recorded stage from conversation:

- Main assembly and epoxy filling are nearing completion.
- Final side was poured and curing.
- Next steps include trimming, flattening or removing a small surface layer, sanding, and applying oil after adequate cure.

### 3D printing — modular aquarium cave

Active project: `P-001 • Modular Aquarium Cave System`.

Current concept:

- Build interchangeable cave rooms and passages along the aquarium front glass.
- Leave viewing rooms open toward the front glass so fish remain visible inside.
- Use a standardized passage connection so rooms, tunnels, junctions, and end caps can be replaced during periodic aquarium teardown and cleaning.
- Include several top entrances with raised substrate-retaining rims.
- Use natural cave textures, rounded stalactites, stalagmites, and structural rock columns.
- Validate the concept with one small prototype before designing the full facade.

Current next step: obtain exact aquarium, substrate, equipment-clearance, and fish-size measurements before dimensioned CAD work.

Canonical record: `platforms/3d-printing/projects/P-001-modular-aquarium-cave/README.md`.

### Electronics education

- Current primary platform: Arduino Uno.
- Lessons and projects should be numbered, dated, reproducible, and stored under platform-specific folders.
- Ready code, wiring, parts, and lessons learned belong in GitHub.

## Current priorities

1. Measure the aquarium and planned installation zone for the modular cave project.
2. Define and test the first standardized cave-passage connector.
3. Reconcile the existing inventory files with tools already known from prior work.
4. Add the two folding sawhorses and drill press vise to the workshop inventory.
5. Continue documenting the floating shelf project.
6. Prepare the next Arduino lesson when the family is ready.

## Known inventory facts requiring preservation

### Electronics tools and components

- AstroAI digital multimeter, 4000 counts.
- ESD-12 tweezers.
- Engineer NS-06 pliers/cutters.
- Elegoo Dupont wire set, 120 pieces.
- Resistors: 220 ohm, 1 kohm, and 10 kohm.
- Arduino Uno kits for family use.

### Fabrication

- Bambu P2S 3D printer.
- Router.
- Drill press.
- Table saw.
- Thickness planer was used during the floating shelf project.
- Folding metal sawhorses, quantity 2.
- Drill press vise, quantity 1.

Some exact brands, models, quantities, and storage locations remain unknown and must not be invented.

## Required startup reading

Every assistant working on an existing Engineering-Lab workstream must read:

1. `AGENTS.md`
2. `PROJECT_STATE.md`
3. `docs/AI_OPERATING_MODEL.md`
4. `docs/DECISIONS.md`
5. `docs/KNOWLEDGE_MAP.md`
6. the affected inventory, lesson, project, or platform files

## Questions that should not be restarted from zero

- Who participates in the family lab.
- Whether GitHub is the source of truth.
- Whether lessons and projects should be numbered and documented.
- Whether platform-specific work should live in separate folders.
- Whether existing tool and component information should be kept in inventory.
- Whether the assistant should update documentation as part of normal work.
- Whether the aquarium cave should be modular and visible through the front glass.
- Whether top cave entrances require raised rims to retain substrate.

## Open questions

- Exact canonical inventory file or files to use after reconciliation with the current repository structure.
- Exact brands and models of workshop tools that have not been confirmed.
- Storage locations for tools and consumables.
- Current quantities of consumables such as epoxy, pigments, sandpaper, oils, and filament.
- Exact next Arduino lesson status after synchronization with existing lesson files.
- Exact internal aquarium dimensions and usable front installation area.
- Largest fish dimensions and safe passage size for the aquarium cave.
- Final aquarium-safe filament, coating, and cleaning method.
- Final cave connector geometry and tolerances.
- Final water-circulation approach through the lower cave level.

## Change policy

Routine additions and corrections may be committed directly to `main`.

Structural changes, bulk moves, deletions, and source-of-truth migrations require explicit approval and normally use a branch and pull request.
