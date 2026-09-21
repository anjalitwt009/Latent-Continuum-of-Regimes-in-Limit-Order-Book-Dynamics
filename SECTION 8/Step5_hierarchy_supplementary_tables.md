# Step 5 — Discrete regimes and hierarchical transfer: supplementary tables

Supplementary tables for the hierarchical level-set analysis (paper Section 8.5).
ΔR² is the incremental out-of-sample R² over a persistence baseline. Purged
estimates refit the full pipeline under a one-day embargo. Minus signs denote
negative values.

## Cross-duration headline

| Duration | Min axis cosine | Pooled macro ΔR² LE / AI | Mean cross-representation ARI | Continuous predictive ΔR² |
|---|---:|---:|---:|---:|
| 30 s | 0.859 | +0.029 / +0.043 | 0.445 | 0.034 |
| 45 s | 0.866 | +0.014 / +0.043 | 0.489 | 0.025 |
| 60 s | 0.872 | +0.005 / +0.032 | 0.508 | 0.019 |

## Table A — Hierarchy complexity and transfer at 30 seconds

Single chronological-halves split. ΔR² is combined minus persistence OOS R².

| Metric | Tier | Bands | Train η² | OOS ΔR² | Stability ARI | Median leaf |
|---|---|---:|---:|---:|---:|---:|
| AI | MACRO | 4 | 0.061 | 0.011 | 0.880 | 215,082 |
| AI | MACRO-SUB | 8 | 0.157 | −0.031 | 0.792 | 102,275 |
| AI | MICRO | 16 | 0.172 | −0.041 | 0.671 | 48,609 |
| AI | MICRO-SUB | 31 | 0.232 | −0.051 | 0.459 | 24,927 |
| LE | MACRO | 4 | 0.086 | 0.039 | 0.897 | 189,359 |
| LE | MACRO-SUB | 8 | 0.205 | −0.043 | 0.722 | 74,987 |
| LE | MICRO | 16 | 0.238 | −0.084 | 0.711 | 29,827 |
| LE | MICRO-SUB | 27 | 0.263 | −0.081 | 0.626 | 16,876 |

## Table B — Purged pooled walk-forward hierarchy performance

One-day embargo; 95% day-block bootstrap intervals. This is the primary
granularity-transfer table.

| Duration | Metric | Tier | Bands | ΔR² | 95% interval | Sig. |
|---:|---|---|---:|---:|---|---|
| 30 | LE | MACRO | 4 | 0.0292 | [0.0239, 0.0350] | + |
| 30 | LE | MACRO-SUB | 8 | 0.0116 | [0.0067, 0.0166] | + |
| 30 | LE | MICRO | 16 | 0.0093 | [0.0030, 0.0159] | + |
| 30 | LE | MICRO-SUB | 27 | −0.0012 | [−0.0069, 0.0047] | ns |
| 30 | AI | MACRO | 4 | 0.0432 | [0.0396, 0.0470] | + |
| 30 | AI | MACRO-SUB | 8 | 0.0184 | [0.0147, 0.0229] | + |
| 30 | AI | MICRO | 16 | 0.0174 | [0.0132, 0.0220] | + |
| 30 | AI | MICRO-SUB | 31 | 0.0102 | [0.0060, 0.0143] | + |
| 45 | LE | MACRO | 4 | 0.0135 | [0.0092, 0.0177] | + |
| 45 | LE | MACRO-SUB | 8 | 0.0270 | [0.0229, 0.0315] | + |
| 45 | LE | MICRO | 16 | 0.0156 | [0.0106, 0.0207] | + |
| 45 | LE | MICRO-SUB | 28 | 0.0020 | [−0.0026, 0.0063] | ns |
| 45 | AI | MACRO | 4 | 0.0426 | [0.0396, 0.0456] | + |
| 45 | AI | MACRO-SUB | 8 | 0.0240 | [0.0193, 0.0292] | + |
| 45 | AI | MICRO | 16 | 0.0201 | [0.0150, 0.0248] | + |
| 45 | AI | MICRO-SUB | 31 | 0.0053 | [0.0010, 0.0097] | + |
| 60 | LE | MACRO | 4 | 0.0053 | [0.0020, 0.0086] | + |
| 60 | LE | MACRO-SUB | 8 | 0.0228 | [0.0197, 0.0260] | + |
| 60 | LE | MICRO | 14 | 0.0209 | [0.0175, 0.0246] | + |
| 60 | LE | MICRO-SUB | 25 | 0.0048 | [0.0012, 0.0083] | + |
| 60 | AI | MACRO | 4 | 0.0318 | [0.0286, 0.0349] | + |
| 60 | AI | MACRO-SUB | 8 | 0.0182 | [0.0142, 0.0223] | + |
| 60 | AI | MICRO | 16 | 0.0163 | [0.0124, 0.0205] | + |
| 60 | AI | MICRO-SUB | 31 | 0.0057 | [0.0023, 0.0090] | + |

## Table C — Purged versus non-purged macro transfer

Purged estimates refit the complete pipeline and impose a one-day embargo.
Non-purged estimates reuse the single-fit hierarchy, so the columns are a
sensitivity comparison rather than a controlled difference. "ns" denotes not
significant.

| Duration | Metric | Fold | Purged ΔR² | Non-purged ΔR² |
|---:|---|---|---|---:|
| 30 | LE | wf_2023 | 0.0059 | 0.0500 |
| 30 | LE | wf_2024 | 0.0527 | 0.0521 |
| 30 | LE | wf_2025 | 0.0450 | 0.0454 |
| 30 | AI | wf_2023 | 0.0605 | 0.0841 |
| 30 | AI | wf_2024 | 0.0467 | 0.0427 |
| 30 | AI | wf_2025 | 0.0134 ns | 0.0118 |
| 45 | LE | wf_2023 | 0.0036 | 0.0462 |
| 45 | LE | wf_2024 | 0.0333 | 0.0309 |
| 45 | LE | wf_2025 | 0.0124 ns | 0.0143 |
| 45 | AI | wf_2023 | 0.0590 | 0.0771 |
| 45 | AI | wf_2024 | 0.0510 | 0.0501 |
| 45 | AI | wf_2025 | 0.0096 ns | 0.0105 |
| 60 | LE | wf_2023 | 0.0044 | 0.0368 |
| 60 | LE | wf_2024 | 0.0185 | 0.0118 |
| 60 | LE | wf_2025 | −0.0043 ns | −0.0024 |
| 60 | AI | wf_2023 | 0.0531 | 0.0633 |
| 60 | AI | wf_2024 | 0.0364 | 0.0359 |
| 60 | AI | wf_2025 | −0.0059 ns | −0.0043 |

## Table D — Frozen-band out-of-sample transfer

Entries are test economic NMI; hold requires test/train NMI ≥ 0.60. The
2022→2023 split fails under both metrics at every duration.

| Duration | Train→test | AI test NMI | LE test NMI | AI / LE hold |
|---:|---|---:|---:|---|
| 30 | 2022–23→2024–25 | 0.0844 | 0.0767 | Yes / Yes |
| 30 | 2022–24→2025 | 0.0409 | 0.0662 | Yes / Yes |
| 30 | 2022→2023 | 0.0055 | 0.0144 | No / No |
| 30 | 2022–23→2024 | 0.0528 | 0.0381 | Yes / Yes |
| 45 | 2022–23→2024–25 | 0.1144 | 0.1072 | Yes / Yes |
| 45 | 2022–24→2025 | 0.0618 | 0.0734 | Yes / Yes |
| 45 | 2022→2023 | 0.0147 | 0.0231 | No / No |
| 45 | 2022–23→2024 | 0.0747 | 0.0666 | Yes / Yes |
| 60 | 2022–23→2024–25 | 0.1340 | 0.1144 | Yes / Yes |
| 60 | 2022–24→2025 | 0.0717 | 0.0759 | Yes / Yes |
| 60 | 2022→2023 | 0.0238 | 0.0297 | No / No |
| 60 | 2022–23→2024 | 0.0899 | 0.0765 | Yes / Yes |

## Table E — Cross-representation agreement

Continuous-AI and Continuous-LE have ARI 1.000 by construction; no independent
AI dial is stored.

| Duration | Mean off-diag. ARI | Discrete LE–AI | Discrete LE–continuous | Discrete AI–continuous | Continuous LE–AI |
|---:|---:|---:|---:|---:|---:|
| 30 | 0.4447 | 0.3426 | 0.3123 | 0.3504 | 1.000 |
| 45 | 0.4894 | 0.3471 | 0.3720 | 0.4227 | 1.000 |
| 60 | 0.5076 | 0.3572 | 0.3899 | 0.4543 | 1.000 |

## Table F — Axis stability and migrating levels

Pair rows report adjacent-year PC1 cosine; year rows report stress level and
VSTOXX.

| Duration | Pair or year | Axis cosine | Stress level | VSTOXX |
|---:|---|---:|---:|---:|
| 30 | 2022→23 | 0.8586 | — | — |
| 30 | 2023→24 | 0.9519 | — | — |
| 30 | 2024→25 | 0.9288 | — | — |
| 30 | 2022 | — | 2.6427 | 26.89 |
| 30 | 2023 | — | −2.2153 | 17.99 |
| 30 | 2024 | — | −1.3735 | 15.99 |
| 30 | 2025 | — | 0.9354 | 18.84 |
| 45 | 2022→23 | 0.8660 | — | — |
| 45 | 2023→24 | 0.9584 | — | — |
| 45 | 2024→25 | 0.9212 | — | — |
| 45 | 2022 | — | 2.8033 | 26.89 |
| 45 | 2023 | — | −2.4444 | 17.98 |
| 45 | 2024 | — | −1.4534 | 15.99 |
| 45 | 2025 | — | 1.0866 | 18.84 |
| 60 | 2022→23 | 0.8724 | — | — |
| 60 | 2023→24 | 0.9647 | — | — |
| 60 | 2024→25 | 0.9181 | — | — |
| 60 | 2022 | — | 2.8960 | 26.89 |
| 60 | 2023 | — | −2.5879 | 17.98 |
| 60 | 2024 | — | −1.4996 | 15.99 |
| 60 | 2025 | — | 1.1855 | 18.84 |

## Appendix A — Evaluation and silhouette diagnostics

Silhouette, Davies–Bouldin, and Hopkins values are diagnostics rather than
criteria for selecting discrete regimes. AC denotes autocorrelation.

| Duration | Metric | Macro-F1 | Silhouette | Davies–Bouldin | Hopkins | Lag-1 AC | \|dial–VSTOXX\| |
|---:|---|---:|---:|---:|---:|---:|---:|
| 30 | LE | 0.512 | 0.174 | 2.156 | 0.980 | 0.939 | 0.500 |
| 30 | AI | 0.444 | 0.035 | 2.744 | 0.971 | 0.939 | 0.500 |
| 45 | LE | 0.410 | 0.165 | 2.167 | 0.960 | 0.951 | 0.514 |
| 45 | AI | 0.461 | 0.024 | 2.712 | 0.956 | 0.951 | 0.514 |
| 60 | LE | 0.417 | 0.159 | 2.113 | 0.958 | 0.957 | 0.522 |
| 60 | AI | 0.469 | 0.027 | 2.691 | 0.962 | 0.957 | 0.522 |

## Appendix B — Predictive coincidence

Incremental R² is the combined-model increment over persistence. The peak
lead-lag association occurs at one window for every duration.

| Duration | Persistence R² | Dial-only R² | Combined R² | ΔR² | Directional accuracy | Peak lag / corr. |
|---:|---:|---:|---:|---:|---:|---|
| 30 | 0.4066 | 0.1920 | 0.4404 | 0.0338 | 0.6118 | 1 / 0.3846 |
| 45 | 0.5051 | 0.2137 | 0.5304 | 0.0253 | 0.6054 | 1 / 0.4168 |
| 60 | 0.5717 | 0.2241 | 0.5912 | 0.0195 | 0.5949 | 1 / 0.4358 |

## Appendix C — Cross-duration band stability

ARI(E,A) measures agreement between the designated hierarchy representation and
the alternative comparator. Frozen OOS transfer fails the joint all-scheme
criterion under both metrics.

| Duration | ARI(E,A) AI | ARI(E,A) LE | Stability AI | Stability LE | Frozen OOS holds AI / LE |
|---:|---:|---:|---:|---:|---|
| 30 | 0.128 | 0.143 | 0.312 | 0.888 | No / No |
| 45 | 0.194 | 0.264 | 0.333 | 0.871 | No / No |
| 60 | 0.240 | 0.324 | 0.319 | 0.779 | No / No |
