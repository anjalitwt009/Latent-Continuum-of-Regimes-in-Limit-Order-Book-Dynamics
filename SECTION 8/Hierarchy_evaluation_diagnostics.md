# Hierarchy evaluation and silhouette diagnostics

Silhouette, Davies-Bouldin, and Hopkins values are diagnostics rather than criteria for selecting discrete regimes. AC denotes autocorrelation.

| Duration (s) | Metric | Macro-F1 | Silhouette | Davies-Bouldin | Hopkins | Lag-1 AC | Absolute dial-VSTOXX correlation |
|---:|---|---:|---:|---:|---:|---:|---:|
| 30 | LE | 0.512 | 0.174 | 2.156 | 0.980 | 0.939 | 0.500 |
| 30 | AI | 0.444 | 0.035 | 2.744 | 0.971 | 0.939 | 0.500 |
| 45 | LE | 0.410 | 0.165 | 2.167 | 0.960 | 0.951 | 0.514 |
| 45 | AI | 0.461 | 0.024 | 2.712 | 0.956 | 0.951 | 0.514 |
| 60 | LE | 0.417 | 0.159 | 2.113 | 0.958 | 0.957 | 0.522 |
| 60 | AI | 0.469 | 0.027 | 2.691 | 0.962 | 0.957 | 0.522 |