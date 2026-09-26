# Practical Statistics for Data Scientists — Code Reproduction & Theoretical Deep-Dive

Individual assignment (Enrichment for Machine Learning and Deep Learning
Classes): reproducing the code from every chapter of *Practical Statistics
for Data Scientists* (Peter Bruce, Andrew Bruce & Peter Gedeck, O'Reilly,
2nd ed.), summarizing each chapter's content, and explaining the underlying
statistical theory in my own words.

**Reference book:** [Practical Statistics for Data Scientists (O'Reilly)](https://www.oreilly.com/library/view/practical-statistics-for/9781492072935/)

## Repository structure

Each chapter has its own folder containing:
- a Jupyter notebook reproducing and summarizing the chapter's code,
- a short README explaining what the chapter covers,
- the datasets used (from the book's official companion repository) and
  saved chart outputs.

| Chapter | Topic | Status |
|---|---|---|
| 1 | [Exploratory Data Analysis](Chapter1_Exploratory_Data_Analysis/) | ✅ Done |
| 2 | Data and Sampling Distributions | ⏳ In progress |
| 3 | Statistical Experiments and Significance Testing | ⏳ In progress |
| 4 | Regression and Prediction | ⏳ In progress |
| 5 | Classification | ⏳ Not started |
| 6 | Statistical Machine Learning | ⏳ Not started |
| 7 | Unsupervised Learning | ⏳ Not started |

Deadline for Chapters 1–4: **3 October 2026**.

## Chapter 1 summary — Exploratory Data Analysis

Covers how to describe a dataset before any modeling: location estimates
(mean, trimmed mean, median, weighted variants), variability estimates
(standard deviation, robust MAD, IQR), the shape of a distribution
(percentiles, boxplots, histograms, KDE), exploring categorical data, and
exploring the relationship between two or more variables (correlation,
scatterplots, hexbin/contour plots for large datasets, cross-tabulation,
grouped boxplots, and facet grids). Full write-up and reproduced code are in
[`Chapter1_Exploratory_Data_Analysis/`](Chapter1_Exploratory_Data_Analysis/).

## Setup

```bash
pip install -r requirements.txt
```

## Academic integrity note

All explanations were written in my own words; code was reproduced and
adapted from the book's methodology using the official companion datasets
(not copy-pasted from the original repository). LLM assistance was used for
clarifying statistical theory, per the assignment guidelines.
