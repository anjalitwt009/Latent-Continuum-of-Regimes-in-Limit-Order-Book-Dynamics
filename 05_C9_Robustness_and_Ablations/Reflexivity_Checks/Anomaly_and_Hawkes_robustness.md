# Anomaly-treatment materiality and Hawkes robustness.

**Source label:** `tab:anomaly_hawkes_robustness`

| Duration | LE<br>spread | AI<br>spread | Mean<br>$n$ | $\mathrm{corr}$<br>$(n,\mathrm{VSTOXX})$ | LE $n$<br>spread | AI $n$<br>spread | Verdict |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 30 s | 0.0298 | 0.0380 | 0.4417 | 0.1631 | 0.0318 | 0.0138 | Pass / negative |
| 45 s | 0.0300 | 0.0272 | 0.4419 | 0.1627 | 0.0251 | 0.0161 | Pass / negative |
| 60 s | 0.0230 | 0.0224 | 0.4418 | 0.1634 | 0.0232 | 0.0168 | Pass / negative |

> **Note.** The anomaly-treatment materiality gate is an economic-NMI spread below 0.05. The reflexivity-flat gates are a regime-$n$ spread below 0.10 and $\vert \mathrm{corr}(n,\mathrm{VSTOXX})\vert <0.20$. "Pass / negative" denotes a materiality pass and a negative result for separable Hawkes reflexivity.
