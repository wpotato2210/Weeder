# See Layer Pipeline

## Steps
1. Frame acquisition (camera abstraction)
2. Preprocessing
   - Resize / crop ROI
   - Noise reduction
3. Detection Interface
   - CV backend (FZ-G1)
   - DL backend (TPU/GPU)
4. Postprocessing
   - NMS / filtering
5. Tracking
   - Assign detection → row ID
   - Velocity calculation
6. Prediction
   - Forecast future position
   - Schedule actuator fire
7. Actuation
   - Send coordinates/timing to tool

## ROI Strategy
- Single-row → fixed ROI
- Multi-row → split ROIs per row
- Adaptive ROI → track row dynamically