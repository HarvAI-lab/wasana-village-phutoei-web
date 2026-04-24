
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
