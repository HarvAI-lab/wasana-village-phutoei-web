# Tasks

This file tracks future requested work.

Every future task must identify:

- Goal
- Allowed files
- Forbidden files
- Whether `index.html` may be touched
- Required verification
- Expected documentation update
- Task type: website content, project documentation, or repository control

Default rule: `index.html` may not be touched.

## Proposed

- Add or refine documentation-only project controls.
  - Task type: project documentation
  - Allowed files: documentation files only
  - Forbidden files: `index.html`
  - `index.html` may be touched: no

## Approved

- None.

## In Progress

- None.

## Completed

- Added initial project control files.
  - Task type: project documentation
  - Allowed files: `README.md`, `PROJECT_RULES.md`, `CHANGELOG.md`, `TASKS.md`
  - Forbidden files: `index.html`
  - `index.html` may be touched: no
- Task 1B: Clean room gallery captions.
  - Task type: website content
  - Allowed files: `index.html`, `CHANGELOG.md`, `TASKS.md`
  - Forbidden files: `README.md`, `PROJECT_RULES.md`, CSS, layout, gallery behavior, JavaScript functions, unrelated images, unrelated text
  - `index.html` may be touched: yes, only room gallery `alt` labels
  - Result: changed `VIP Room [number]` to `VIP ROOM`, `Standard Room [number]` to `STANDARD ROOM`, and `VIP Extra Room [number]` to `VIP EXTRA ROOM`
  - Excluded: `Resort View` labels, image `src` values, Task 2 image replacement

## Rejected

- None.
