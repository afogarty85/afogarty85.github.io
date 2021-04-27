---
title: 'BERT-Vision'
date: 2021-04-26
permalink: /posts/2021/04/BERTVision/
tags:
  - BERT
  - Transformers
  - Natural Language Processing
  - PyTorch
---


What compression methods can extract regularity from BERT during *fine-tuning*? Drawing on research that demonstrates the utility of information found across all of BERT's layers \citep{tenney2019bert, van2019does}, we propose a compression method, *BERT-Vision*, that captures the regularities produced by BERT during fine-tuning. BERT-Vision's contribution is two-fold: First, we show that compression during fine-tuning can yield comparative and sometimes better performance than BERT, and second, we show that this performance is realized with a model that is 209x smaller than BERT in terms of its parameters. To view this project, please [click here](https://github.com/afogarty85/BERTVision){:target="_blank"}.
