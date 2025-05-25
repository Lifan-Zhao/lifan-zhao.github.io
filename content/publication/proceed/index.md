---
title: Proactive Model Adaptation Against Concept Drift for Online Time Series Forecasting
authors:
- admin
- Yanyan Shen
date: '2025-02-01'
publishDate: '2025-05-25T08:14:53.191810Z'
publication_types:
- paper-conference
publication: "Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery
  and Data Mining **(KDD'25)**"
abstract: "Time series forecasting always faces the challenge of concept drift, where data distributions evolve over time, leading to a decline in forecast model performance. Existing solutions are based on online learning, which continually organize recent time series observations as new training samples and update model parameters according to the forecasting feedback on recent data. However, they overlook a critical issue: obtaining ground-truth future values of each sample should be delayed until after the forecast horizon. This delay creates a temporal gap between the training samples and the test sample. Our empirical analysis reveals that the gap can introduce concept drift, causing forecast models to adapt to outdated concepts. In this paper, we present Proceed, a novel proactive model adaptation framework for online time series forecasting. Proceed first estimates the concept drift between the recently used training samples and the current test sample. It then employs an adaptation generator to efficiently translate the estimated drift into parameter adjustments, proactively adapting the model to the test sample. To enhance the generalization capability of the framework, Proceed is trained on synthetic diverse concept drifts. Extensive experiments on five real-world datasets across various forecast models demonstrate that Proceed brings more performance improvements than the state-of-the-art online learning methods, significantly facilitating forecast models' resilience against concept drifts. Code is available at https://github.com/SJTU-DMTai/OnlineTSF."
doi: 10.1145/3690624.3709210
links:
url_pdf: https://arxiv.org/pdf/2412.08435
url_code: https://github.com/SJTU-DMTai/OnlineTSF
---
