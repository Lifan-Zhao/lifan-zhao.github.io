---
title: 'RESUS: Warm-up Cold Users via Meta-learning Residual User Preferences in CTR
  Prediction'
authors:
- Yanyan Shen
- Lifan Zhao
- Weiyu Cheng
- Zibin Zhang
- Wenwen Zhou
- Lin Kangyi
date: '2023-02-01'
publishDate: '2025-05-25T08:14:53.213675Z'
publication_types:
- article-journal
publication: 'ACM Transactions on Information System (TOIS)'
doi: 10.1145/3564283
abstract: Click-through Rate (CTR) prediction on cold users is a challenging task
  in recommender systems. Recent researches have resorted to meta-learning to tackle
  the cold-user challenge, which either perform few-shot user representation learning
  or adopt optimization-based meta-learning. However, existing methods suffer from
  information loss or inefficient optimization process, and they fail to explicitly
  model global user preference knowledge, which is crucial to complement the sparse
  and insufficient preference information of cold users. In this article, we propose
  a novel and efficient approach named RESUS, which decouples the learning of global
  preference knowledge contributed by collective users from the learning of residual
  preferences for individual users. Specifically, we employ a shared predictor to
  infer basis user preferences, which acquires global preference knowledge from the
  interactions of different users. Meanwhile, we develop two efficient algorithms
  based on the nearest neighbor and ridge regression predictors, which infer residual
  user preferences via learning quickly from a few user-specific interactions. Extensive
  experiments on three public datasets demonstrate that our RESUS approach is efficient
  and effective in improving CTR prediction accuracy on cold users, compared with
  various state-of-the-art methods.
tags:
- Cold-start recommendation
- CTR prediction
- few-shot learning
- metric-based meta learning
links:
- name: URL
  url: https://doi.org/10.1145/3564283
---
