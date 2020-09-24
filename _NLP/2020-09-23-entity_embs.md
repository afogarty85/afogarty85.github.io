---
title: 'Classification: Entity Embeddings'
permalink: /NLP/Entity_Embeddings
date: 2020-09-23
tags:
  - Applied Machine Learning
  - Natural Language Processing
---


In this guide, we will implement entity embeddings in two ways via PyTorch: (1) via `nn.Embedding()`, and (2) via transformers. We will also show how to load data in a more efficient manner through a custom PyTorch data set class. This style of data management is slightly more complicated to initialize, but is the precise way we want to load our data when dealing: (1) big data, or (2) a memory-conservative environment. [Entity embeddings](/applied_nlp/entity_embs.html){:target="_blank"} refers to the idea of transforming categorical variables into continuous embeddings to avoid one-hot encoding and sparse matrices.
