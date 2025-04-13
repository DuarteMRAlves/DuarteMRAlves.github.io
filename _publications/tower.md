---
title: "Tower: An Open Multilingual Large Language Model for Translation-Related Tasks"
authors:
    - name: Duarte M. Alves
      core: true
      me: true
    - name: José Pombal
      core: true
    - name: Nuno M Guerreiro
      core: true
    - name: Pedro Henrique Martins
    - name: João Alves
    - name: Amin Farajian
    - name: Ben Peters
    - name: Ricardo Rei
    - name: Patrick Fernandes
    - name: Sweta Agrawal
    - name: Pierre Colombo
    - name: José G. C. de Souza
    - name: Andre Martins
permalink: /publication/tower
date: 2024-10-07
venue: 'First Conference on Language Modeling (COLM) - Oral Spotlight'
paperurl: 'https://arxiv.org/pdf/2402.17733'
---

While general-purpose large language models (LLMs) demonstrate proficiency on multiple tasks within the domain of translation, approaches based on open LLMs are competitive only when specializing on a single task. In this paper, we propose a recipe for tailoring LLMs to multiple tasks present in translation workflows. We perform continued pretraining on a multilingual mixture of monolingual and parallel data, creating TowerBase, followed by finetuning on instructions relevant for translation processes, creating TowerInstruct. Our model surpasses open alternatives on several relevant tasks and is competitive with general-purpose closed LLMs. We will release the Tower models, our specialization dataset, an evaluation framework for LLMs focusing on the translation ecosystem, and a collection of model generations on our benchmark.