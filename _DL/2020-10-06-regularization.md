---
title: 'Regularization'
permalink: /DL/Regularization
date: 2020-10-06
tags:
  - Deep Learning
  - Multilayer Perceptrons
---

We can think of regularization as a general means to reduce overfitting. In practice, this means that regularizing effects aim to reduce the model capacity and/or the variance of the predictions. While the best way to reduce overfitting is to acquire more data, data augmentation (e.g., for images: random rotation, crop, etc) is the next best thing. Barring those possibilities, we can reduce the capacity of the model through regularization methods. [In this post](/deep_learning/regularization.html){:target="_blank"}, we walk through the application of L2 regularization (manually and automatically) and dropout in PyTorch.
