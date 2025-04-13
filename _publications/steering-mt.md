---
title: "Steering Large Language Models for Machine Translation with Finetuning and In-Context Learning"
authors:
    - name: Duarte M. Alves
      core: true
      me: true
    - name: Nuno M Guerreiro
    - name: João Alves
    - name: José Pombal
    - name: Ricardo Rei
    - name: José G. C. de Souza
    - name: Pierre Colombo
    - name: Andre Martins
permalink: /publication/steering-mt
date: 2023-12-06
venue: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
paperurl: 'https://aclanthology.org/2023.findings-emnlp.744.pdf'
order: 3
share: false
---

Large language models (LLMs) are a promising avenue for machine translation (MT). However, current LLM-based MT systems are brittle: their effectiveness highly depends on the choice of few-shot examples and they often require extra post-processing due to overgeneration. Alternatives such as finetuning on translation instructions are computationally expensive and may weaken in-context learning capabilities, due to overspecialization. In this paper, we provide a closer look at this problem. We start by showing that adapter-based finetuning with LoRA matches the performance of traditional finetuning while reducing the number of training parameters by a factor of 50. This method also outperforms few-shot prompting and eliminates the need for post-processing or in-context examples. However, we show that finetuning generally degrades few-shot performance, hindering adaptation capabilities. Finally, to obtain the best of both worlds, we propose a simple approach that incorporates few-shot examples during finetuning. Experiments on 10 language pairs show that our proposed approach recovers the original few-shot capabilities while keeping the added benefits of finetuning.