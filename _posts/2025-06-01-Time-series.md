---
layout: post
title: "Time Series Modeling for Mortality Predictions"
type: post
date: 2025-06-01
tags:
  - ML in Healthcare
  - Time Series
  - Representation Learning
  - Pytorch
  - Data Preprocessing
---

This project focuses on working with complex healthcare data from the Physionet 2012 Challenge dataset, which contains 48 hours of intensive care data used to predict patient mortality. It involves handling noisy, sparse, and irregularly-sampled multi-variate data through preprocessing, exploration, supervised learning, representation learning, and leveraging large language models (LLMs) for embedding extraction and analysis.

### Contributions

- Performed data preprocessing and exploratory analysis, including data transformation, handling missing values, standardization, and distribution visualization
- Implemented representation learning using an LSTM Autoencoder, and trained linear probes based on extracted embeddings for comparison with supervised approaches under label scarcity

### Key findings

SSL + linear probing show advantages under label scarcity. However, as labeled data increases, supervised training becomes more effective



Below, you'll find some results of our reports.
![Data Exploration](https://raw.githubusercontent.com/YanYang-G0001/github.io/master/img/data_exploration_time_series.png)
![Model Performance Comparison_1](https://raw.githubusercontent.com/YanYang-G0001/github.io/master/img/comp_prc.png)
![Model Performance Comparison_2](https://raw.githubusercontent.com/YanYang-G0001/github.io/master/img/comp_roc.png)







