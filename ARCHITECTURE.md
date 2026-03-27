ARCHITECTURE.md
# SYSTEM ARCHITECTURE — SEE ENGINE + PRODUCTS

## Overview
Describes high-level architecture for engine and product tracks.

### Layers

1. **Planning Layer**
   - Defines product tracks, milestones, and versioning
2. **See Layer (Core Engine)**
   - Perception modules
   - Engine LED
   - GUI visualization
3. **Think Layer (Optional)**
   - Decision-making / actuation planning
4. **Do Layer (Product Track)**
   - Weeder: DC Motor → Hydraulic → Precision
   - Sprayer: Valve/Nozzle

### Interfaces

- Engine → Products
  - Detection output → Actuation input
  - Engine LED → Product GUI/feedback
- Product → GUI
  - Actuator status → GUI visualization

### Module Relationships


See Engine (Core)
├─ Vision Model
├─ Engine LED
└─ GUI
Products (Weeder / Sprayer)
├─ Actuation Modules
└─ GUI Modules


## Placeholders

- [ ] Detailed UML / sequence diagrams  
- [ ] Hardware/software boundaries
