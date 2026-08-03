# P-001 • Modular Aquarium Cave System

**Platform:** 3D printing — Bambu P2S  
**Started:** 2026-08-02  
**Completed:** —  
**Status:** Concept development  
**Version:** v0.1  
**Difficulty:** ⭐⭐⭐⭐☆

## Goal

Design and print a modular underwater cave system for the family's approximately 20-gallon rectangular aquarium.

The system should create a visible lower cave level along the front glass, allowing the family to watch fish swimming inside while preserving normal open-water space above.

## Confirmed design requirements

- The main cave rooms must sit against or immediately behind the front glass so their interiors are visible from the aquarium facade.
- The front side of each viewing room remains open; the aquarium glass acts as the viewing wall.
- The system must be modular rather than one permanent monolithic structure.
- Rooms and passages should use a standardized connection interface so individual modules can be replaced during periodic aquarium teardown and cleaning.
- The aquarium is normally dismantled and cleaned approximately every six months, so modules may be removed during that maintenance.
- Modules may include rooms, connecting tunnels, bends, junctions, end caps, and vertical entrances.
- Several entrances should descend from the upper substrate level into the cave system.
- Every top entrance must have a raised rim to reduce substrate falling into the cave.
- Current concept rim height: approximately 8–10 mm above the surrounding roof surface; final value needs testing against the actual substrate.
- Exterior and interior visible surfaces should resemble a natural cave with textured rock walls.
- Decorative features may include rounded stalactites, stalagmites, rock columns, cracks, ledges, and erosion patterns.
- All fish-contacting shapes must avoid sharp points, narrow traps, and fin-catching gaps.
- Water circulation through the lower level must be included in the design. One concept is to route aeration or water movement through the lower cave and let it rise through an entrance, but the final flow method is not yet selected.
- Optional low-level cave lighting may be investigated later; it is outside the first prototype scope.

## Existing aquarium context

- Aquarium volume: approximately 20 US gallons, based on the user's description and linked product; exact internal dimensions need direct measurement before CAD work.
- Current substrate depth: approximately 80 mm in some areas.
- The aquarium already contains small front-glass cave inserts that demonstrate the basic viewing concept.
- The family views the aquarium primarily through the front glass, not from above.
- Source reference: aquarium photograph supplied in chat on 2026-08-02. The image itself is not currently stored in the repository.

## Modular architecture — initial proposal

Use a common passage port shared by all interchangeable modules.

Initial module families:

1. **Viewing room** — broad chamber open toward the front glass.
2. **Straight passage** — connects two rooms.
3. **Corner passage** — 90-degree direction change.
4. **T-junction** — connects three paths.
5. **Vertical entrance** — opening from the substrate surface with a raised rim.
6. **End cap** — safely closes an unused connection.
7. **Transition module** — adapts a room to a passage while hiding the joint with rock texture.

The connection must:

- align the floors of adjacent modules;
- resist accidental separation under substrate;
- avoid creating a narrow fish trap at the joint;
- be separable during scheduled maintenance;
- tolerate normal FDM dimensional variation;
- remain visually hidden behind cave texture where practical.

The exact connector geometry is undecided. Candidate approaches include a loose tongue-and-groove, overlapping sleeve, or keyed sliding joint. Magnets and metal fasteners are not part of the baseline concept.

## First prototype scope

Create a minimal test assembly before designing the full facade:

- one front viewing room;
- one standardized side passage port;
- one short connecting tunnel;
- one top entrance with substrate-retaining rim;
- one removable end cap;
- representative cave texture;
- a few rounded stalactite/stalagmite features;
- provisions for water exchange and cleaning.

The prototype should validate:

- fish access and turning space;
- visibility through the front glass;
- substrate retention at the top entrance;
- connector fit and removability;
- debris accumulation;
- water circulation;
- cleaning access;
- printability and structural strength.

## Measurements required before CAD

- Exact internal aquarium length, depth, and usable height.
- Front frame/lip dimensions that may obstruct the cave view.
- Actual substrate depth along the planned front installation zone.
- Maximum fish body length and body height, including the largest current species.
- Desired width of the facade installation.
- Distance from front glass to plants, filter equipment, heater, and existing decorations.
- Preferred number and approximate positions of top entrances.
- Bambu P2S verified printable build area from the canonical printer record.

## Material and safety questions

Material selection is not yet finalized. Before printing the aquarium-use prototype, document and verify:

- suitable filament for long-term freshwater immersion;
- whether the printed surface requires sealing;
- cleaning and curing requirements before installation;
- colorant, paint, epoxy, or coating compatibility if finishing is used;
- resistance to delamination and trapped contamination;
- safe minimum feature radii for the fish in this aquarium.

Until those questions are resolved, this project remains at the concept and dry-fit prototype stage.

## Design principles

- Engineer the internal geometry first; apply organic cave texture afterward.
- Prefer several useful large modules over many decorative miniature pieces.
- Make every water-filled cavity inspectable or flushable.
- Avoid blind dead-end cavities unless they are intentionally capped and accessible.
- Use rock columns as both visual features and roof supports.
- Keep stalactites and stalagmites rounded, sparse, and easy to brush clean.
- Treat the front glass as the transparent wall of the cave rooms.
- Preserve uncertainty rather than guessing dimensions from the photograph or product listing.

## Current decisions

- Modular replaceable rooms and passages are preferred over a single permanent facade.
- Periodic aquarium teardown is expected and can be used to reconfigure or replace modules.
- A standardized connection interface will be developed before multiple room designs are produced.
- The initial aesthetic direction is a natural textured cave rather than a house or cartoon decoration.
- Raised rims around top entrances are required to limit substrate intrusion.

## Next actions

1. Measure the aquarium and planned installation zone.
2. Record fish sizes and identify the largest fish that must safely navigate the system.
3. Produce dimensioned top, front, and side concept drawings.
4. Define the first passage-port standard.
5. Model and print a small dry-fit connector test.
6. After connector validation, model the first viewing-room prototype.

## Changelog

### v0.1 — 2026-08-02

- Created the project record.
- Captured the modular cave concept, front-glass viewing requirement, top entrances with raised rims, natural cave texture, and first prototype scope.
