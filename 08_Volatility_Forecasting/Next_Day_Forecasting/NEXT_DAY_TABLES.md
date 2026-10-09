# Next-Day Volatility Forecast — Ablation Tables

**Does the covariance-regime dial beat HAR at the next-DAY horizon?** Target = next trading-day realized variance; purged walk-forward by year; embargo 1 day.

- **r2** — OOS R²; **r2_vs_har** — R² difference vs the HAR benchmark; **qlike** lower = better.
- **dm_vs_har_p** — Diebold–Mariano p vs HAR; **in_mcs** — survives the 90% Model Confidence Set.


## Σ = 30s

| metric | model | R² | R² vs HAR | QLIKE | DM p vs HAR | in MCS90 |
|---|---|---|---|---|---|---|
| AI | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| AI | HAR | 0.8298 |  | 0.0802 |  | False |
| AI | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| AI | regime | 0.3438 | -2.8556 | 0.2550 | 0.0000 | False |
| AI | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| AI | HAR_LOB_regime | 0.8197 | -0.0592 | 0.1099 | 0.0000 | False |
| LE | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| LE | HAR | 0.8298 |  | 0.0802 |  | False |
| LE | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| LE | regime | 0.3809 | -2.6376 | 0.2490 | 0.0000 | False |
| LE | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| LE | HAR_LOB_regime | 0.8374 | +0.0448 | 0.0804 | 0.9268 | False |

## Σ = 45s

| metric | model | R² | R² vs HAR | QLIKE | DM p vs HAR | in MCS90 |
|---|---|---|---|---|---|---|
| AI | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| AI | HAR | 0.8298 |  | 0.0802 |  | False |
| AI | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| AI | regime | 0.2842 | -3.2056 | 0.3040 | 0.0000 | False |
| AI | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| AI | HAR_LOB_regime | 0.8191 | -0.0628 | 0.1124 | 0.0000 | False |
| LE | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| LE | HAR | 0.8298 |  | 0.0802 |  | False |
| LE | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| LE | regime | 0.3220 | -2.9837 | 0.3330 | 0.0000 | False |
| LE | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| LE | HAR_LOB_regime | 0.8375 | +0.0452 | 0.0834 | 0.3484 | False |

## Σ = 60s

| metric | model | R² | R² vs HAR | QLIKE | DM p vs HAR | in MCS90 |
|---|---|---|---|---|---|---|
| AI | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| AI | HAR | 0.8298 |  | 0.0802 |  | False |
| AI | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| AI | regime | 0.2211 | -3.5765 | 0.3761 | 0.0000 | False |
| AI | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| AI | HAR_LOB_regime | 0.8211 | -0.0510 | 0.1071 | 0.0000 | False |
| LE | persistence | 0.8018 | -0.1647 | 0.0960 | 0.0000 | False |
| LE | HAR | 0.8298 |  | 0.0802 |  | False |
| LE | LOB | 0.7036 | -0.7416 | 0.1315 | 0.0000 | False |
| LE | regime | 0.2687 | -3.2969 | 0.6362 | 0.0002 | False |
| LE | HAR_LOB | 0.8335 | +0.0220 | 0.0760 | 0.0284 | True |
| LE | HAR_LOB_regime | 0.8342 | +0.0256 | 0.0833 | 0.3566 | False |
