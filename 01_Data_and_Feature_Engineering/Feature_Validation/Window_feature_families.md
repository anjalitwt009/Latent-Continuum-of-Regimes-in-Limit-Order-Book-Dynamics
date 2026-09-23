# Composition of the 143-variable window store by feature family.

**Source label:** `tab:app_window_feature_families`

| Family | # | Examples |
| --- | --- | --- |
| Order flow/imbalance | 29 | `ofi_window`, `imbal_1-10`, `price_pressure_mean`, `vpin_proxy` |
| Rolling robust z-scores/warm-up | 17 | `spread_z`, `vol_z`, `ofi_z`, `feat_warmup` |
| Lags | 16 | `mid_return_lag1/2`, `realized_vol_lag1/2` |
| Price/return | 14 | `mid_open/close/high/low`, `mid_return`, `vwap` |
| Spread/cost | 13 | `spread_median/max/min`, `effective_spread_mean`, `roll_spread` |
| Depth/book shape | 13 | \texttt{depth_bid/ask_\{3,5,10\}}, `book_slope_ratio_mean`, `depth_gini` |
| Realised variation/volatility | 12 | `realized_var`, `bipower_var`, `parkinson_vol`, `garman_klass_vol` |
| Trading activity | 12 | `n_upticks`, `n_trades`, `events_per_sec`, `arrival_cv` |
| Calendar position | 6 | `minutes_since_open`, `is_first_30min`, `day_of_week` |
| Liquidity/impact | 4 | `kyle_lambda`, `amihud_illiq`, `message_to_trade_ratio` |
| VSTOXX/external | 4 | `vstoxx_level`, `vstoxx_return`, `fesx_vstoxx_corr` |
| Jump measures | 3 | `jump_component`, `jump_flag`, `jump_ratio` |
| Total | 143 |  |

> **Note.** Counts are mutually exclusive and sum to 143. These window-level variables support anomaly detection, forecasting targets, and validation; they do not enter $\Sigma_t$ directly. Table \ref{tab:app_covariance_feature_inventory} separately identifies the 15 raw event-level covariance inputs, including any similarly named analogues.
