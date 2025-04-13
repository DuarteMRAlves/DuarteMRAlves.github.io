---
title: "COMETKiwi: IST-Unbabel 2022 Submission for the Quality Estimation Shared Task"
authors:
- name: Ricardo Rei
- name: Marcos Treviso
- name: Nuno M. Guerreiro
- name: Chrysoula Zerva
- name: Ana C Farinha
- name: Christine Maroti
- name: José G. C. de Souza
- name: Taisiya Glushkova
- name: Duarte Alves
  me: true
- name: Luisa Coheur
- name: Alon Lavie
- name: André F. T. Martins
permalink: /publication/cometkiwi
date: 2022-12-07
venue: 'Proceedings of the Seventh Conference on Machine Translation (WMT)'
paperurl: 'https://aclanthology.org/2022.wmt-1.60.pdf'
---

We present the joint contribution of IST and Unbabel to the WMT 2022 Shared Task on Quality Estimation (QE). Our team participated in all three subtasks: (i) Sentence and Word-level Quality Prediction; (ii) Explainable QE; and (iii) Critical Error Detection. For all tasks we build on top of the COMET framework, connecting it with the predictor-estimator architecture of OpenKiwi, and equipping it with a word-level sequence tagger and an explanation extractor. Our results suggest that incorporating references during pretraining improves performance across several language pairs on downstream tasks, and that jointly training with sentence and word-level objectives yields a further boost. Furthermore, combining attention and gradient information proved to be the top strategy for extracting good explanations of sentence-level QE models. Overall, our submissions achieved the best results for all three tasks for almost all language pairs by a considerable margin.