# musalhu

**MUSALHU**: a civil engineering bassist who drafts and designs structures.

This repo follows one project from start to finish: a hillside music venue and studio, designed from the first sketch to detailed calculations and drawings. It uses hydraulics, geotechnics, structural analysis, materials and highway engineering together. The same project drives the Musalhu identity: the mask, the posters and the music.

> **Status: WIP.** This is an academic design study. All site data, loads and assumptions are stated in the Design Basis. The design has not been checked by a chartered engineer.

## The site

| Element | Disciplines |
|---|---|
| Site and ground model | Survey, geology, geotechnics |
| Reservoir and small dam | Hydraulics, geotechnics, concrete |
| Water tower | Hydraulics, structures, foundations |
| Terraced seating (retaining walls) | Geotechnics, structures |
| Stage canopy (steel frame) | Structural analysis, steel design |
| Crowd-induced vibration | Structural dynamics |
| Concrete mix | Materials |
| Access road | Highways, Civil 3D |

## Folder map

| Folder | What goes in it |
|---|---|
| `00-brief/` | The brief and the story of the site |
| `01-design-basis/` | The loads, soil values, water levels and materials every calc uses, plus how the elements depend on each other |
| `02-site/` | Survey, terrain, geology, site appraisal |
| `03-concept/` | Dated sketch scans, options, ballpark checks |
| `04-calcs/` | Calculations, one folder per element |
| `05-models/` | Revit, Robot, GSA and Civil 3D models |
| `06-drawings/` | Drawing PDFs and the drawing register |
| `07-brand/` | Mask, posters, identity, title block |
| `08-music/` | Track list, artwork, liner notes (no audio files) |
| `09-portfolio/` | Layouts for the full book and the short engineering portfolio |

## Stages

Brief → Site appraisal → Sketches → Options → Ballpark checks → Scheme calcs → Drawings and details → Construction sequence

Commit at the end of each stage, so the history shows how the project grew.

## What stays out of this repo

- **Audio, video and archives.** GitHub rejects files over 100 MB, so keep these in their own folders.
- **Design codes, standards and reference books.** They are copyrighted, so cite the clause numbers instead. Keep local copies in `_private/`, which git ignores.
- **Software backups and temp files.** See `.gitignore`.
