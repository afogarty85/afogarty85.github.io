---
title: 'PetaFlights'
date: 2020-12-11
permalink: /posts/2020/12/PetaFlights/
tags:
  - Spark
  - Petastorm
  - Horovod
  - DataBricks
  - PyTorch
---

What accounts for flight delays in the U.S.? This project portrays the machine learning end of a large data engineering project that merged 630 million rows of weather data against 31 million rows of flight data. I use the state-of-the-art in distributed deep learning by leveraging Petastorm, Horovod, and PyTorch to produce a multilayer perceptron model that is distributed across 8 workers in DataBricks. Importantly, I use novel approaches to transform categorical data into continuous features through an embedding table. To view this project, please [click here](/projects/petaflights/petastorm.html){:target="_blank"}.
