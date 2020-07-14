---
title: 'Multiple Imputation'
permalink: /applied/MI
date: 2020-04-22
tags:
  - Multiple Imputation
  - Bayesian
  - Missing Data
  - Applied Statistics
---

Missingness refers to observations or measurement that, in principle, could have been carried out but for whatever reason, failed to occur (Ward and Ahlquist 2018). Data that we collect, whether observational or experimental data, will with near certainty, have some values that are missing. The general idea behind missing data imputation algorithms is that they all fill in the missing data with estimates of what real data would look like if it were available. Because the estimated data is by nature uncertain, we replicate the missing data many times to incorporate the uncertainty into the analysis. This post walks through the latest cutting edge [multiple imputation technique](/stats/missing_data.html){:target="_blank"} developed by Hollenbach et. al (2018).
