---
title: "EuroBERT: Scaling Multilingual Encoders for European Languages"
authors:
    - name: Nicolas Boizard
      core: true
    - name: Hippolyte Gisserot-Boukhlef
      core: true
    - name: Duarte M. Alves
      core: true
      me: true
    - name: André Martins
    - name: Ayoub Hammal
    - name: Caio Corro
    - name: Céline Hudelot
    - name: Emmanuel Malherbe
    - name: Etienne Malaboeuf
    - name: Fanny Jourdan
    - name: Gabriel Hautreux
    - name: João Alves
    - name: Kevin El-Haddad
    - name: Manuel Faysse
    - name: Maxime Peyrard
    - name: Nuno M. Guerreiro
    - name: Patrick Fernandes
    - name: Ricardo Rei
    - name: Pierre Colombo
permalink: /publication/eurobert
date: 2025-03-07
venue: 'ArXiv Preprint'
paperurl: 'https://arxiv.org/pdf/2503.05500'
---

General-purpose multilingual vector representations, used in retrieval, regression and classification, are traditionally obtained from bidirectional encoder models. Despite their wide applicability, encoders have been recently overshadowed by advances in generative decoder-only models. However, many innovations driving this progress are not inherently tied to decoders. In this paper, we revisit the development of multilingual encoders through the lens of these advances, and introduce EuroBERT, a family of multilingual encoders covering European and widely spoken global languages. Our models outperform existing alternatives across a diverse range of tasks, spanning multilingual capabilities, mathematics, and coding, and natively supporting sequences of up to 8,192 tokens. We also examine the design decisions behind EuroBERT, offering insights into our dataset composition and training pipeline. We publicly release the EuroBERT models, including intermediate training checkpoints, together with our training framework.