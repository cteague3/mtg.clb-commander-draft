# CLB Reusable Commander Draft Cube

This repository documents and tracks a reusable *Commander Legends: Battle for Baldur's Gate* (CLB) Commander Draft cube built from five Prerelease Kits. It supports house drafts for 3, 4, or 5 players.

## Repository contents

### Source card exports

`data/` contains the 15 UrzaGatherer CSV exports for the three boosters from each of five kits (`CLB-Kit01-Booster01.csv` through `CLB-Kit05-Booster03.csv`). The `Deck count` values in these exports define the authoritative **300-card cube inventory**: each booster contributes 20 cards. Keep these source exports unchanged.

`data/CLB-Promos.csv` lists the five prerelease promos separately. They are tracked for event use, but are not part of the 300-card cube inventory.

### Guides and analysis

- [`docs/CLB-Cube-Guide.md`](docs/CLB-Cube-Guide.md) is the main guide. It explains official Commander Limited rules and clearly separates them from this cube's house procedures.
- [`docs/CLB-Cube-Guide.pdf`](docs/CLB-Cube-Guide.pdf) is the printable companion to the Markdown guide.
- [`output/CLB-Cube-Data.xlsx`](output/CLB-Cube-Data.xlsx) is the detailed inventory and event-planning workbook. Its sheets include the 300-card inventory, original booster summaries, color/pool distribution, Session Pool selection, reconstructed-pack recipe, quick guide, promo list, methodology notes, and an official-rules-versus-house-procedures reference.

The CSV exports are the source of truth for card counts and attributes. The workbook organizes and analyzes that inventory; the Markdown guide explains how to use it; the PDF provides a print-friendly version of the guide. If the inventory is ever deliberately changed, update the derived workbook and both guide formats to remain consistent.

## Cube overview

| Players | Reconstructed packs | Cards used | Resting Pool |
|---:|---:|---:|---:|
| 3 | 9 | 180 | 120 |
| 4 | 12 | 240 | 60 |
| 5 | 15 | 300 | 0 |

Each player receives three 20-card packs and drafts two cards per pick. The 60-, 80-, and 100-percent Session Pool selection, Resting Pool rotation, category balancing, snake-dealing, pack reconstruction, and between-game sideboard handling are **house procedures**, not official Wizards collation or tournament rules. Decks must contain at least 60 cards, including basic lands, and multiplayer Commander games start at 40 life. See the guide for citations and the complete procedures.
