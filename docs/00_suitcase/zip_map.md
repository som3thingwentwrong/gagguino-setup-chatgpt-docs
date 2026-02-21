# Gaggiuino Official Documentation — ZIP Map  
Navigation guide for the project “Bible”

This document is a navigation map for the Official Gaggiuino Documentation ZIP.
It does not replace the docs.
Its job is to help us pick the correct “chapter” before answering questions, so we don’t mix wiring paths,
machine variants, or firmware procedures.

---

## Start Here (ZIP Entrypoint)
- `docs/README.md`  
- `docs/_sidebar.md`  
- `docs/_coverpage.md`

If unsure where to begin, start with those files and follow the sidebar.

---

## Install Guides (STM32 / Gen 3)
**Where:** `docs/guides-stm32/*`  
**What it’s for:** primary install flows (PCB path, lego/component build, stock integration, custom wiring, flashing).

---

## General Guides
**Where:** `docs/guides/*`  
**What it’s for:** interface guides + machine-specific notes.

---

## Accessories
**Where:** `docs/accessories/*`  
**What it’s for:** add-ons such as ToFnLED and hardware scales.

---

## Schematics
**Where:** `docs/schematics/*`  
**What it’s for:** wiring diagrams / reference images (includes 120V/220V variants).

---

## Media Library
**Where:** `docs/media/*`  
**What it’s for:** shared images used across docs (install photos, diagrams, icons).

---

## Firmware Artifacts
**Where:** `docs/firmware/*`  
**What it’s for:** firmware / partition artifacts used by restore tools.

---

## Restore Tools (HTML)
**Where:**
- `docs/index.html`
- `docs/restore.html`
- `docs/emergency_restore.html`

**What it’s for:** browser-based restore utilities.

---

## User Manuals (Images)
**Where:**
- `docs/manual/gen2/*`
- `docs/manual/gen3/*`

**What it’s for:** UI screenshots and manual assets.

---

## Learning & Reference
**Where:**
- `docs/learning/*`
- `docs/rest-api/rest-api.md`

**What it’s for:** wiring basics, learning sources, example tools, REST API.

---

## Upgrades
**Where:** `docs/guides-upgrade/*`  
**What it’s for:** upgrade paths (PCB upgrade, nano→stm32, relay/dimmer).

---

## Community & Announcements
**Where:**
- `docs/community/*`
- `docs/announcements/*`

**What it’s for:** community links and announcements.

---

## Archive (Legacy)
**Where:** `docs/archive/*`  
**What it’s for:** legacy / nano-era guides & historical notes.

---

## Manifests (JSON)
**Where:**
- `docs/manifest_headless.json`
- `docs/manifest_lcd.json`

**What it’s for:** docs site manifests for headless/LCD modes.

---

## Usage Rules (to stay accurate)

### Wiring questions
Use the appropriate install path in `docs/guides-stm32/`
and cross-check matching visuals in `docs/schematics/` (and `docs/media/` if referenced).

### Firmware / restore questions
Consult `docs/restore.html` / `docs/emergency_restore.html`
and referenced artifacts in `docs/firmware/` before advising action.

### If unsure where to begin
Start at `docs/README.md` and follow `docs/_sidebar.md`.