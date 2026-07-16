# Desk Otter Codex Pet

A bespectacled desk-worker otter mascot in a blue shirt, animated for Codex task states.

This repository contains the Codex-compatible v2 Desk Otter pet package, including the 9 standard animation rows plus 16 looking directions.

![Desk Otter contact sheet](contact-sheet.png)

## Package files

- `pet.json`
- `spritesheet.webp`
- `contact-sheet.png`
- `desk-otter-v2-validation.json`

## Version

- `spriteVersionNumber`: `2`
- atlas size: `1536x2288`
- cell size: `192x208`
- layout: `8` columns x `11` rows
- rows `0-8`: standard Codex pet animations
- rows `9-10`: 16 clockwise looking directions

## States

- `idle`
- `running-right`
- `running-left`
- `waving`
- `jumping`
- `failed`
- `waiting`
- `running`
- `review`
- `look-000` through `look-337.5`

## Install

Copy this folder into your Codex pets directory:

```powershell
Copy-Item -Recurse -Force . "$env:USERPROFILE\.codex\pets\desk-otter"
```

Or copy only the required package files:

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets\desk-otter"
Copy-Item -Force .\pet.json "$env:USERPROFILE\.codex\pets\desk-otter\pet.json"
Copy-Item -Force .\spritesheet.webp "$env:USERPROFILE\.codex\pets\desk-otter\spritesheet.webp"
```

## Validation

The installed v2 atlas passed `hatch-pet` validation with no errors or warnings:

```text
ok: true
format: WEBP
width: 1536
height: 2288
columns: 8
rows: 11
spriteVersionNumber: 2
errors: []
warnings: []
```

Additional QA artifacts from the upgrade run are in `desk-otter-v2-run/qa/`.
