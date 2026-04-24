# A Social Media-Driven Occupational Analysis

## What This Project Does

Compares how the U.S. government classifies computing jobs (SOC/O\*NET taxonomy) against how those jobs are actually described on LinkedIn — and measures the gap created by AI-driven role fragmentation.

## Scope

Analysis is restricted to **Computer & Mathematical Occupations (SOC 15-xxxx)** plus emerging tech roles (AI Engineer, MLOps, Prompt Engineer, etc.) that do not yet have official SOC codes.

## Four Objectives

**O1 — Gap Analysis**
Which self-reported LinkedIn titles fall outside the official taxonomy? Which AI-era roles are most unclassified?

**O2 — Longitudinal Trends**
How has the share of AI/ML-related job titles changed over time in tech postings?

**O3 — AI Impact**
Using O\*NET Technology Skills data, which computing occupations have the highest density of AI/ML tools — and how is that changing?

**O4 — Normalization & Clustering**
How accurately can a hybrid rule + semantic (JobBERT) model map diverse LinkedIn titles to official SOC codes? What natural clusters emerge?

## Data Required

| Dataset | Source |
|---|---|
| O\*NET 30.2 (Occupation Data, Alternate Titles, Technology Skills) | [O\*NET Online](https://www.onetcenter.org/database.html) |
| BLS OEWS May 2024 | [BLS.gov](https://www.bls.gov/oes/tables.htm) |
| LinkedIn Job Postings | [Kaggle](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings) |

Place datasets in `Raw/` and `Processed/` as expected by the notebook.

## How to Run

Open `DASC5131_Group2_Project_FINAL.ipynb` and run all cells sequentially.
