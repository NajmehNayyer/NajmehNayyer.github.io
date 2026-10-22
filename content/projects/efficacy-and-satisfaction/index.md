---
title: "General Self-Efficacy and Life Satisfaction: A Survey-Based Analysis"
date: 2026-10-22
links:
  - name: Persian Survey
    url: https://survey.porsline.ir/s/nuHchN0H
  - name: Data
    url: https://najmehnayyer.github.io/uploads/efficacy-and-satisfaction-data.sav
  - name: Output
    url: https://najmehnayyer.github.io/uploads/efficacy-and-satisfaction-output.sav
tags:
  - SPSS
  - Data Analysis
---

## Overview

This project investigates general self-efficacy and life satisfaction using survey data. It examines the relationships between these two psychological constructs and explores differences associated with demographic characteristics and self-reported daily social activity.

The project combines psychological measurement, survey data management, and statistical hypothesis testing using IBM SPSS Statistics.

## Research Objectives

The analyses focus on the following questions:

- Is general self-efficacy associated with life satisfaction?
- Do general self-efficacy and life satisfaction differ by gender?
- Are there differences in psychological outcomes across educational levels?
- Are psychological outcomes associated with living status and other demographic characteristics?

## Data Collection

Data were collected using an online questionnaire.

**[Access the survey](https://survey.porsline.ir/s/nuHchN0H)**

The dataset includes demographic information, a measure of daily social activity, and questionnaire items assessing general self-efficacy and life satisfaction.

### Variables

| Category | Variables |
|---|---|
| Demographics | Age, gender, living status, education |
| Social activity | Self-reported daily social-activity duration |
| General self-efficacy | GSE1–GSE10; total score (`GENERAL`) |
| Life satisfaction | SWLS1–SWLS5; total score (`SATISFAC`) |

Social activity is recorded in five duration categories: under one hour, 1–2 hours, 2–3 hours, 3–4 hours, and more than four hours.

### Psychological Measures

- **General Self-Efficacy Scale (GSE):** A 10-item questionnaire measuring perceived general self-efficacy.
- **Satisfaction With Life Scale (SWLS):** A 5-item questionnaire measuring subjective life satisfaction.

The dataset contains item-level responses and corresponding overall scores for both measures.

## Statistical Analysis

Statistical analyses were conducted using **IBM SPSS Statistics**.

The analysis output includes the following procedures:

- **Descriptive statistics:** Summarizing the study variables.
- **Pearson correlation:** Examining linear associations between variables.
- **Nonparametric correlation:** Examining associations using a rank-based approach.
- **Independent-samples t-test:** Comparing two groups.
- **One-way ANOVA:** Testing differences across multiple groups, followed by post hoc comparisons.
- **Univariate analysis of variance:** Examining between-group effects on individual outcomes.
- **Post hoc comparisons:** Identifying pairwise group differences where applicable.

These procedures provide complementary approaches to examining associations and differences in the survey data.

## Tools and Technologies

- IBM SPSS Statistics
- Porsline for online survey administration
- Psychological questionnaire scoring
- Descriptive and inferential statistical analysis

## Project Files

- `data.sav` — SPSS dataset containing survey responses, demographic variables, questionnaire items, and total scores.
- `output.spv` — SPSS output file containing the statistical analyses and tables.
