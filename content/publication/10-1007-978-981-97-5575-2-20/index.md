---
title: 'StockCL: Selective Contrastive Learning for Stock Trend Forecasting via Learnable Concepts'
authors:
- Zexi Zhang
- admin
- Yanyan Shen
- Bin Yao
date: '2024-01-01'
publishDate: '2025-05-25T08:14:53.229533Z'
publication_types:
- paper-conference
publication: "Database Systems for Advanced Applications: 29th International Conference **(DASFAA'24)**"
doi: 10.1007/978-981-97-5575-2_20
abstract: Stock trend forecasting is crucial for quantitative investment and various
  deep learning models have been proposed to obtain superior performance. Due to the
  limited stock data, existing deep learning models suffer from overfitting. It has
  been revealed that supervised contrastive learning can provide additional supervision
  signals by pulling closer samples with the same label and pushing apart samples
  with different labels. However, stock data has continuous labels and it is nontrivial
  to identify appropriate contrastive pairs based on label information. In this paper,
  we develop a novel selective contrastive learning framework named StockCL for stock
  trend forecasting, which is applicable to any stock trend forecasting models. Our
  key insight is to identify latent concepts that drive the stock trends and select
  reliable contrastive pairs according to the samples’ belonging concepts and their
  label similarity. Experiments on two datasets with four stock trend forecasting
  models demonstrate that StockCL consistently improves the forecasting performance
  with a significant margin by 5%–18%. Code is available at .
tags:
- Stock trend forecasting
- Contrastive learning
links:
- name: URL
  url: https://doi.org/10.1007/978-981-97-5575-2_20
---
