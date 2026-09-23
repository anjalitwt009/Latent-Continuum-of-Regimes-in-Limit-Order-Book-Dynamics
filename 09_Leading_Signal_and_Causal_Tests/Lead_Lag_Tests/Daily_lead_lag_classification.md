# Daily lead-lag classification

Each entry reports peak lag in days, peak correlation, and the corrected
classification. The classifications, rather than the sign of the lag alone,
are the canonical interpretation.

| Pair | 30 s LE | 30 s AI | 45 s LE | 45 s AI | 60 s LE | 60 s AI |
| --- | --- | --- | --- | --- | --- | --- |
| Stress level vs RV | 0 / 0.5655 / coincident | 0 / 0.5423 / coincident | 0 / 0.5637 / coincident | 0 / 0.5385 / coincident | 0 / 0.5622 / coincident | 0 / 0.5355 / coincident |
| Stress level vs VSTOXX | 0 / 0.5596 / coincident | 0 / 0.5350 / coincident | 0 / 0.5679 / coincident | 0 / 0.5413 / coincident | 0 / 0.5725 / coincident | 0 / 0.5442 / coincident |
| Velocity vs RV | 0 / 0.1980 / coincident | 0 / 0.1973 / coincident | 0 / 0.2047 / coincident | 0 / 0.2037 / coincident | 0 / 0.2089 / coincident | 0 / 0.2069 / coincident |
| Velocity vs VSTOXX | −6 / −0.1051 / lags | −6 / −0.1111 / lags | −6 / −0.1079 / lags | −6 / −0.1133 / lags | −6 / −0.1096 / lags | −6 / −0.1144 / lags |
| Acceleration vs RV | −1 / −0.2306 / coincident | −1 / −0.2245 / coincident | −1 / −0.2416 / coincident | −1 / −0.2352 / coincident | −1 / −0.2482 / coincident | −1 / −0.2408 / coincident |
| Acceleration vs VSTOXX | −1 / −0.0902 / coincident | −1 / −0.0925 / coincident | −1 / −0.0922 / coincident | −1 / −0.0932 / coincident | −1 / −0.0926 / coincident | −1 / −0.0924 / coincident |

The daily lead-lag module therefore identifies no leading relationship. The
separate Granger associations are bidirectional, and the chronological OOS
test remains the decisive causal arbiter.
