# TKA Brand

Canonical brand assets and voice for The King's Academy — logos, colors, type, and the
global **King's Voice** context file that every admin's Claude references.

This repo is intentionally separate from `tka-admin-agent` (internal/private) so brand assets
can be grabbed directly. The admin-agent repo *references* this one; it does not duplicate it.

## What's here
- `KINGS-VOICE.md` — the global voice/tone/conventions file (the thing Claude loads as context).
- `brand/logos/` — web-ready logo files (SVG + PNG; primary, reversed/white, mark-only).
- `brand/ASSETS.md` — index of every asset: what it is, when to use it, and its link.
- `brand/colors.md`, `brand/typography.md` — palette (hex) and type specs.
- `brand/BRAND-GUIDE.pdf` — source brand guide, if provided.

## How to grab an asset
Open `brand/ASSETS.md` for the list and direct links. When asking Claude to build something
("make a flyer with the TKA logo"), Claude pulls the right file and usage rule from here.

## Updating
Drop new/updated files in the right folder, update `brand/ASSETS.md`, commit, and push.
Changes propagate to everyone automatically — no re-distributing files.
