# Table D1: Realised-variation quantities and forecast-horizon specification.

**Source label:** `tab:app_forecast_targets`

| Quantity | Definition | Role |
| --- | --- | --- |
| Realised variance and volatility | $\mathrm{RV}_t=\sum_i r_i^2$ and $\mathrm{RVol}_t=\sqrt{\mathrm{RV}_t}$, using within-session log-mid-price returns with the first session return set to zero | Forecast target and persistence benchmark |
| Bipower variation | $\mathrm{BV}_t=(\pi/2)\sum_i \vert r_i\vert \vert r_{i-1}\vert $ | Jump-robust continuous-variation estimate |
| Jump component | $J_t=\max\{\mathrm{RV}_t-\mathrm{BV}_t,0\}$ | Non-negative discontinuity measure |
| Forward horizons | Next complete native window; 30, 45, and 60 seconds; 2, 5, 10, 15, and 30 minutes; and 1 hour | Multi-horizon forecasting |
| Constraints | Targets remain within the same trading session, and no forecast horizon is finer than the native covariance duration | Temporal-alignment and leakage control |

> **Note.** These quantities are constructed separately from the 15 event-level inputs to $\Sigma_t$. Realised variance enters the jump decomposition, while realised volatility supplies the volatility-scale forecasting outcome.
