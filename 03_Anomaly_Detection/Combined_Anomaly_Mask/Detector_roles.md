# Anomaly-detection components and their roles in state selection.

**Source label:** `tab:detector_roles`

| Component | Research use | Status |
| --- | --- | --- |
| M1: Tick-validity guard | Prevents invalid ticks from contaminating the one-second series used by MDI. | Pre-filter |
| M2: Manifold velocity | Measures rapid transitions in covariance structure. | Diagnostic |
| M3: Matrix-profile discord | Detects unusual intraday trajectories that differ from recurring market patterns. | Gates |
| M4: Hawkes excitation | Measures self-exciting trading activity and distinguishes endogenous clustering from exogenous shocks. | Diagnostic |
| M5: Isolation Forest | Detects unusual multivariate combinations of liquidity, volatility, depth, flow, and activity. | Gates |
| M6: Calendar rule | Removes intervals not representative of continuous-book trading. | Gates |
