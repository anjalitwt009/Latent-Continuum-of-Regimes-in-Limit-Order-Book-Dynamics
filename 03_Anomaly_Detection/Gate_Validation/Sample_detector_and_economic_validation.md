# Native-grid sample, detector, and economic validation. The economic lift compares the realised-volatility tail probability in the highest combined-score decile with its unconditional 10% rate.

|  | 30 s | 45 s | 60 s |
| --- | --- | --- | --- |
| Unmasked windows | 1,038,115 | 692,481 | 519,121 |
| Canonical clean windows | 837,890 | 559,261 | 419,493 |
| Retained fraction (%) | 80.71 | 80.76 | 80.81 |
| Matrix-profile own-flag AUROC | 0.9834 | 0.9848 | 0.9860 |
| Matrix-profile Cohen's $d$ | 1.930 | 1.964 | 1.996 |
| Isolation Forest Cohen's $d$ | 3.674 | 3.754 | 3.819 |
| MDI-Isolation Forest Jaccard | 0.0249 | 0.0279 | 0.0326 |
| Velocity-gate Cohen's $d$ | $-0.09$ | 0.02 | 0.16 |
| Decile-contemporaneous-volatility Spearman correlation | 0.952 | 0.915 | 0.964 |
| Decile-future-volatility Spearman correlation | 0.988 | 0.952 | 0.988 |
| Decile-VSTOXX Spearman correlation | 0.733 | 0.733 | 0.867 |
| Top-decile volatility-tail probability (%) | 26.60 | 25.57 | 27.14 |
| Top-decile tail lift | 2.660 | 2.557 | 2.714 |
| Combined-score proxy AUROC | 0.679 | 0.670 | 0.688 |
| Proxy gate precision | 0.0346 | 0.0343 | 0.0347 |
| Proxy gate recall | 0.3263 | 0.3236 | 0.3285 |

> **Note.** Proxy metrics use an intentionally incomplete volatility/VSTOXX label and are reported only as diagnostics.
