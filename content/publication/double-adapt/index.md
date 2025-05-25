---
title: 'DoubleAdapt: A Meta-learning Approach to Incremental Learning for Stock Trend
  Forecasting'
authors:
- admin
- Shuming Kong
- Yanyan Shen
date: '2023-08-01'
publishDate: '2025-05-25T08:14:53.207435Z'
publication_types:
- paper-conference
publication: "Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery
  and Data Mining **(KDD'23)**"
doi: 10.1145/3580305.3599315
abstact: "Stock trend forecasting is a fundamental task of quantitative investment where precise predictions of price trends are indispensable. As an online service, stock data continuously arrive over time. It is practical and efficient to incrementally update the forecast model with the latest data which may reveal some new patterns recurring in the future stock market. However, incremental learning for stock trend forecasting still remains under-explored due to the challenge of distribution shifts (a.k.a. concept drifts). With the stock market dynamically evolving, the distribution of future data can slightly or significantly differ from incremental data, hindering the effectiveness of incremental updates. To address this challenge, we propose DoubleAdapt, an end-to-end framework with two adapters, which can effectively adapt the data and the model to mitigate the effects of distribution shifts. Our key insight is to automatically learn how to adapt stock data into a locally stationary distribution in favor of profitable updates. Complemented by data adaptation, we can confidently adapt the model parameters under mitigated distribution shifts. We cast each incremental learning task as a meta-learning task and automatically optimize the adapters for desirable data adaptation and parameter initialization. Experiments on real-world stock datasets demonstrate that DoubleAdapt achieves state-of-the-art predictive performance and shows considerable efficiency."
links:
url_pdf: https://arxiv.org/pdf/2306.09862
url_code: https://github.com/SJTU-DMTai/DoubleAdapt
url_project: https://github.com/SJTU-DMTai/qlib
url_slides: https://raw.githubusercontent.com/SJTU-DMTai/DoubleAdapt/e20b6e46ccbd2b6b8180ff3db62f68b16721684c/slides_DoubleAdapt.pdf
url_video: https://iframe.videodelivery.net/eyJraWQiOiI3YjgzNTg3NDZlNWJmNDM0MjY5YzEwZTYwMDg0ZjViYiIsImFsZyI6IlJTMjU2In0.eyJzdWIiOiI5NDBiYmNjZmZjZDUyZDFiNGE2M2VhYjMzNjI4NjdiMCIsImV4cCI6MTc0ODE4NTUxMiwia2lkIjoiN2I4MzU4NzQ2ZTViZjQzNDI2OWMxMGU2MDA4NGY1YmIifQ.EES8UHgEptlYg9Hcz6o1w6zelvkI-_yCl85wouZ8myJC60BQZ6W0u5yy7ezNU-HSPRjhIwSSdm7UgbwcPOywJ3afWBWydCN6g2jNyo0uDPYnJUCRV0hKNFGUslhHq0i2JwRRPvETX21X_r40zibMS4EK1CAxg8-UoyAe2In0dp67LiixmBhHcQkx2MFzEeKXERHtYJfmqDP4HeHaw1HGYx847SuMi6bNWwiWTfQn9qZVtJ5vu3HdR3JYl9TSvrhDRPkMPVtHDzaUq52CfX9BC5Y1Bs_QjnXOmA_aEPmn3gSCc-QOKjap58H9rY_Cvs2YgrIIO03fzOrTdptpmEy6bA
---
