---
title: "CroissantLLM: A Truly Bilingual French-English Language Model"
authors:
  - name: Manuel Faysse
  - name: Patrick Fernandes
  - name: Nuno M. Guerreiro
  - name: António Loison
  - name: Duarte M. Alves
    me: true
  - name: Caio Corro
  - name: Nicolas Boizard
  - name: João Alves
  - name: Ricardo Rei
  - name: Pedro H. Martins
  - name: Antoni Bigata Casademunt
  - name: François Yvon
  - name: André F.T. Martins
  - name: Gautier Viaud
  - name: Céline Hudelot
  - name: Pierre Colombo
permalink: /publication/croissantllm
date: 2024-02-01
venue: 'ArXiv Preprint'
paperurl: 'https://arxiv.org/pdf/2402.00786'
share: false
---

We introduce CroissantLLM, a 1.3B language model pretrained on a set of 3T English and French tokens, to bring to the research and industrial community a high-performance, fully open-sourced bilingual model that runs swiftly on consumer-grade local hardware. To that end, we pioneer the approach of training an intrinsically bilingual model with a 1:1 English-to-French pretraining data ratio, a custom tokenizer, and bilingual finetuning datasets. We release the training dataset, notably containing a French split with manually curated, high-quality, and varied data sources. To assess performance outside of English, we craft a novel benchmark, FrenchBench, consisting of an array of classification and generation tasks, covering various orthogonal aspects of model performance in the French Language. Additionally, rooted in transparency and to foster further Large Language Model research, we release codebases, and dozens of checkpoints across various model sizes, training data distributions, and training steps, as well as fine-tuned Chat models, and strong translation models. We evaluate our model through the FMTI framework, and validate 81 % of the transparency criteria, far beyond the scores of even most open initiatives. This work enriches the NLP landscape, breaking away from previous English-centric work in order to strengthen our understanding of multilinguality in language models.