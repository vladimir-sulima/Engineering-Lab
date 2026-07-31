# AGENTS.md

## Purpose

Engineering-Lab is the family's long-term engineering knowledge base and operating system for electronics, Arduino, 3D printing, woodworking, workshop inventory, lessons, and reproducible projects.

## Repository identity

- Canonical repository: `vladimir-sulima/Engineering-Lab`
- Default branch: `main`
- GitHub is the source of truth. ChatGPT, Codex, and other conversations are interfaces used to read and maintain it.

## Non-negotiable startup behavior

For every request related to an existing Engineering-Lab workstream, synchronize with GitHub before answering, proposing changes, or asking follow-up questions.

The user must not have to repeat information that is already recorded in the repository.

## Mandatory session bootstrap

1. Open `vladimir-sulima/Engineering-Lab` through the connected GitHub app.
2. Read `AGENTS.md` and `PROJECT_STATE.md` from the current `main` branch.
3. Read `docs/AI_OPERATING_MODEL.md`, `docs/DECISIONS.md`, `docs/KNOWLEDGE_MAP.md`, and the affected source-of-truth files.
4. Continue from the recorded state instead of reconstructing the project from chat memory.
5. Do not rely on unrelated local files or remembered repository state.
6. Ask only for details that remain genuinely missing after synchronization.
7. After a successful update, report the repository, branch, files changed, and commit SHA or pull-request link when available.
8. If GitHub access fails, report the exact failed action and error.

Useful explicit instruction:

> Synchronize with `vladimir-sulima/Engineering-Lab`. Read `AGENTS.md` and `PROJECT_STATE.md` from `main`, then perform my request and publish the completed change according to the repository rules. GitHub is the source of truth.

## Operating model

The assistant acts as repository manager, engineering manager, and technical writer.

A durable fact, decision, inventory update, lesson, or project change is complete only after the repository has been updated and the change has been committed or published through the required pull-request flow.

## Sources of truth

- `PROJECT_STATE.md` — current status, active work, open questions, and next actions.
- `docs/AI_OPERATING_MODEL.md` — mandatory assistant behavior and definition of done.
- `docs/CHATGPT_PROJECT_INSTRUCTIONS.md` — persistent bootstrap wording for new chats.
- `docs/DECISIONS.md` — accepted durable decisions.
- `docs/KNOWLEDGE_MAP.md` — what is known, partial, or unknown and where it belongs.
- `docs/ROADMAP.md` — strategic phases and milestones.
- `docs/INVENTORY.md` or current inventory files — actual equipment and component records.
- `platforms/` — platform-specific lessons, projects, code, and libraries.
- `templates/` — reusable lesson and project templates.

## Update rules

1. Read this file and `PROJECT_STATE.md` before substantial work.
2. Never invent brands, models, quantities, measurements, dates, prices, locations, or capabilities.
3. Mark uncertain information as `unknown` or `needs confirmation`.
4. Update every affected source-of-truth file when one fact influences several areas.
5. Avoid asking questions whose answers are already recorded.
6. Record accepted long-lived facts, policies, decisions, lessons learned, and workflows before moving on.
7. Surface conflicts between new proposals and existing decisions before changing direction.
8. Prefer extending an existing record over creating a competing parallel structure.
9. Use ISO dates: `YYYY-MM-DD`.
10. Keep human-readable documentation in Markdown and structured records in YAML when useful.
11. Use English for repository structure and machine-oriented fields. Family-facing notes may remain in Russian or English.
12. Prefer one logical change per commit with a clear imperative message.
13. Small routine updates may be committed directly to `main`.
14. Structural changes, bulk moves, and deletions require explicit approval and normally use a branch and pull request.
15. Never rewrite history or delete substantial information without explicit approval.
16. Report only completed GitHub actions. Never claim a commit, merge, or update that did not succeed.

## Attached images

When the user attaches an image of a tool, component, workpiece, or project state:

1. Extract only facts visible in the image or explicitly supplied by the user.
2. Do not guess brand or model when unreadable.
3. Add or update the appropriate inventory or project record.
4. Record the observation date and mark image-derived uncertainty clearly.
5. Store image assets in the repository only when an available upload workflow supports it; otherwise record that the source was a chat image without claiming the image itself was committed.

## Commit style

Examples:

- `inventory: add drill press vise`
- `inventory: add folding sawhorses`
- `arduino: add lesson 001 LED circuit`
- `project: update floating shelf epoxy stage`
- `docs: clarify workshop inventory workflow`
