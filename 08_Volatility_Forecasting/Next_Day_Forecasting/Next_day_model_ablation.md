# Next-day model ablation

**Canvas source:** `step7-forecasting-tables.canvas.tsx` · **Rows:** 16

| Duration seconds | Metric | Model | R² | QLIKE | ΔR² vs HAR | DM p | MCS90 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| All | Shared | Persistence | .8018 | .0960 | −.1647 | <.001 | No |
| All | Shared | HAR | .8298 | .0802 | Ref. | Ref. | No |
| All | Shared | LOB | .7036 | .1315 | −.7416 | <.001 | No |
| All | Shared | HAR+LOB | .8335 | .0760 | +.0220 | .0284 | Yes |
| 30 | LE | Regime | .3809 | .2490 | −2.6376 | <.001 | No |
| 30 | AI | Regime | .3438 | .2550 | −2.8556 | <.001 | No |
| 45 | LE | Regime | .3220 | .3330 | −2.9837 | <.001 | No |
| 45 | AI | Regime | .2842 | .3040 | −3.2056 | <.001 | No |
| 60 | LE | Regime | .2687 | .6362 | −3.2969 | .0267 | No |
| 60 | AI | Regime | .2211 | .3761 | −3.5765 | <.001 | No |
| 30 | LE | HAR+LOB+regime | .8374 | .0804 | +.0448 | .9268 | No |
| 30 | AI | HAR+LOB+regime | .8197 | .1099 | −.0592 | <.001 | No |
| 45 | LE | HAR+LOB+regime | .8375 | .0834 | +.0452 | .3484 | No |
| 45 | AI | HAR+LOB+regime | .8191 | .1124 | −.0628 | <.001 | No |
| 60 | LE | HAR+LOB+regime | .8342 | .0833 | +.0256 | .3566 | No |
| 60 | AI | HAR+LOB+regime | .8211 | .1071 | −.0510 | <.001 | No |
