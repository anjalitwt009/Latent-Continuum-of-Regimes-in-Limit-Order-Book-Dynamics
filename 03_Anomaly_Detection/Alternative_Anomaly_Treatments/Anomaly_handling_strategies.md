# Table 02: Alternative treatments of identified anomalies. Strategies A-E are applied after M1-M6 to test whether downstream state structure depends on hard exclusion. All experiments use $K=4$, random seed 42, and a common sample of up to 200,000 windows. Strategy C is LE-only; Strategy E is a shared tangent-space comparator.

**Source label:** `tab:anomaly_handling`

| Strategy | Treatment | Robustness question | Scope |
| --- | --- | --- | --- |
| A: Hard selection | Fits the state representation using only windows with $C_{h,t}=1$. | Does the canonical clean-window specification produce the inferred structure? | LE and AI |
| B: Soft weighting | Retains all windows through anomaly-weighted resampling; flagged windows are downweighted and calendar exclusions receive zero weight. | Are the conclusions sensitive to complete removal rather than gradual downweighting? | LE and AI |
| C: Score feature | Appends the maximum daily robust $z$-score across MDI, Isolation Forest, and velocity to the LE representation. | Does anomaly severity contain useful state information? | LE only |
| D: Separate state | Fits $K$ states on clean windows and assigns flagged windows to an additional anomaly state. | Are flagged observations better represented as a distinct state? | LE and AI |
| E: Gaussian mixture | Fits a regularised full-covariance Gaussian mixture to the standardised tangent representation. | Do the conclusions depend on the clustering model? | Shared comparator |
