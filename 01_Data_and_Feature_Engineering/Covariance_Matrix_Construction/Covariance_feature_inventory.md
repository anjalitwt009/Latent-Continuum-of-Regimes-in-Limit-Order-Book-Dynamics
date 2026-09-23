# Fixed-order event-level variables used to construct each covariance state.

| # | Variable | Description | Group |
| --- | --- | --- | --- |
| 1 | `bid_price_1` | Best bid price (L1) | Price |
| 2 | `ask_price_1` | Best ask price (L1) | Price |
| 3 | `mid` | Mid-price $\tfrac{1}{2}(b_1+a_1)$ | Price |
| 4 | `spread` | Quoted spread $a_1-b_1$ | Cost |
| 5 | `relative_spread` | Spread divided by mid-price | Cost |
| 6 | `microprice` | Size-weighted microprice | Price/pressure |
| 7 | `bid_vol_1` | Displayed L1 bid quantity | Depth |
| 8 | `ask_vol_1` | Displayed L1 ask quantity | Depth |
| 9 | `trade_volume` | Traded volume associated with the observation | Activity |
| 10 | `depth_imbalance_5` | Five-level depth imbalance | Depth/imbalance |
| 11 | `imbalance_1` | Level-1 imbalance | Imbalance |
| 12 | `imbalance_2` | Level-2 imbalance | Imbalance |
| 13 | `imbalance_3` | Level-3 imbalance | Imbalance |
| 14 | `ofi_weighted` | Depth-weighted five-level order-flow imbalance using depth decay | Order flow |
| 15 | `price_pressure` | Clipped price pressure | Order flow |
