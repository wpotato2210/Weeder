# See Layer Timing and FPS

## Latency Budget
- Preprocessing: ≤ 20 ms
- Detection: ≤ 50 ms (FZ-G1) / ≤ 30 ms (TPU)
- Tracking + Prediction: ≤ 10 ms
- Actuation: ≤ 10 ms

## FPS Targets
| Hardware | Rows | FPS |
|----------|------|-----|
| FZ-G1    | 1    | 15–30 |
| Coral TPU| 3    | 15–25 |
| GPU/Laptop| 4–6 | 20–40 |

## Simulation
- Use artificial delays to mimic target FPS
- Validate tracking + actuation logic independent of hardware