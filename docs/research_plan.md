# Research Plan

Version: 0.1
Status: Initial experimental design

## 1. Research objective

Determine whether explicit representation of observation
arrival, evidence quality, and maintained belief provides
measurable advantages over established monitoring methods.

The research proceeds through two separately evaluated
hypotheses.

## 2. H1 — Diagnostic advantage

Does explicit evidence/arrival/belief representation identify
consequential estimation failures beyond strong established
monitoring diagnostics?

The primary comparison will hold the estimator, available
observations, and evaluation periods constant.

Candidate comparators include:
- Observation freshness and age
- Predictive uncertainty
- Innovation and residual diagnostics
- A tuned combination of established diagnostics

The principal outcome will be detection of consequential
estimation errors against withheld reference measurements,
at a fixed false-alarm budget.

## 3. H2 — Adaptive decision advantage

Does using those diagnostic distinctions to guide sensing
improve independently assessed estimates under comparable
sensing budgets?

H2 is conditional on an informative H1 result.

Candidate policies include:
- Feasible reference selection
- Uncertainty-seeking selection
- Information-value-based selection
- Evidence-health-aware selection

Policies will receive matched observation budgets and
be evaluated against independent reference measurements.

## 4. Initial monitored quantity

Hourly ambient PM2.5 concentration.

Candidate dataset:
UCI Beijing Multi-Site Air Quality (2013-2017).

The dataset has not yet been qualified for this study.

## 5. Independent evaluation

Reference measurements must be unavailable to the monitor
at decision time.

The initial design will partition stations into eligible
sensing locations and withheld reference locations.

Chronological training, validation, and test periods will
be defined after examining the dataset.

## 6. Information-flow impairment

The dataset provides historical measurements, not a complete
record of communication and arrival events.

Loss, delay, and additional measurement corruption will
therefore be introduced as controlled experimental conditions.

Simulated arrival times must not be presented as historical
communication evidence.

## 7. Scientific boundaries

Internal uncertainty is not independent estimation accuracy.

H1 diagnostic improvement does not establish H2 decision
improvement.

Retrospective station selection supports only actions for
which historical measurements are available.

Results will be interpreted within those limitations.

## 8. Research sequence

D00: Dataset acquisition and qualification
D01: Fixed estimator baseline
D02: Established diagnostic baselines
D03: Evidence-aware diagnostics and H1 evaluation
Gate: Assess whether H1 warrants further investigation
D04: Budget-matched adaptive sensing and H2 evaluation
D05: Robustness, replication, and transfer

## 9. Next decision

Qualify the Beijing dataset before finalizing the
experimental design or downloading additional datasets.
