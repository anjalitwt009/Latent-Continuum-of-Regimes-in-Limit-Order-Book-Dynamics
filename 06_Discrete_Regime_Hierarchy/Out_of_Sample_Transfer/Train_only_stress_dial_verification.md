# Step 5 stress-dial predictive — clean (train-only dial) path

Dial (standardization + PC1 + VSTOXX orientation) refit on TRAIN days only, then projected to test. First-half/second-half day split, per step5.predictive().

| dur | persistence R² | geometry R² | combined R² | ΔR² (geometry) | n_test |
|---|---|---|---|---|---|
| 30s | 0.4066 | 0.1922 | 0.4409 | +0.0343 | 418,847 |
| 45s | 0.5051 | 0.2130 | 0.5304 | +0.0253 | 279,357 |
| 60s | 0.5717 | 0.2224 | 0.5910 | +0.0193 | 209,342 |
