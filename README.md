# TKA Brand

Canonical, public brand assets for The King's Academy — logos for the main marks, athletics,
and every sub-brand.

This repo holds **assets only**. The internal "King's Voice" context file (tone, conventions,
comms strategy) lives in the private `tka-admin-agent` repo and references these assets by URL.

## What's here
- `brand/logos/` — web/print-ready logos (PNG, JPG, PDF), organized by mark and sub-brand.
- `brand/ASSETS.md` — index of every asset with its path.
- `brand/colors.md`, `brand/typography.md` — palette (hex) and type specs _(pending brand guide)_.

## How to grab an asset
Open `brand/ASSETS.md` for the list and direct links. When asking Claude to build something
("make a flyer with the TKA logo"), Claude pulls the right file and usage rule from here.

## Updating
Drop new/updated files in the right folder, update `brand/ASSETS.md`, commit, and push.
Changes propagate to everyone automatically — no re-distributing files.
