---
title: "Hallucinations in Large Multilingual Translation Models"
authors:
- name: Nuno M. Guerreiro
- name: Duarte M. Alves
  me: true
- name: Jonas Waldendorf
- name: Barry Haddow
- name: Alexandra Birch
- name: Pierre Colombo
- name: André F. T. Martins
permalink: /publication/hallucinations-large-mt
date: 2023-01-01
venue: 'Transactions of the Association for Computational Linguistics (TACL)'
paperurl: 'https://aclanthology.org/2023.tacl-1.85.pdf'
---

Hallucinated translations can severely undermine and raise safety issues when machine translation systems are deployed in the wild. Previous research on the topic focused on small bilingual models trained on high-resource languages, leaving a gap in our understanding of hallucinations in multilingual models across diverse translation scenarios. In this work, we fill this gap by conducting a comprehensive analysis—over 100 language pairs across various resource levels and going beyond English-centric directions—on both the M2M neural machine translation (NMT) models and GPT large language models (LLMs). Among several insights, we highlight that models struggle with hallucinations primarily in low-resource directions and when translating out of English, where, critically, they may reveal toxic patterns that can be traced back to the training data. We also find that LLMs produce qualitatively different hallucinations to those of NMT models. Finally, we show that hallucinations are hard to reverse by merely scaling models trained with the same data. However, employing more diverse models, trained on different data or with different procedures, as fallback systems can improve translation quality and virtually eliminate certain pathologies.