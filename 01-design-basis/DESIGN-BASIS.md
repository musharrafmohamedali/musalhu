# Design Basis: Musalhu site

One source of truth. Every calculation takes its inputs from here, and every change is logged in the revision table.

| Rev | Date | Change |
|---|---|---|
| P01 | | First issue |

## 1. Project

- Description:
- Design working life: (EC0 Table 2.1)
- Consequence class: (EC0 Annex B)

## 2. Codes

| Topic | Codes |
|---|---|
| Basis and actions | BS EN 1990, BS EN 1991-1-1, 1991-1-3, 1991-1-4, 1991-2, with UK National Annexes |
| Steel | BS EN 1993-1-1, BS EN 1993-1-8 |
| Concrete | BS EN 1992-1-1, BS 8500 |
| Geotechnics | BS EN 1997-1, BS 8002, BS 8004, BS 8006-1 |
| Soil description | BS 5930 |

## 3. Site

- Location and terrain source:
- Datum and levels:
- Basic wind velocity v_b,0 = __ m/s (UK NA map), site altitude = __ m

## 4. Ground model

| Stratum | Top level (m) | γ (kN/m³) | φ'k (°) | c'k (kPa) | cu,k (kPa) | Source |
|---|---|---|---|---|---|---|
| | | | | | | |

- Groundwater level:
- Design bearing resistance:

## 5. Water levels

| Level | Value (m AOD) | Used by |
|---|---|---|
| Reservoir top water level | | Dam, water tower |
| Flood level | | Dam spillway |
| Groundwater | | Retaining walls, foundations |

## 6. Actions

| Action | Value | Source |
|---|---|---|
| Imposed: terraces and assembly areas | | EC1-1-1 Tables 6.1 and 6.2 (category C5) |
| Imposed: stage | | EC1-1-1 |
| Wind | | EC1-1-4 |
| Snow | | EC1-1-3 |
| Water pressure | γw = 9.81 kN/m³ | |
| Crowd dynamic loading | | IStructE grandstand dynamics guidance |
| Traffic | | EC1-2 |

## 7. Materials

| Material | Grade | Notes |
|---|---|---|
| Structural steel | S355 | BS EN 10025-2 |
| Concrete (dam, walls, foundations) | C__/__ | Exposure class __ (BS 8500), from `04-calcs/07-concrete-mix` |
| Reinforcement | B500B | |

## 8. Partial factors

- EC0 load combinations: Expression 6.10, or 6.10a and 6.10b (UK NA)
- EC7: Design Approach 1, Combinations 1 and 2 (UK NA)

## 9. Interface register

How the elements depend on each other. This table is where the multidisciplinary design shows.

| From | Passes | To |
|---|---|---|
| Ground model | Bearing resistance, soil strength | Water tower, retaining walls, canopy foundations |
| Reservoir | Top water level | Water tower height, dam design |
| Water tower | Available head | Pipe network |
| Retaining walls | Support | Access road |
| Concrete mix | Strength class, exposure class | Dam, walls, foundations |
| Crowd vibration | Natural frequency limit | Terraces, canopy |

## 10. Assumptions log

| No | Assumption | Why | Used in |
|---|---|---|---|
| A01 | | | |
