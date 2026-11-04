Title:

Certified uncertainty for drifting digital sensors between sparse reference checks using staleness stratified conformal prediction

Abstract:

Field-deployed digital sensors drift between sparse, scheduled reference checks, yet the expanded uncertainty of every reported value must stay trustworthy. Model-based (GUM/Kalman) evaluations are only as good as their drift model, and online conformal methods assume continuous or random feedback, whereas real checks come on a schedule, at maximal staleness and against an uncertain reference. We propose SPARC, a staleness-aware conformal framework. A calibration-state digital twin identifies a zero/span drift budget from as-found and as-left residuals, with staleness treated as an explicit influence quantity. Stratified adaptive conformal recursions turn this budget into expanded uncertainties with an audited coverage factor, which are published as D-SI records. We prove a distribution-free long-run coverage bound at audited checks, state when this coverage transfers to unreferenced values, and prove that the budget is identifiable and that reference-referred intervals are conservative. In 1200 synthetic deployments SPARC reduced the mean as-found coverage deviation from 1.28 × 10⁻² with adaptive conformal inference to 1.5 × 10⁻³ and cut the interval score by 3.4–6.5 %. On one year of public metal-oxide multisensor data it gave the most accurate coverage of unreferenced values (mean deviation 1.16 × 10⁻²) without a significant loss of efficiency, and all 34 620 D-SI records validated against the official schemas.

Keywords:

measurement uncertainty; conformal prediction; sensor drift; in-situ calibration; D-SI; digital twin; low-cost sensors
