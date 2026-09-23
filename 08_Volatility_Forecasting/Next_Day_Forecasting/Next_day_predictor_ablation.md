# Next-day predictor ablation

[Open the PDF](./Next_day_predictor_ablation.pdf)

## Description

Next-day predictor ablation under \(R^2\) and QLIKE. The left panel reports
out-of-sample \(R^2\), and the right panel reports QLIKE, for persistence,
HAR, LOB-only, regime-only, HAR-LOB, and HAR-LOB-regime specifications. LOB
information provides a small improvement over HAR, whereas the regime-only
specification performs poorly and adding regimes does not produce a
consistent gain across metrics.

## Interpretation

On the 734-day test set, HAR has \(R^2=0.8298\) and QLIKE 0.0802; HAR-LOB has
\(R^2=0.8335\) and QLIKE 0.0760. LE regime augmentation reaches
\(R^2=0.8374\) but QLIKE 0.0804, while AI augmentation gives
\(R^2=0.8197\) and QLIKE 0.1099. The LE \(R^2\) increase therefore does not
constitute a robust loss improvement over HAR. The model-confidence set's
retention of HAR-LOB is evidence for a small feature refinement, not for the
discrete regime hypothesis.
