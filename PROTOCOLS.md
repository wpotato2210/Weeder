PROTOCOLS.md
# SEE ENGINE PROTOCOLS

## Input / Output Definitions

| Module | Input | Output | Format |
|--------|-------|--------|--------|
| Vision Model | Camera feed | Crop/Weed classification | JSON / protobuf placeholder |
| Engine LED | Classification | On/Off | Boolean |
| DC Motor Driver | Classification | Motor L/R | PWM signal / command |
| Hydraulic Driver | Classification | Actuator | Analog / CAN bus |
| Sprayer Driver | Classification | Valve/Nozzle | Digital / Relay |

## Timing & Synchronization

- Engine detects → LED toggles → Product actuation
- DC Motor Dev → GUI feedback within X ms
- Hydraulic / Sprayer → gated on engine output + safety checks

## Hardware Abstraction

- Engine output → standardized actuation API
- Products implement hardware-specific driver layers

## Placeholders

- [ ] Protocol serialization formats  
- [ ] Exact timing constraints  
- [ ] Safety interlocks
3. HARDWARE.md
# HARDWARE SPECIFICATION — SEE ENGINE & PRODUCTS

## Engine Hardware

- Camera: [placeholder]
- Processing: MCU / Embedded Computer: [placeholder]
- LED: Engine status LED

## Weeder Hardware

- DC Motor: L/R rotation
- Hydraulic Actuator: linear / rotational
- Precision Driver: fine positioning feedback
- Actuator LEDs: L/R indicators
- GUI terminal / display: for development + feedback

## Sprayer Hardware

- Valve / Nozzle assembly
- Sprayer control electronics
- GUI interface: targeting / status

## Placeholders

- [ ] Pinout diagrams  
- [ ] Motor driver specs  
- [ ] Hydraulic specifications  
- [ ] Valve / nozzle specs  
- [ ] Wiring / harness diagrams
