# Rat-Growth-Mixed-ANOVA

## Project Overview
This repository contains the statistical analysis and R code for **Formative Assessment 11: Mixed-Design Repeated Measures ANOVA Using R** in BIO2105 Biostatistics.

## Research Objectives
* Determine whether rat body weight differs significantly across treatment groups (Control, Thiouracil, Thyroxin) and measurement occasions (Weeks 0–4).
* Investigate whether the pattern of body weight changes over time differs depending on the treatment received (Treatment × Time interaction).

## Dataset Information
* **Dataset Name:** `rats`
* **Package:** `nlmm` (based on Box, 1950)
* **Design:** Mixed-design ANOVA (Between-subjects factor: Treatment; Within-subjects factor: Time)

## Repository Structure
* `README.md`: Project description and reproduction instructions.
* `Rat_Growth_Mixed_ANOVA.R`: Complete and documented R script containing all statistical procedures, visualizations, assumption checks, mixed ANOVA, simple main effects, and post-hoc tests.

## Instructions for Reproduction
1. Open R or RStudio.
2. Install required packages (`install.packages(c("nlmm", "tidyverse", "rstatix", "ggpubr"))`).
3. Open and run `Rat_Growth_Mixed_ANOVA.R`.
