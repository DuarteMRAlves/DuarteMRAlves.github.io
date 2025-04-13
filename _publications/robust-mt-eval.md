---
title: "Robust MT Evaluation with Sentence-level Multilingual Augmentation"
authors:
    - name: Duarte M. Alves
      core: true
      me: true
    - name: Ricardo Rei
    - name: Ana C Farinha
    - name: José G. C. de Souza
    - name: Andre Martins
permalink: /publication/robust-mt-eval
date: 2022-12-07
venue: 'Proceedings of the Seventh Conference on Machine Translation (WMT)'
paperurl: 'https://aclanthology.org/2022.wmt-1.43.pdf'
---

Automatic translations with critical errors may lead to misinterpretations and pose several risks for the user. As such, it is important that Machine Translation (MT) Evaluation systems are robust to these errors in order to increase the reliability and safety of Machine Translation systems. Here we introduce SMAUG a novel Sentence-level Multilingual AUGmentation approach for generating translations with critical errors and apply this approach to create a test set to evaluate the robustness of MT metrics to these errors. We show that current State-of-the-Art metrics are improving their capability to distinguish translations with and without critical errors and to penalize the first accordingly. We also show that metrics tend to struggle with errors related to named entities and numbers and that there is a high variance in the robustness of current methods to translations with critical errors.