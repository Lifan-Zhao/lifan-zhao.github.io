---
title: 'Less is More: Unlocking Specialization of Time Series Foundation Models via
  Structured Pruning'
authors:
- admin
- Yanyan Shen
- Zhaoyang Liu
- Xue Wang
- Jiaji Deng
date: '2025-09-19'
publishDate: '2025-09-19T02:53:44.206815Z'
publication_types:
- paper-conference
publication: "The Thirty-ninth Annual Conference on Neural Information Processing Systems **(NeurIPS'25)**"
links:
- name: arXiv
  url: https://arxiv.org/abs/2505.23195
url_pdf: https://arxiv.org/pdf/2505.23195
abstract: "Scaling laws motivate the development of Time Series Foundation Models (TSFMs) that pre-train vast parameters and achieve remarkable zero-shot forecasting performance. Surprisingly, even after fine-tuning, TSFMs cannot consistently outperform smaller, specialized models trained on full-shot downstream data. A key question is how to regularize the adaptation process of TSFMs for a target forecasting task. Through empirical studies on various TSFMs, the pre-trained models often exhibit inherent sparsity and redundancy in computation, suggesting that TSFMs have learned to activate task-relevant network substructures to accommodate diverse forecasting tasks. To preserve this valuable prior knowledge, we propose structured pruning method to regularize the subsequent fine-tuning process by focusing it on a more relevant and compact parameter space. Extensive experiments on seven TSFMs and six benchmarks demonstrate that fine-tuning a smaller, pruned TSFM significantly improves forecasting performance compared to fine-tuning original models. This ``prune-then-finetune'' paradigm often enables TSFMs to achieve state-of-the-art performance and surpass strong specialized baselines."
---
