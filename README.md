# VoltGuard PCB

KiCad hardware design for **VoltGuard**, a board built around the ESP32-C3 SuperMini module.

## Contents

| Path | Description |
|------|-------------|
| `voltguard/` | KiCad project: schematic (`.kicad_sch`), PCB layout (`.kicad_pcb`), project files |
| `ESP32-C3_SUPERMINI_TH/` | ESP32-C3 SuperMini symbol, footprint and 3D model (`.step`) |
| `NewSymbols.kicad_sym` | Custom symbol library |
| `NewFootprint.pretty/` | Custom footprint library |

## Opening the project

1. Install [KiCad](https://www.kicad.org/) 8 or later.
2. Open `voltguard/voltguard.kicad_pro`.
3. If symbols or footprints show as missing, add `NewSymbols.kicad_sym` and `NewFootprint.pretty` to the project's symbol and footprint library tables (see `ESP32-C3_SUPERMINI_TH/how-to-import.htm`).

---

Author: **Prince Oscar Mwinnuo** ([@Oscar006-HUB](https://github.com/Oscar006-HUB))
