# Step 7 AI dial leak check - clean (train-only basis) path

AI dial basis (Karcher whitening + PC1 + standardization + VSTOXX orientation) refit on TRAIN rows only per walk-forward fold; AI geodesic velocity is basis-independent. Fixed OLS learner (isolates the feature-basis effect, not the learner). Target = 10-min forward RV.

| dur | model R² | persistence R² | ΔR² (dial) | Δ vs leaky basis | n_test |
|---|---|---|---|---|---|
| 30s | 0.6253 | 0.5726 | +0.0528 | +0.0044 | 610,631 |
| 45s | 0.6719 | 0.6370 | +0.0349 | +0.0019 | 407,145 |
| 60s | 0.7063 | 0.6821 | +0.0242 | +0.0005 | 305,725 |

Clean ΔR² ≥ leaky ΔR² at every duration → the full-sample AI dial basis did not inflate the dial's incremental value (conservative, consistent with steps 5 & 6). Absolute R² here is OLS (not the SVR headline); the 0.75 headline is the LE 60s SVR cell, whose LE dial is covered by the step-6 verification.
