# Feature transformation policy

| Group | Method | Behaviour | Exact feature |
| --- | --- | --- | --- |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_l2_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_l3_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_l4_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_l5_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_weighted_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_total_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ofi_weighted_10_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | signed_vol_window |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | bid_queue_chg_sum |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | ask_queue_chg_sum |
| Signed heavy-tailed | asinh(x) | 12 transformed columns are added; original columns remain. | mid_return |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | trade_vol |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | trade_count_sum |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | n_trades |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | event_count |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | events_per_sec |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | trade_intensity |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | kyle_lambda |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | mean_inter_arrival_ms |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | inter_arrival_std_ms |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | bid_vol_l1 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | ask_vol_l1 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_bid_3 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_ask_3 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_bid_5 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_ask_5 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_bid_10 |
| Positive heavy-tailed | log1p(x) | 17 transformed columns are added; original columns remain. | depth_ask_10 |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | spread_z ← spread_std [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | spread_wide_frac_z ← spread_wide_frac [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | vol_z ← trade_vol [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | activity_z ← event_count [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | ofi_z ← ofi_window [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | ofi_weighted_z ← ofi_weighted_window [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | ofi_weighted_10_z ← ofi_weighted_10_window [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | kyle_lambda_z ← kyle_lambda [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | amihud_z ← amihud_illiq [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | arrival_cv_z ← arrival_cv [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | vwap_dev_z ← vwap_deviation [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | trade_imbalance_z ← trade_imbalance [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | realized_vol_z ← realized_vol [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | return_autocorr_z ← return_autocorr [dropped] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | depth_imbalance_10_z ← depth_imbalance_10 [kept] |
| Rolling robust standardisation | (x − rolling median) / (1.4826 × rolling MAD + ε) | 16 z-score columns exist in the window store; 8 survive the default modelling filter. | vstoxx_z ← vstoxx_level [dropped] |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | spread_wide_frac |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | spread_wide_frac_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | message_to_trade_ratio |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | amihud_illiq → amihud_daily |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | amihud_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | kyle_lambda_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | return_autocorr_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | spread_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | trade_imbalance_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | vstoxx_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | vwap_dev_z |
| Dropped or replaced at modelling time | Remove degenerate, saturated, sentinel, or unstable columns | 12 columns are dropped. Daily Amihud replaces the 30-second Amihud measure. | feat_warmup |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | bid_price_1 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | ask_price_1 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | mid |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | spread |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | relative_spread |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | microprice |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | bid_vol_1 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | ask_vol_1 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | trade_volume |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | depth_imbalance_5 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | imbalance_1 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | imbalance_2 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | imbalance_3 |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | ofi_weighted |
| Raw covariance inputs | No auxiliary transformation | These 15 tick-level inputs remain raw when constructing Σ(t). | price_pressure |
