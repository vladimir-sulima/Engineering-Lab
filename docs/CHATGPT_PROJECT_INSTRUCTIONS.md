# ChatGPT Project Instructions

Use the following persistent instruction for conversations related to Engineering-Lab:

> Synchronize with `vladimir-sulima/Engineering-Lab` through the connected GitHub app. Read `AGENTS.md` and `PROJECT_STATE.md` from `main`, then read `docs/AI_OPERATING_MODEL.md`, `docs/DECISIONS.md`, `docs/KNOWLEDGE_MAP.md`, and the affected source-of-truth files. Continue from the recorded state instead of reconstructing the project from chat memory. GitHub is the source of truth. Publish completed durable changes according to the repository rules and report the branch, changed files, and commit or pull-request identifier.

## Mobile short form

> Sync with `vladimir-sulima/Engineering-Lab`, read `AGENTS.md` and `PROJECT_STATE.md`, then continue my request and publish the completed change. GitHub is the source of truth.

## Expected behavior

- Do not ask the user to repeat facts already stored in GitHub.
- Do not claim an update is complete until it is committed or published.
- Mark missing information as unknown instead of guessing.
- Update project state and related source-of-truth files when durable progress is made.
