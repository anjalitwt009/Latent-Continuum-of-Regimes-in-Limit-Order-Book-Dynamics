# Continuous-state validity and best-timescale predictive performance.

## Panel A: State validity and persistence

| Duration | Windows | PC1<br>fraction | Corr.<br>VSTOXX | Pearson<br>next RV | Spearman<br>next RV | Lag-1 AC /<br>decay HL |
| --- | --- | --- | --- | --- | --- | --- |
| 30 s | 837,890 | 0.2741 | 0.4997 | 0.3828 | 0.2955 | 0.9391 / 11.03 |
| 45 s | 559,261 | 0.2855 | 0.5141 | 0.4145 | 0.3439 | 0.9515 / 13.93 |
| 60 s | 419,493 | 0.2922 | 0.5221 | 0.4332 | 0.3775 | 0.9570 / 15.78 |

## Panel B: Best-half-life predictive performance

| Duration | Best<br>$h$ | Persist / +slow / +fast<br>$R^2$ | Slow $\Delta R^2$<br>(95% interval) | Fast<br>$\Delta R^2$ |
| --- | --- | --- | --- | --- |
| 30 s | 5 | 0.4273 / 0.4590 / 0.4659 | 0.0317 [0.0272, 0.0365] | 0.0069 |
| 45 s | 5 | 0.5225 / 0.5462 / 0.5508 | 0.0237 [0.0206, 0.0270] | 0.0046 |
| 60 s | 5 | 0.5871 / 0.6054 / 0.6083 | 0.0183 [0.0160, 0.0207] | 0.0029 |

> **Note.** M0 is the persistence model, M1 adds the slow stress dial, and M2 adds the fast residual and velocity. Predictive results are pooled purged walk-forward estimates with a one-day embargo; $h$ is measured in windows.
