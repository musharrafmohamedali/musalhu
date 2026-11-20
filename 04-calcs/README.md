# Calculations

One folder per element. Every calc takes its inputs from `01-design-basis/DESIGN-BASIS.md`.

| Folder | Element | Main checks |
|---|---|---|
| `01-ground-model` | Ground model | Soil classification, design soil parameters |
| `02-reservoir-dam` | Reservoir and small dam | Water pressure and uplift, sliding, overturning, spillway flow, seepage |
| `03-water-tower` | Water tower | Tank height from required head, pipe losses, wind, load takedown, foundation bearing |
| `04-retaining-walls` | Terraced seating | Earth pressure, sliding, overturning, bearing |
| `05-stage-canopy` | Steel canopy | Load takedown, beams, columns, lateral-torsional buckling, connections |
| `06-crowd-vibration` | Terraces and canopy | Natural frequency against crowd jumping frequencies |
| `07-concrete-mix` | Concrete for dam and walls | Target mean strength, w/c ratio, mix proportions |
| `08-access-road` | Access road | Alignment, cut and fill, drainage |

## Calc sheet rules

- **Header on every sheet:** project, element, calc number, sheet number, by, date, revision.
- **Three columns:** Reference (code clause) | Calculation | Output.
- **Numbering:** `MSL-CAL-<folder number>-<nn>`, for example `MSL-CAL-03-01` for the first water tower calc.
- **Hand checks:** every Robot or GSA result gets a hand check next to it.
- **Summary first:** each element opens with a table of every check and its utilisation (design effect ÷ design resistance).
- **Assumptions:** log them in the Design Basis, not only in the calc.
