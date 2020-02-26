---
title: "Restenosis prediction"
layout: archive
author_profile: true
author: Chechu
date: 2020-02-05
tags: [Machine Learning]
categories: [Machine Learning]
excerpt: "Scientific Publication"
---
# Restenosis (CJC)

## Article:
**Machine Learning To Predict Stent Restenosis Based On Daily Demographic, Clinical And Angiographic Characteristics**

[![DOI_article1](https://zenodo.org/badge/DOI/10.1016/j.cjca.2020.01.027.svg)](https://doi.org/10.1016/j.cjca.2020.01.027)

## EDITORIAL referring our article:
**The Rise of Open-sourced Machine Learning in Small and Imbalanced Datasets: Predicting In-Stent Restenosis**

[![DOI_editorial](https://zenodo.org/badge/DOI/10.1016/j.cjca.2020.02.002.svg)](https://doi.org/10.1016/j.cjca.2020.02.002)


## Abstract
### Background
Machine-learning (ML) has arrived in medicine to deliver individually adapted medical care. This study sought to use ML to discriminate stent restenosis (SR) compared to existing predictive scores of SR. In order to develop an easily-applicable model, we performed our predictions without any additional variables than those obtained in daily practice.

### Methods
The dataset, obtained from the GRACIA-3 trial, consisted of 263 patients with demographic, clinical and angiographic characteristics; 23 (9%) of them presented SR at 12-months after stent implantation. A methodology to work with small imbalanced datasets, based in cross-validation and the Precision/Recall (PR) plots, was used and state-of-the-art ML classifiers were trained.

### Results
Our best performing model (0.46, area under the PR curve [AUC-PR]) was developed with an extremely randomized trees classifier, which showed better performance than chance alone (0.09 AUC-PR, corresponding to the 9% of patients presenting SR in our dataset) and three existing scores; PRESTO-1 (0.31 AUC-PR), PRESTO-2 (0.27 AUC-PR), and EVENT (0.18 AUC-PR). The most important variables ranked according to their contribution to the predictions were diabetes, ≥2 vessel-coronary disease, post-PCI TIMI-flow, abnormal platelets, post-PCI thrombus, and abnormal cholesterol. To counteract the lack of external validation for our study, we deployed our ML algorithm in an open source calculator, where the model would stratify patients of high and low-risk; as an example tool to determine generalizability of prediction models from small imbalanced sample size.

### Conclusions
Applied immediately after stent implantation, a ML model better differentiates those patients who will present SR over current discriminators.