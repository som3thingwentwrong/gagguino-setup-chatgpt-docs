# Official Gaggiuino Documentation — Local Copy Map  
Navigation guide for the project “Bible” (verbatim copy)

This document is a navigation map for the Official Gaggiuino Documentation.
It does not replace the docs.

**Canonical rule:** All installation steps must be followed directly from the Official Documentation.
This repo may route and support, but must not duplicate or rewrite step sequences.

---

## Where the Official Docs Live (in this repo)

The official documentation is stored **verbatim** under:

- `official/docs/`

Do not reorganize or curate this folder.
Do not edit official files here.
Update by replacing with a fresh upstream copy (or use a submodule later if desired).

---

## Start Here (Entrypoint)

- `official/docs/README.md`
- `official/docs/_sidebar.md`
- `official/docs/_coverpage.md`

If unsure where to begin, start with those files and follow the sidebar.

---

## Install Guides (STM32 / Gen 3)

**Where:** `official/docs/guides-stm32/`  
**What it’s for:** primary install flows (PCB path, lego/component build, stock integration, custom wiring, flashing).

---

## General Guides

**Where:** `official/docs/guides/`  
**What it’s for:** interface guides + machine-specific notes.

---

## Accessories

**Where:** `official/docs/accessories/`  
**What it’s for:** add-ons such as ToFnLED and hardware scales.

---

## Schematics

**Where:** `official/docs/schematics/`  
**What it’s for:** wiring diagrams / reference images (includes 120V/220V variants).

---

## Media Library

**Where:** `official/docs/media/`  
**What it’s for:** shared images used across docs (install photos, diagrams, icons).

---

## Firmware Artifacts

**Where:** `official/docs/firmware/`  
**What it’s for:** firmware / partition artifacts used by restore tools.

---

## Restore Tools (HTML)

**Where:**
- `official/docs/index.html`
- `official/docs/restore.html`
- `official/docs/emergency_restore.html`

**What it’s for:** browser-based restore utilities.

---

## User Manuals (Images)

**Where:**
- `official/docs/manual/gen2/`
- `official/docs/manual/gen3/`

**What it’s for:** UI screenshots and manual assets.

---

## Learning & Reference

**Where:**
- `official/docs/learning/`
- `official/docs/rest-api/rest-api.md`

**What it’s for:** wiring basics, learning sources, example tools, REST API.

---

## Upgrades

**Where:** `official/docs/guides-upgrade/`  
**What it’s for:** upgrade paths (PCB upgrade, nano→stm32, relay/dimmer).

---

## Community & Announcements

**Where:**
- `official/docs/community/`
- `official/docs/announcements/`

**What it’s for:** community links and announcements.

---

## Archive (Legacy)

**Where:** `official/docs/archive/`  
**What it’s for:** legacy / nano-era guides & historical notes.

---

## Manifests (JSON)

**Where:**
- `official/docs/manifest_headless.json`
- `official/docs/manifest_lcd.json`

**What it’s for:** docs site manifests for headless/LCD modes.

---

## Usage Rules (to stay accurate)

### Wiring questions
Use the appropriate install path in `official/docs/guides-stm32/`
and cross-check matching visuals in `official/docs/schematics/`
(and `official/docs/media/` if referenced).

### Firmware / restore questions
Consult `official/docs/restore.html` / `official/docs/emergency_restore.html`
and referenced artifacts in `official/docs/firmware/` before advising action.

### If unsure where to begin
Start at `official/docs/README.md` and follow `official/docs/_sidebar.md`.