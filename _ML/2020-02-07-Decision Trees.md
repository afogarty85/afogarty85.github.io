---
title: 'Decision Trees'
permalink: /ML/Decision_Trees
date: 2020-02-07
tags:
  - Applied Machine Learning
  - CART
---

The *Decision Tree* algorithm is part of a family of classifier and regression algorithms that aim to predict the class or value of an observation. [Decision trees](/applied_ml/CART.html){:target="_blank"} classify data by splitting features at specified thresholds such that, ideally, we can perfectly predict the observation's label. At its core, features are split by using two relatively simplistic algorithms: `entropy` and `information gain`. When deciding how to split a feature, a threshold is selected such that the informational gain is the highest, meaning more information is revealed and thereby our predictions for our dependent variable's label is improved (or perfect).

This applied application also includes a near complete treatment of `xgboost` -- one of the most popular and most powerful algorithms used today.
