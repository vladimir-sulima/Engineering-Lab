# Engineering Standards

These conventions keep the lab understandable, reproducible, and pleasant to revisit years later. Improve this document when experience shows a better approach.

## Core principles

1. **Understand first. Build second. Optimize third.**
2. Documentation is part of the deliverable, not an afterthought.
3. Every lesson and project must be reproducible without searching old chats.
4. Prefer small, working increments over complicated first versions.
5. Explain *why* a choice was made whenever it is not obvious.

## IDs and names

IDs are permanent. Titles are short, descriptive, and use Title Case in documents.

| Type | Format | Example |
| --- | --- | --- |
| Foundation project | `FP-001` | `FP-001 • Engineering Lab Foundation` |
| Lesson | `L-001` | `L-001 • First Blink` |
| Project | `P-001` | `P-001 • Traffic Light` |
| Standalone project | `SP-001` | `SP-001 • Greenhouse Controller` |

Folder names use the ID, an underscore, and an ASCII title in `Pascal_Snake_Case`:

```text
L-001_First_Blink
P-001_Traffic_Light
SP-001_Greenhouse_Controller
```

Lesson and project numbering is local to a platform. The platform path supplies the context. A project relates to lessons through its README rather than by nesting it under a lesson.

## Lesson and project records

Every lesson and project is a self-contained directory containing at minimum a `README.md`. Add folders only when needed:

```text
<ID>_<Title>/
├── README.md              # Purpose, status, parts, instructions, learning
├── src/                   # Source code
├── docs/                  # Design notes or supporting documents
└── assets/                # Wiring diagrams and project-specific photos
```

Use the templates in [`templates/`](../templates/) as the starting point. A lesson answers one main engineering question. Projects may require several lessons and have their own version and changelog.

## Documentation requirements

Each README should state:

- ID, title, platform, started date, status, and difficulty;
- goal and prerequisites;
- required components and wiring;
- how to run or reproduce it;
- what was learned and what could improve next;
- related lessons or projects.

Use ISO dates: `YYYY-MM-DD`. Status values are `Planned`, `In Progress`, `On Hold`, `Completed`, or `Archived`.

## Files and shared assets

- Keep project-specific files with the lesson or project.
- Put assets reused by multiple areas in `shared/`.
- Store datasheets as files or stable source links with the component record.
- Never commit passwords, API keys, Wi-Fi credentials, or personal access tokens.

## Code and commits

- Use clear names and comments that explain intent, not syntax.
- Keep working code buildable where practical.
- Record hardware assumptions such as board model, pin mapping, and power source.
- Prefer focused commits with messages such as `docs: add lab standards`, `lesson: start L-001 First Blink`, or `fix: correct button debounce`.

## Change policy

The standards are deliberately lightweight. If a convention starts creating work without improving clarity or safety, change it and record the reason in the lab changelog.

