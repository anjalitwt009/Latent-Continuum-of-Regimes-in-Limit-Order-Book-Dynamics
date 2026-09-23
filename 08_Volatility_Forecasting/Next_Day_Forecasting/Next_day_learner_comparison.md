# Next-day learner comparison

[Open the PDF](./Next_day_learner_comparison.pdf)

## Description

Next-day learner comparison across covariance durations and SPD metrics.
Cells report out-of-sample \(R^2\) for the full HAR-LOB-regime specification.
Regularised linear learners occupy the top of the ranking across
duration-metric cells, indicating that additional nonlinear capacity does not
resolve the weak next-day regime contribution.

## Interpretation

The fifteen-learner comparison shows that covariance representation alone is
a weak daily predictor, while regularised linear learners dominate the full
specification. The conclusion is horizon-specific: covariance information is
meaningful intraday but does not robustly improve daily HAR forecasts,
consistent with the short mean-reversion timescale.
