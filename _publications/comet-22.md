---
title: "COMET-22: Unbabel-IST 2022 Submission for the Metrics Shared Task"
authors:
- name: Ricardo Rei
- name: José G. C. de Souza
- name: Duarte Alves
  me: true
- name: Chrysoula Zerva
- name: Ana C Farinha
- name: Taisiya Glushkova
- name: Alon Lavie
- name: Luisa Coheur
- name: André F. T. Martins
permalink: /publication/comet-22
date: 2022-12-07
venue: 'Proceedings of the Seventh Conference on Machine Translation (WMT)'
paperurl: 'https://aclanthology.org/2022.wmt-1.52.pdf'
---

In this paper, we present the joint contribution of Unbabel and IST to the WMT 2022 Metrics Shared Task. Our primary submission – dubbed COMET-22 – is an ensemble between a COMET estimator model trained with Direct Assessments and a newly proposed multitask model trained to predict sentence-level scores along with OK/BAD word-level tags derived from Multidimensional Quality Metrics error annotations. These models are ensembled together using a hyper-parameter search that weights different features extracted from both evaluation models and combines them into a single score. For the reference-free evaluation, we present CometKiwi. Similarly to our primary submission, CometKiwi is an ensemble between two models. A traditional predictor-estimator model inspired by OpenKiwi and our new multitask model trained on Multidimensional Quality Metrics which can also be used without references. Both our submissions show improved correlations compared to state-of-the-art metrics from last year as well as increased robustness to critical errors.