# WEEDER PRODUCT ROADMAP

## Versions

| Version | Milestone | Description |
|---------|-----------|-------------|
| v0.4 DC Motor Dev + LED + GUI | M4 | DC Motor rotates L/R; LED indicates actuation; GUI shows actuator state |
| v0.5 Hydraulic Integration + GUI | M5 | Hydraulic actuator control; GUI shows actuator feedback |
| v0.6 Hydraulic Precision + GUI | M6 | Fine hydraulic positioning; GUI shows precise feedback |

## Tracks / Modules

- **Actuation Track — DC Motor (Dev)**
  - Motor Driver Module → M4: Rotate left/right
  - LED Module → M4: L/R indicator
- **Actuation Track — Hydraulic**
  - Hydraulic Driver Module → M5: Actuation follows detection
  - Precision Driver Module → M6: Fine positioning
- **GUI Track**
  - Actuation GUI Module → M4–M6: Displays actuator/position feedback

## Notes

- Multiple weeders can branch from same engine version
- DC Motor + LED track is development-only
- Product versions reference pinned engine milestones

## Placeholders

- [ ] Hydraulic hardware specs  
- [ ] DC motor test parameters  
- [ ] GUI mockups/images