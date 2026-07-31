# AI Operating Model

## Purpose

This document defines how an AI assistant must work with Engineering-Lab.

## Core rule

GitHub is the source of truth. Conversations are temporary interfaces.

The assistant must synchronize with the repository before continuing an existing workstream and must publish durable changes back to GitHub.

## Startup protocol

Before answering a request about existing Engineering-Lab work:

1. Read `AGENTS.md`.
2. Read `PROJECT_STATE.md`.
3. Read `docs/DECISIONS.md` and `docs/KNOWLEDGE_MAP.md`.
4. Read the affected source-of-truth files.
5. Continue from repository state, not chat memory.

## Responsibilities

The assistant is responsible for:

- maintaining clear repository structure;
- updating inventory when tools, components, or consumables are added or corrected;
- preserving uncertainty instead of guessing;
- linking lessons, projects, code, parts, and lessons learned;
- keeping `PROJECT_STATE.md` current after meaningful progress;
- recording durable decisions in `docs/DECISIONS.md`;
- reporting completed GitHub operations accurately.

## Definition of done

A durable change is complete only when:

1. the relevant source-of-truth file is updated;
2. related records are updated when necessary;
3. the change is committed to GitHub or published through an approved pull request;
4. the user is told the repository, branch, files changed, and commit or PR identifier.

A statement made only in chat is not a completed durable change.

## Inventory behavior

When new equipment is shown or described:

1. identify only confirmed facts;
2. search existing inventory before creating a duplicate;
3. update the existing record when possible;
4. use `unknown` or `needs confirmation` for missing model, brand, quantity, or location;
5. record quantity, status, and source date when known;
6. update project documentation if the item is relevant to an active project.

## Project behavior

Every reproducible project should eventually include:

- purpose and status;
- participants;
- bill of materials;
- required tools;
- measurements and design decisions;
- code or drawings when applicable;
- build notes and photos when supported;
- safety notes;
- lessons learned;
- next actions.

## Lesson behavior

Lessons should be:

- numbered;
- dated;
- platform-specific;
- focused on one clear concept;
- written with English technical terms where useful;
- accompanied by code, wiring, parts, tests, and expected results when applicable.

## Change routing

Commit directly to `main` for:

- routine inventory additions;
- corrections;
- project status updates;
- lesson notes;
- documentation clarifications.

Use a branch and pull request for:

- structural redesign;
- bulk moves;
- large migrations;
- substantial deletions;
- changes that may invalidate existing links or workflows.

## Accuracy and safety

- Never claim a GitHub action succeeded unless the tool returned success.
- Never invent tool specifications or safety ratings.
- Surface conflicts with existing decisions.
- For potentially dangerous work, preserve safety notes and recommend manufacturer guidance where appropriate.
