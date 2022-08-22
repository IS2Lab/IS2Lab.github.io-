---
title: Automatic Fairness Testing of Neural Classifiers through Adversarial Sampling
categories: AI_System_Analysis
header-img: images/post/ADF.gif
description: Fairness Testing of Deep Learning Systems <br> Published in TSE 2021
paper: https://ieeexplore.ieee.org/abstract/document/9506918
code: https://github.com/pxzhang94/ADF
---

### Abstract
Although deep learning has demonstrated astonishing performance in many applications, there are still concerns on their dependability. One desirable property of deep learning applications with societal impact is fairness (i.e., non-discrimination). Unfortunately, discrimination might be intrinsically embedded into the models due to discrimination in the training data. As a countermeasure, fairness testing systemically identifies discriminative samples, which can be used to retrain the model and improve its fairness. Existing fairness testing approaches however have two major limitations. First, they only work well on traditional machine learning models and have poor performance (e.g., effectiveness and efficiency) on deep learning models. Second, they only work on simple tabular data and are not applicable for domains such as text. In this work, we bridge the gap by proposing a scalable and effective approach for systematically searching for discriminative samples while extending fairness testing to address a challenging domain, i.e., text classification. Compared with state-of-the-art methods, our approach only employs lightweight procedures like gradient computation and clustering, which makes it significantly more scalable. Experimental results show that on average, our approach explores the search space more effectively (9.62 and 2.38 times more than the state-of-art methods respectively on tabular and text datasets) and generates much more individual discriminatory instances (24.95 and 2.68 times) within reasonable time. The retrained models reduce discrimination by 57.2% and 60.2% respectively on average.