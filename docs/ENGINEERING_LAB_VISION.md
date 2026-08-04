# Engineering Lab Vision

Last updated: 2026-08-03

## Mission

Engineering Lab is a long-term family program for learning how to design, build, test, document, and improve real devices.

The goal is not merely to follow Arduino tutorials. The goal is to help Vova, Alexandr, and Daria develop practical engineering judgment and gradually become capable of taking an idea from problem definition to a working, documented product.

## Core learning tracks

Engineering Lab develops four tracks in parallel:

1. **Electronics** — Arduino, ESP32, sensors, actuators, communications, soldering, circuit design, and later PCB work.
2. **Software** — embedded C/C++, Python, algorithms, Git, testing, debugging, automation, and later AI or computer vision where useful.
3. **Fabrication** — measurement, hand tools, woodworking, CAD, 3D printing, enclosures, fasteners, materials, and assembly.
4. **Engineering Thinking** — requirements, experiments, datasheets, safety, troubleshooting, trade-offs, documentation, and presentation.

## Learning cadence

The target cadence is approximately three sessions per week, with four sessions per week possible during school breaks.

Sessions do not need to be equal in length. A healthy weekly rhythm may include:

- one concept lesson;
- one guided build or coding session;
- one debugging, soldering, fabrication, or documentation session;
- an optional fourth project session.

The program should preserve momentum without turning every meeting into a new topic. Repetition, testing, and completion are part of the curriculum.

## Project lifecycle

Every substantial project should move through three visible completion levels.

### 1. Prototype

- Built on a breadboard or temporary mechanical setup.
- Demonstrates the main idea.
- Includes working code and basic wiring documentation.
- Can still be fragile and easy to modify.

### 2. Permanent

- Proven circuit is transferred to perfboard, a soldered module, or another suitable durable implementation.
- Wiring is strain-relieved and organized.
- Electrical continuity, polarity, and expected voltages are tested.
- The device can survive normal handling.

### 3. Product

- Includes an enclosure, panel, mount, or other finished physical form where appropriate.
- Includes usable controls, labels, access to power, and serviceability.
- Includes final code, wiring, bill of materials, photos or diagrams, test notes, known limitations, and lessons learned.
- Receives a documented repository milestone or release.

A project may intentionally stop at Prototype, but that status must be explicit. Selected projects must be taken all the way to Product.

## Soldering policy

Soldering is introduced early and incrementally rather than postponed to an advanced module.

Initial practice should progress through short supervised exercises:

1. safe workstation setup and iron handling;
2. tinning a wire and the iron tip;
3. joining two wires;
4. soldering a resistor or LED to practice board;
5. soldering a button or connector;
6. inspecting joints and checking continuity with a multimeter;
7. transferring a proven breadboard circuit to perfboard.

Soldering practice should use low-voltage electronics only, appropriate ventilation, eye protection, a stable iron stand, and direct adult supervision.

## Project selection rules

- New components are first explored in isolation, then reused in at least two later projects where practical.
- Projects should combine previously learned skills instead of constantly discarding earlier knowledge.
- Roughly every third suitable project should be considered for completion as a durable Product.
- At least some finished projects should solve a real household, workshop, aquarium, garden, or family need.
- Fun projects and games are equally valid when they create motivation and require genuine engineering work.

## Current flagship learning project

The current Arduino button-and-LED game is the first candidate for the full lifecycle.

Working name: **Reaction Game**.

Planned progression:

### Prototype

- Complete and stabilize the breadboard circuit.
- Finalize gameplay and button handling.
- Add reliable debounce behavior.
- Measure reaction time with `millis()`.
- Define clear start, waiting, go, result, and false-start states.

### Permanent

- Choose the final button, LED or other indicators, buzzer if used, power arrangement, and connectors.
- Draw the final wiring plan.
- Transfer the proven circuit to perfboard under supervision.
- Inspect solder joints and validate with the multimeter before powering it.

### Product

- Design and print a simple serviceable enclosure.
- Mount the button and indicators for comfortable use.
- Add labels and safe cable routing.
- Record final code, wiring, bill of materials, assembly steps, tests, photos, limitations, and improvements.
- Publish a documented project milestone or release.

Exact project identifier and canonical project folder should be confirmed from the existing Arduino project records before creating a competing duplicate.

## Skill levels

The long-term progression is:

- **Explorer** — follows a circuit, identifies components, and explains the basic result.
- **Maker** — modifies code and wiring and completes small guided projects.
- **Builder** — combines systems, solders durable assemblies, and fabricates simple enclosures.
- **Engineer** — defines requirements, evaluates trade-offs, tests systematically, and documents reproducible designs.
- **Inventor** — proposes and delivers an original project from idea through presentation.

These levels are guidance, not grades. Progress is demonstrated through completed work and increasing independence.

## Definition of a successful Engineering Lab project

A successful project does not have to be perfect. It should leave behind:

- a working or honestly documented experimental result;
- an explanation of what was learned;
- reproducible code, wiring, dimensions, or procedures where applicable;
- known problems and next improvements;
- a repository update that preserves the knowledge for the next session.

## Source of truth

GitHub repository `vladimir-sulima/Engineering-Lab` is the source of truth.

For a new conversation, the assistant must first read `AGENTS.md`, `PROJECT_STATE.md`, this vision document, `docs/DECISIONS.md`, and the affected project or lesson files. The user should be able to say:

> Synchronize with Engineering Lab and continue the current project.

The assistant must then recover the recorded context from GitHub instead of asking the family to reconstruct it from memory.