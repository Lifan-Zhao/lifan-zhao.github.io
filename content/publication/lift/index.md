---
title: 'Rethinking Channel Dependence for Multivariate Time Series Forecasting: Learning
  from Leading Indicators'
authors:
- admin
- Yanyan Shen
date: '2024-01-01'
publishDate: '2025-05-25T08:14:53.200877Z'
publication_types:
- paper-conference
publication: "The Twelfth International Conference on Learning Representations **(ICLR'24)**"
abstract: "Recently, channel-independent methods have achieved state-of-the-art performance in multivariate time series (MTS) forecasting. Despite reducing overfitting risks, these methods miss potential opportunities in utilizing channel dependence for accurate predictions. We argue that there exist locally stationary lead-lag relationships between variates, i.e., some lagged variates may follow the leading indicators within a short time period. Exploiting such channel dependence is beneficial since leading indicators offer advance information that can be used to reduce the forecasting difficulty of the lagged variates. In this paper, we propose a new method named LIFT that first efficiently estimates leading indicators and their leading steps at each time step and then judiciously allows the lagged variates to utilize the advance information from leading indicators. LIFT plays as a plugin that can be seamlessly collaborated with arbitrary time series forecasting methods. Extensive experiments on six real-world datasets demonstrate that LIFT improves the state-of-the-art methods by 5.5% in average forecasting performance. Our code is available at https://github.com/SJTU-DMTai/LIFT."
url_pdf: https://arxiv.org/pdf/2401.17548
url_code: https://github.com/SJTU-DMTai/LIFT
url_poster: https://iclr.cc/media/PosterPDFs/ICLR%202024/18928.png?t=1714892383.2416034
---
