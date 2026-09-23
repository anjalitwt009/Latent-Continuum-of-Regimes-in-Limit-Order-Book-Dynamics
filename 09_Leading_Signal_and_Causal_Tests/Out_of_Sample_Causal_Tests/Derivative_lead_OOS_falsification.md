# Derivative-lead out-of-sample falsification

| Duration | Metric | ΔR² with derivatives | 5-day block 95% interval | 10-day block 95% interval | Derivative lead OOS |
| --- | --- | --- | --- | --- | --- |
| 30 s | LE | +0.00637 | [−0.00273, 0.01386] | [−0.00222, 0.01387] | No |
| 30 s | AI | +0.00269 | [−0.00824, 0.01181] | [−0.00785, 0.01207] | No |
| 45 s | LE | +0.00684 | [−0.00366, 0.01535] | [−0.00258, 0.01523] | No |
| 45 s | AI | +0.00299 | [−0.00969, 0.01324] | [−0.00859, 0.01340] | No |
| 60 s | LE | +0.00710 | [−0.00337, 0.01592] | [−0.00327, 0.01597] | No |
| 60 s | AI | +0.00312 | [−0.00937, 0.01372] | [−0.00972, 0.01403] | No |

> **Note.** The validation uses 732 out-of-sample daily observations. In each
> expanding-year fold, the covariance dial and its orientation are fitted on
> prior years only. Targets crossing a fold boundary are purged, the first test
> day is embargoed, and outcomes, predictions, and fold-specific baselines are
> resampled together. Intervals use 2,000 moving-block bootstrap replications.
> Every combined-derivative interval includes zero under both block lengths.
> Velocity alone clears both intervals in the three LE cells but in none of
> the AI cells, so the predeclared cross-geometry leading-signal criterion is
> not met.
