# Socio-Emotional Conversational Framework

This repository provides a reproducible data mining pipeline for socio-emotional analysis in conversational interactions, as described in the associated research article.

---

## Features
- Inter-annotator agreement (Cohen’s κ, Krippendorff’s α)
- Multi-class emotion classification (BETO-light)
- Session-based data splitting (leakage prevention)
- Bootstrap confidence intervals (95%)
- Confusion matrix and error analysis
- Supplementary material (predictions + probabilities)

---

## Reproducibility
All experiments are executed with a fixed random seed (**SEED = 37**) and controlled configuration to ensure replicability of results.

---

## Dataset
A sanitized and anonymized dataset is included.
Sensitive information has been removed or transformed to reduce the risk of re-identification.  
The full dataset is not publicly released due to privacy and ethical constraints.

---

## Privacy Notice
This repository contains an anonymized version of conversational data.
The dataset has been processed following data minimization and anonymization principles.  
No direct or indirect identifiers are included.

---

## Citation
If you use this repository, please cite:

**De León Vargas, C. (2026).**  
*A Reproducible Data Mining Framework for Socio-Emotional Analysis in Conversational Interactions.*

---

## Associated Article
This repository accompanies the research article:

**"A Reproducible Data Mining Framework for Socio-Emotional Analysis in Conversational Interactions"**
Submitted to *International Journal of Combinatorial Optimization Problems and Informatics (IJCOPI)*.

---

## Repository Structure
data/ -> anonymized dataset
scripts/ -> reproducible pipeline
results/ -> outputs, metrics, and supplementary material

---

## Notes
This repository is intended to support reproducibility, traceability, and auditability in socio-emotional conversational analysis.
The provided materials allow replication of the experimental pipeline without exposing sensitive conversational data.
