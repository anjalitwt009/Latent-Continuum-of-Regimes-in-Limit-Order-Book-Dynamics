# Continuous-state validity and selected-timescale predictive performance

## Panel A: State validity and persistence

| Duration | Windows | PC1<br>fraction | Corr.<br>VSTOXX | Pearson<br>next RV | Spearman<br>next RV | Lag-1 AC /<br>decay HL |
| --- | --- | --- | --- | --- | --- | --- |
| 30 s | 837,890 | 0.2741 | 0.4997 | 0.3828 | 0.2955 | 0.9391 / 11.03 |
| 45 s | 559,261 | 0.2855 | 0.5141 | 0.4145 | 0.3439 | 0.9515 / 13.93 |
| 60 s | 419,493 | 0.2922 | 0.5221 | 0.4332 | 0.3775 | 0.9570 / 15.78 |

## Panel B: Five-window-half-life predictive performance

| Duration | Best<br>$h$ | Persist / +slow / +fast<br>$R^2$ | Slow $\Delta R^2$<br>(95% interval) | Fast<br>$\Delta R^2$ |
| --- | --- | --- | --- | --- |
| 30 s | 5 | 0.4273 / 0.4601 / 0.4694 | 0.0328 [0.0282, 0.0378] | 0.0092 |
| 45 s | 5 | 0.5225 / 0.5470 / 0.5535 | 0.0244 [0.0213, 0.0278] | 0.0066 |
| 60 s | 5 | 0.5871 / 0.6060 / 0.6103 | 0.0188 [0.0165, 0.0213] | 0.0044 |

> **Note.** M0 is the persistence model, M1 adds the slow stress dial, and M2 adds the fast residual and velocity. Predictive results are pooled purged walk-forward estimates with a one-day embargo; standardisation, the PCA axis, and its VSTOXX orientation are refitted on each training fold. $h$ is measured in windows.
