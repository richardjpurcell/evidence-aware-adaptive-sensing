# Evidence-Aware Adaptive Sensing

Independent evaluation of evidence-aware diagnostics and adaptive sensing
under incomplete, delayed, and unreliable information flow.

## Research hypotheses

### H1 — Diagnostic advantage

Does explicit representation of observation arrival, maintained belief,
and evidence quality identify consequential estimation failures beyond
strong established monitoring diagnostics?

### H2 — Adaptive decision advantage

Does using those diagnostic distinctions to guide sensing improve
independently assessed estimates under comparable sensing budgets?

## Research approach

This project extends the research questions arising from the PhD thesis:

*Adaptive Wildfire Sensing Under Impaired Information Flow:
A Representation-Centred Methodology* (Purcell, 2026).

The project will evaluate estimation errors against independent
reference measurements and compare its methods against established approaches.

The initial candidate dataset is the UCI Beijing Multi-Site Air Quality
dataset. Its suitability must be established through a documented
qualification study before experimental claims are made.

H1 will be evaluated first. H2 is conditional on the H1 findings.

## Development environment

Python 3.12 using Conda.

Create the environment:

    conda env create -f environment.yml

Activate it:

    conda activate evidence-sensing

## Status

Initial repository setup. No experimental results yet.
