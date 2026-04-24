
---

# 3. `CHANGELOG.md`

```markdown
# Changelog

All notable repository changes must be documented in this file.

## Entry Format

Each future entry must include:

- Date
- Change summary
- Files changed
- Verification result
- Rollback note

## 2026-04-24

### Cleaned room gallery captions

- Changed room gallery captions to remove numeric suffixes.
- `VIP Room [number]` now displays as `VIP ROOM`.
- `Standard Room [number]` now displays as `STANDARD ROOM`.
- `VIP Extra Room [number]` now displays as `VIP EXTRA ROOM`.
- Left `Resort View` labels unchanged.
- Did not change image `src` values or implement the later VIP Room 2 image replacement.

Files changed:

- `index.html`
- `CHANGELOG.md`
- `TASKS.md`

Verification result:

- Only room gallery `alt` labels were changed in `index.html`.
- No image sources, CSS, layout, gallery behavior, JavaScript functions, unrelated text, or unrelated images were changed.

Rollback note:

- Restore the previous room gallery `alt` labels from the prior commit if this caption cleanup needs to be reverted.

### Added project control files

- Added `README.md`, `PROJECT_RULES.md`, `CHANGELOG.md`, and `TASKS.md`.
- Documented the locked `index.html` rule.
- Documented the `v1.0-original` permanent recovery point.
- Added required verification commands for future work.

Files changed:

- `README.md`
- `PROJECT_RULES.md`
- `CHANGELOG.md`
- `TASKS.md`

Verification result:

- `index.html` remains unchanged.
- `v1.0-original` remains available.

Rollback note:

- Remove the four project control files if this documentation-only setup needs to be reverted.
