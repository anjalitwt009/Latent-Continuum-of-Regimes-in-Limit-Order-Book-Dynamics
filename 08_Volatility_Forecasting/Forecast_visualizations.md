# Forecast visualizations

## Intraday forecasting

- [Incremental R² across horizons](./Forecast_Horizon_Grid/Intraday_incremental_R2.pdf) - best-model gains over persistence for every feasible duration, horizon, and geometry.
- [Cross-duration R² comparison](./Forecast_Horizon_Grid/Cross_duration_R2.pdf) - absolute forecast performance across covariance durations.
- [Incremental R² map](./Forecast_Horizon_Grid/Intraday_incremental_R2_map.pdf) - complete duration-horizon comparison.
- [Nonlinear capacity gains](./Linear_Nonlinear_Comparison/Nonlinear_capacity_gains.pdf) - gain from replacing the linear model with the best learner.
- [Performance across learners](./Fifteen_Model_Bakeoff/Forecast_performance_across_learners.pdf) - out-of-sample R² for all fifteen learners.
- [Thirty-second learner comparison](./Fifteen_Model_Bakeoff/Forecast_performance_30s.pdf) - detailed learner profiles on the 30-second grid.
- [Learner R² heatmap](./Fifteen_Model_Bakeoff/Learner_R2_heatmap.pdf) - learner performance across duration-metric cells.
- [Learner ranking](./Fifteen_Model_Bakeoff/Learner_ranking.pdf) - aggregate learner ordering.
- [LE-AI comparison](./LE_AI_Comparison/LE_AI_forecast_comparison.pdf) - agreement between the two SPD geometries.
- [QLIKE robustness](./LE_AI_Comparison/Intraday_QLIKE_robustness.pdf) - loss-based robustness across learners and horizons.
- [QLIKE across horizons](./LE_AI_Comparison/QLIKE_across_horizons.pdf) - horizon-specific loss profiles.
- [Train-test actual and predicted volatility](./Intraday_Forecasting/Train_test_actual_prediction_60s_10m_LE_SVR.pdf) - the 60-second, ten-minute LE-SVR specification.

## Next-day forecasting

- [Predictor ablation](./Next_Day_Forecasting/Next_day_predictor_ablation.pdf) - HAR, LOB, and covariance-state ablations using train-floor QLIKE.
- [Learner comparison](./Next_Day_Forecasting/Next_day_learner_comparison.pdf) - next-day performance of all fifteen learners.

## Interactive dashboards

- [Intraday master dashboard](./Fifteen_Model_Bakeoff/Intraday_master_dashboard.html)
- [30-second bake-off](./Fifteen_Model_Bakeoff/Intraday_bakeoff_dashboard_30s.html)
- [45-second bake-off](./Fifteen_Model_Bakeoff/Intraday_bakeoff_dashboard_45s.html)
- [60-second bake-off](./Fifteen_Model_Bakeoff/Intraday_bakeoff_dashboard_60s.html)
- [Next-day dashboard](./Next_Day_Forecasting/Next_day_dashboard.html)
