# See Layer Hardware

## Tier 1: FZ-G1
- Single-row
- CPU / OpenCV CV pipeline
- FPS: 15–30

## Tier 2: Coral TPU
- 3 rows
- TFLite DL models
- FPS: 15–25
- USB hub required for multiple cameras

## Tier 3: Jetson / Laptop GPU
- 4–6 rows
- ONNX/TensorRT DL models
- Parallel ROI processing
- Future-proof for higher FPS

## Constraints
- USB bandwidth
- Latency
- Camera synchronization
- Thermal throttling