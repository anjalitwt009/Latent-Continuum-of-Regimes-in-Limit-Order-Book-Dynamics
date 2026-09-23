# Comparison of Log-Euclidean and affine-invariant covariance geometry.

**Source label:** `tab:app_geometry_comparison`

| Property | Log-Euclidean (LE) | Affine-invariant (AI) |
| --- | --- | --- |
| Distance | $\|\log\Sigma_t-\log\Sigma_u\|_F$; Equation `eq:method_dle` | $\|\log(\Sigma_t^{-1/2}\Sigma_u\Sigma_t^{-1/2})\|_F =\{\sum_j\log^2\gamma_{j,t,u}\}^{1/2}$; Equation `eq:method_dai` |
| Mean | $\bar\Sigma_{\mathrm{LE}} =\exp\{n^{-1}\sum_i\log\Sigma_i\}$; closed form | Karcher/Fréchet mean $\arg\min_M\sum_i d_{\mathrm{AI}}^2(M,\Sigma_i)$; iterative; Equations `eq:method_karcher_objective`– Equation `eq:method_karcher_update` |
| Tangent coordinate | $\phi(\Sigma)=\operatorname{vech}_{\sqrt2}(\log\Sigma) \in\mathbb R^{120}$, based at the identity | $Z_t^{(\mathrm{AI})} =\operatorname{vech}_{\sqrt2} \{\log(M^{-1/2}\Sigma_tM^{-1/2})\}\in\mathbb R^{120}$, based at Karcher mean $M$ |
| Scale/unit sensitivity | Sensitive to rescaling and linear recombination of the input variables | Invariant to nonsingular rescaling and linear recombination |
| Congruence invariance | Not generally congruence invariant | Congruence invariant; means and centroids are equivariant |
| Numerical cost | Lower: one matrix logarithm per state followed by Euclidean operations | Higher: generalised eigen decompositions for distances and iterative Karcher updates, performed in double precision for metric comparisons |
| Graded perturbation | None | $10^{-6}$ to $3\times10^{-6}$ times the mean diagonal for the 45 and 60-second paths only; none at 30 seconds |
| Role | Exact-isometry operational tangent representation and robustness benchmark | Primary metric for headline, metric-sensitive analysis |
| Where used | Operational continuum coordinate, tangent-space calculations, PCA, and Log-Euclidean hierarchy and robustness checks | Primary distances, means, certificates, and hierarchy; separately estimated Karcher-centred principal-geodesic coordinate $s_t^{(\mathrm{AI})}$ where stated |
