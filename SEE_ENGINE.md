# SEE ENGINE ROADMAP

## Purpose
Multipurpose perception engine for crop/weed detection. Supports multiple product tracks (Weeder, Sprayer, etc.).

## Core Versions

| Version | Milestone | Description |
|---------|-----------|-------------|
| v0.1 Prototype | M1 | Software-only crop/weed detection; **Engine LED: See / No See** |
| v0.2 GUI | M2 | Detection visualized in GUI |
| v0.3 LED Demo | M3 | Engine LED toggles reliably for detection output |

## Tracks / Modules

- **Perception Track**
  - Vision Model Module → M1: Classifies crop/weed
- **GUI Track**
  - Visualization Module → M2: Detection displayed
- **Output Interface Track**
  - Engine LED Module → M3: See / No See LED functional

## Review Points

- After each milestone
- Before branching into product-specific hardware tracks

## Placeholders

- [ ] Camera specs / protocols  
- [ ] Detection thresholds / confidence levels  
- [ ] Timing diagrams for LED / GUI sync