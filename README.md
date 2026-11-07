Title:

Certified uncertainty for drifting digital sensors between sparse reference checks using staleness stratified conformal prediction

Abstract:

Field-deployed digital sensors drift between sparse, scheduled reference checks, yet the expanded uncertainty of every reported value must remain trustworthy. Model-based evaluations following the Guide to the Expression of Uncertainty in Measurement (GUM) depend on an assumed drift model, while online conformal prediction assumes continuous or random feedback. We propose SPARC, a staleness-aware conformal method for in-service uncertainty. A calibration-state digital twin identifies a zero/span drift uncertainty budget from as-found and as-left check residuals, with staleness treated as an explicit influence quantity. Two adaptive conformal recursions audit the as-found and as-left checks separately and convert the budget into expanded uncertainties with an audited coverage factor, published as machine-readable records. We prove a distribution-free coverage bound at the audited checks, state when coverage transfers to values between checks, and prove that the budget is identifiable. In 1200 synthetic deployments, SPARC reduced the mean as-found coverage deviation from 1.28 × 10⁻² with adaptive conformal inference to 1.5 × 10⁻³ and lowered the interval score by 3.4 to 6.5 %. On three public field data sets with metal-oxide, electrochemical and optical sensors (36 deployments), it gave the most accurate as-found audit of all baselines and the most or second most accurate coverage of unreferenced values, without a significant loss of efficiency.

Keywords:

measurement uncertainty; conformal prediction; sensor drift; in-situ calibration; calibration interval; digital system of units; digital twin
