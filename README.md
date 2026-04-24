# Wasana Village Phutoei Web

This repository contains the live GitHub Pages website for Wasana Village Phutoei.

## Current Status

- The website is already deployed through GitHub Pages.
- The original static website file is `index.html`.
- `index.html` is the locked original base version.
- The permanent original recovery point is the `v1.0-original` tag.

## Locked Website Rule

Do not change the live website during project-control work.

The following actions are not allowed unless they are explicitly approved in a future request:

- Editing `index.html`
- Formatting `index.html`
- Refactoring `index.html`
- Renaming `index.html`
- Changing website design, layout, text, links, images, or structure
- Adding frameworks
- Adding build tools

## Maintenance Workflow

Every future change should follow this workflow:

1. Record the requested work in `TASKS.md`.
2. Confirm which files are allowed to change.
3. Verify that `index.html` remains unchanged before work begins.
4. Make only the approved change.
5. Verify that `index.html` remains unchanged after work is complete.
6. Record the completed change in `CHANGELOG.md`.

## Required Verification

Run these checks before and after future work:

```bash
git status
git diff -- index.html
git diff v1.0-original -- index.html
test -f index.html && echo "index.html exists"
git tag --list v1.0-original
