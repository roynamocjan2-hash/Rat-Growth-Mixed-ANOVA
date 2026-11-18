# Rat-Growth-Mixed-ANOVA

## Project Overview
This repository contains the complete statistical analysis, R code, visualizations, and report for **Formative Assessment 11: Mixed-Design Repeated Measures ANOVA Using R** in BIO2105 Biostatistics.

## Research Objectives
* Determine whether rat body weight differs significantly across treatment groups (Control, Thiouracil, Thyroxin) and measurement occasions (Weeks 0–4).
* Investigate whether the pattern of body weight changes over time differs depending on the treatment received (Treatment × Time interaction).

## Dataset Information
* **Dataset Name:** `rats`
* **Package:** `nlmm` (based on Box, 1950)
* **Design:** Mixed-design ANOVA (Between-subjects factor: Treatment; Within-subjects factor: Time)

## Repository Structure
* `README.md`: Project description and reproduction instructions.
* `Rat_Growth_Mixed_ANOVA.R`: Complete and documented R script containing all statistical procedures.
* `Rat_Growth_Mixed_ANOVA.Rmd`: R Markdown source report containing methodology, code, outputs, and interpretations.
* `Rat_Growth_Mixed_ANOVA.html` (or `.pdf`): Successfully rendered final report.

## Instructions for Reproduction
1. Open R or RStudio.
2. Install required packages: `install.packages(c("nlmm", "tidyverse", "rstatix", "ggpubr"))`.
3. Open and run `Rat_Growth_Mixed_ANOVA.R` or knit `Rat_Growth_Mixed_ANOVA.Rmd`.
