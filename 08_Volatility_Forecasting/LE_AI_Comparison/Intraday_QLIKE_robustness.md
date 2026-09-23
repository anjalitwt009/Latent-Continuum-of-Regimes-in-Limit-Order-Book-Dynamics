# Intraday QLIKE robustness

[Open the PDF](./Intraday_QLIKE_robustness.pdf)

## Description

Intraday QLIKE across forecast horizons for all fifteen learners and the
persistence benchmark. The three panels correspond to covariance windows of
30, 45, and 60 seconds. Solid lines denote Log-Euclidean (LE) estimates and
dashed lines denote affine-invariant (AI) estimates. Lower QLIKE values
indicate better forecast performance.

## Interpretation

The loss-based comparison supports the main intraday result: the strongest
learners generally remain below the persistence benchmark across forecast
horizons and covariance durations, and the broad horizon profile is similar
under LE and AI geometry. These QLIKE estimates are descriptive because the
archived implementation derived the positive forecast floor from the
evaluation-sample scale rather than fixing it from the training fold.
