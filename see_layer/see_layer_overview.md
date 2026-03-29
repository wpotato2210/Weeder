# See Layer Overview

## Purpose
Hardware-agnostic vision pipeline for crop/weed detection, scalable from 1 to 6 rows.

## Architecture
Camera(s) → Preprocess → Detection Interface → Postprocess → Tracking → Prediction → Actuation

## Key Principles
- Abstract detection interface (CV vs DL)
- Row-agnostic pipeline
- Configurable ROI mapping
- Unified output contract
- Parallelization handled internally

## Hardware Targets
- FZ-G1 → single-row CV
- Coral TPU → 3-row DL
- Jetson/Laptop GPU → 4–6 rows DL

## Output Contract
Detection {
float x_mm;
float y_mm;
int row_id;
float confidence;
timestamp t;
}

