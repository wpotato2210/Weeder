# SEE ENGINE OPENSPEC

## Purpose
Defines deterministic interfaces, modules, and protocols for the See Engine to support multiple products.

## Modules & Interfaces

| Track / Module | Inputs | Outputs | Notes |
|----------------|--------|---------|-------|
| Vision Model (Perception) | Camera feed | Classification | Core engine module |
| Engine LED | Detection | On/Off | See / No See feedback |
| DC Motor Driver (Weeder) | Detection | Motor L/R | Dev-only track |
| Hydraulic Driver (Weeder) | Detection | Actuator position | Gated on DC motor success |
| Precision Driver (Weeder) | Hydraulic | Fine actuation | GUI feedback enabled |
| Sprayer Driver | Detection | Valve/nozzle | Independent product track |
| GUI Modules | Module outputs | Visualization | Product-specific |

## Versioning & Dependencies

- Core engine: v0.1 → v0.3
- Weeder product: v0.4 → v0.6
- Sprayer product: v0.5
- Each product repo pins engine version

## Milestones & Review Points

- Reviews after each milestone
- Reviews before hardware integration
- Development-only tracks do not block reviews

## Protocols & Timing

- Input/Output formats per module
- Deterministic timing for actuation triggers
- Actuator/GUI sync rules
- Hardware abstraction layers for DC motor, hydraulic, sprayer

## Placeholders

- [ ] Complete I/O tables  
- [ ] Timing diagrams  
- [ ] Protocol examples