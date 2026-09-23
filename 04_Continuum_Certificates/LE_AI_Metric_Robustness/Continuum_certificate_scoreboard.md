# Table 05: Continuum evidence, certificate scoreboard, and metric robustness.

**Source label:** `tab:continuum_scoreboard`

| Certificate or measure | Acceptance rule | 30 s | 45 s | 60 s |
| --- | --- | --- | --- | --- |
| Clean windows | - | 837,890 | 559,261 | 419,493 |
| Raw PC1 variance (%) | - | 83.66 | 84.41 | 85.27 |
| $\vert \mathrm{corr}(\mathrm{PC1},\mathrm{VSTOXX})\vert $ | External validation | 0.500 | 0.514 | 0.522 |
| C1: Effective dimension | $d_{\mathrm{eff}}<3$ | 1.4109 (pass) | 1.3887 (pass) | 1.3634 (pass) |
| C2: PC1 unimodality | dip $<0.01$ | 0.00080 (pass) | 0.00070 (pass) | 0.00096 (pass) |
| C3: $H_0$ connectedness | death ratio $>3$ | 43.579 (pass) | 26.084 (pass) | 25.741 (pass) |
| C4: No persistent $H_1$ loop | ratio $<0.15$ or rank $p\geq0.05$ | 0.0209 (pass) | 0.0568 (pass) | 0.0437 (pass) |
| C5: Spectral gap, AI/LE | each $<0.30$ | 0.176/0.227 (pass) | 0.139/0.200 (pass) | 0.188/0.187 (pass) |
| C6: Bootstrap peak $K$, AI/LE | each $K\leq3$; ARI drop $>0.05$ | 2/2 (pass) | 4/2 (AI fail) | 3/2 (pass) |
| AI/LE vote | at least 5 of 6 | 6/6; 6/6 | 5/6; 6/6 | 6/6; 6/6 |
| Joint verdict | both metrics confirm | Confirmed | Confirmed, qualified | Confirmed |

> **Note.** Paired entries report AI/LE values. The sole pooled miss is the 45-second AI bootstrap certificate; the pre-specified five-of-six voting rule retains the continuum verdict.
