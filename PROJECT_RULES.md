
---

# 2. `PROJECT_RULES.md`

```markdown
# Project Rules

These rules protect the deployed original website.

## Permanent Recovery Point

The `v1.0-original` tag is the permanent recovery point for the original website.

Do not move, delete, recreate, or overwrite `v1.0-original`.

## Locked File

`index.html` is locked.

Do not:

- Edit `index.html`
- Format `index.html`
- Refactor `index.html`
- Rename `index.html`
- Optimize `index.html`
- Reorganize code inside `index.html`
- Change website design, layout, text, links, images, or structure

This rule can only be changed by an explicit future request that clearly says `index.html` may be modified.

## Repository Restrictions

Do not add frameworks, build tools, package managers, generated folders, or GitHub Actions unless they are explicitly approved in a future request.

Do not make broad cleanup changes. Every change must be small, named, documented, and limited to approved files.

## Required Change Request Details

Before future work begins, the request must identify:

- Goal
- Allowed files
- Forbidden files
- Whether `index.html` may be touched
- Required verification
- Expected documentation update

Default answer for `index.html` is always: no, it may not be touched.

## Required Verification

Before and after future work, run:

```bash
git status
git diff -- index.html
git diff v1.0-original -- index.html
test -f index.html && echo "index.html exists"
git tag --list v1.0-original
