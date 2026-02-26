---
title: "Predictive Risk Modeling for Pre-Release QA"
category: "QA Automation"
description: "Python-based predictive risk models at Unity Technologies that analyzed feature signals from logs and defect history to flag high-risk features before release — achieving a 42% reduction in critical bugs."
stack:
  - Python
  - XGBoost
  - MLP
  - pandas
  - NumPy
  - MySQL
  - Jenkins
  - C#
order: 3
github: "https://github.com/maxwellqiu"
---

## Overview

Built at **Unity Technologies**, this project applied ML-driven risk scoring to the QA release process. Rather than treating all features equally in testing, the system identified which features were statistically likely to ship with critical bugs.

## Problem

With large codebases, exhaustive testing before every release is impossible. The challenge was focusing QA effort on the highest-risk areas before they reached production.

## Solution

- Engineered scalable **data extraction pipelines** (pandas/NumPy) to parse Unity test logs and store structured results in MySQL
- Built **quantitative bug-density and severity distributions by module** to identify historical hotspots
- Trained **MLP and XGBoost classifiers** on feature signals (commit patterns, defect history, code complexity) to predict release risk
- Integrated risk scores into the CI/CD pipeline as a pre-release gate — high-risk features triggered expanded test coverage

## Results

- **42% reduction in critical bugs** reaching production
- **56% reduction in low-quality AI behavior submissions** through Python batch validators with MLP/XGBoost
- **60% improved code reusability** via Page Object pattern in C#/Python
- **45% reduction in deployment cycle times**
