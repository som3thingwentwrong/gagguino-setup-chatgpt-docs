# Procedures (Support-Only)

This folder does **not** contain installation instructions.

All step-by-step installation actions must be followed directly from the  
Official Gaggiuino Documentation (verbatim copy stored in this repo under `official/docs/`).

This folder exists to support safe execution by providing:

- Routing to the correct official documentation section
- Risk level classification (Low/Medium/High)
- Live-power requirement labeling (Yes/No)
- Prerequisites / readiness checks
- Rollback point definitions (without step sequences)
- Stop conditions and “when to pause” guidance
- Links to official schematics/media paths

This folder must **never**:
- Duplicate official steps
- Summarize step sequences
- Reorder procedures
- Replace the official docs as a reference

---

## Creating a New Support File

Template:
- `docs/_templates/procedure_template.md`

Minimum required sections:
- Official Source path(s) under `official/docs/`
- Risk Level
- Live Power Required
- Reversible + Rollback Point
- Prerequisites
- Stop Conditions

---

## Files in This Folder

Add support files here only when they point to a specific official doc path.

Example filenames (support-only):

- `thermocouple_support.md`
- `screen_mount_support.md`
- `custom_wiring_support.md`