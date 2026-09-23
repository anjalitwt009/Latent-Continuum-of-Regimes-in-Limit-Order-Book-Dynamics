# Next-day upper-tail performance

**Canvas source:** `step7-forecasting-tables.canvas.tsx` · **Rows:** 16

| Duration seconds | Metric | Model | Tail RMSE | Tail QLIKE | Underprediction | Mean shortfall |
| --- | --- | --- | --- | --- | --- | --- |
| All | Shared | Persistence | .005924 | .1885 | .7703 | .004288 |
| All | Shared | HAR | .006446 | .2387 | .7703 | .004787 |
| All | Shared | LOB | .006721 | .2419 | .5676 | .006207 |
| All | Shared | HAR+LOB | .006347 | .2204 | .7162 | .004883 |
| 30 | LE | Regime | .006327 | .1522 | .3649 | .006692 |
| 30 | AI | Regime | .006339 | .1487 | .3514 | .006398 |
| 45 | LE | Regime | .006462 | .1610 | .3649 | .006571 |
| 45 | AI | Regime | .006373 | .1502 | .3378 | .006607 |
| 60 | LE | Regime | .006559 | .1686 | .3649 | .006473 |
| 60 | AI | Regime | .006409 | .1557 | .3378 | .006485 |
| 30 | LE | Full | .006511 | .2442 | .7432 | .005076 |
| 30 | AI | Full | .007167 | .3638 | .8378 | .005531 |
| 45 | LE | Full | .006516 | .2484 | .7432 | .005100 |
| 45 | AI | Full | .007105 | .3625 | .8378 | .005367 |
| 60 | LE | Full | .006592 | .2479 | .7568 | .005023 |
| 60 | AI | Full | .007074 | .3439 | .8243 | .005356 |

> **Note.** The common 90th-percentile threshold is 0.0157717; each tail contains 74 days.
