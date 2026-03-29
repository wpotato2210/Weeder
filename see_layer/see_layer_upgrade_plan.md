# See Layer Upgrade Plan

## Path
1. Build single-row system on FZ-G1 (CV)
2. Swap detection backend for 3-row system (TPU/GPU)
3. Scale rows 4–6 with faster hardware
4. Keep pipeline, tracking, and actuation unchanged

## Scaling Notes
- ROI split handles multiple rows
- Output contract ensures downstream compatibility
- Hardware upgrades = configuration change only

## Risks & Mitigation
| Risk | Mitigation |
|------|-----------|
| CV ≠ DL outputs | enforce output contract |
| Timing drift | prediction layer |
| Model portability | ONNX/TFLite design |
| USB/camera bottlenecks | design ROI early |