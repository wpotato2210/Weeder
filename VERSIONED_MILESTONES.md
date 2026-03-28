VERSIONED_MILESTONES.md
# SEE ENGINE + PRODUCT TRACKS — VERSIONED MILESTONES

| Version | Milestone | Track / Module | Description | LED / GUI |
|---------|-----------|----------------|-------------|-----------|
| v0.1 | M1 | Perception (Engine) | Software detection of crop/weed | Engine LED: See / No See |
| v0.2 | M2 | GUI (Engine) | Detection visualization | GUI shows detection |
| v0.3 | M3 | Output Interface (Engine) | Engine LED confirmed | Engine LED |
| v0.4 | M4 | Actuation (Weeder) | DC Motor L/R | DC Motor LED; GUI actuator feedback |
| v0.5 | M5 | Actuation (Weeder) | Hydraulic integration | GUI upgraded for hydraulic feedback |
| v0.6 | M6 | Actuation (Weeder) | Precision hydraulic control | GUI shows fine positioning |
| v0.5 | M5 | Actuation (Sprayer) | Valve/nozzle actuation | GUI shows sprayer targeting/status |

## Notes

- Engine: v0.1–v0.3, includes See / No See LED  
- Weeder: v0.4–v0.6, includes DC Motor + LED, Hydraulic, Precision, GUI  
- Sprayer: v0.5, separate repo, reuses engine modules  
- Reviews after each milestone; before hardware integration; after GUI upgrades  
- Multipurpose engine supports multiple products without duplicating core logic  
- Development-only tracks (DC Motor) do not block main milestones
