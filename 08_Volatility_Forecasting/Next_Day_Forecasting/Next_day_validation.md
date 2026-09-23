# Table 13: Next-day permutation and Mincer-Zarnowitz validation summary.

**Source label:** `tab:nextday_validation`

| Duration | Metric | Full<br>$R^2$ | Permuted<br>$R^2$ | Drop | Survives | MZ<br>$a$ | MZ<br>$b$ | Joint<br>$p$ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 30 s | LE | 0.8374 | 0.8288 | $+0.0087$ | Yes | 0.00129 | 0.8866 | $<0.001$ |
| 30 s | AI | 0.8197 | 0.8280 | $-0.0083$ | No | 0.00205 | 0.8861 | $<0.001$ |
| 45 s | LE | 0.8375 | 0.8307 | $+0.0068$ | Yes | 0.00135 | 0.8868 | $<0.001$ |
| 45 s | AI | 0.8191 | 0.8297 | $-0.0106$ | No | 0.00215 | 0.8777 | $<0.001$ |
| 60 s | LE | 0.8342 | 0.8305 | $+0.0037$ | Yes | 0.00144 | 0.8787 | $<0.001$ |
| 60 s | AI | 0.8211 | 0.8314 | $-0.0102$ | No | 0.00205 | 0.8798 | $<0.001$ |

> **Note.** Drop is full-sample $R^2$ minus mean $R^2$ after permuting the regime representation within the training procedure. "Survives" indicates a positive permutation drop. MZ reports the Mincer-Zarnowitz intercept $a$, slope $b$, and joint calibration-test $p$-value.
