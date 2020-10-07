---
title: 'Feature Normalization and Initialization'
permalink: /DL/norm
date: 2020-10-06
tags:
  - Deep Learning
  - Multilayer Perceptrons
---

In this guide, we will walk through feature normalization and weight initialization schemes in PyTorch. In short, we normalize our inputs for gradient descent because large weights will dominate our updates in our attempt to find global or local minima. Separately, we use custom weight initialization schemes to improve our ability to converge during optimization or to improve our ability to use certain activation functions. [In this post](/deep_learning/feature_norm.html){:target="_blank"}, we walk through the application of batch normalization and Xaviar initialization in PyTorch.
