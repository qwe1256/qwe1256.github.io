---
title: "Skewed Memorization in Large Language Models: Quantification and Decomposition"
collection: publications
category: manuscripts
permalink: /publication/Skewed-Memorization
excerpt: 'Hao Li, **Di Huang**, Ziyu Wang, Amir M Rahmani'
date: 2025-02-03
venue: 'arXiv preprint arXiv:2502.01187'
paperurl: 'https://arxiv.org/abs/2502.01187'
citation: ''
keywords: 'Memorization in LLM, Skewed Data Distribution, Privacy in LLM'
---

Memorization in Large Language Models (LLMs) poses privacy and security risks, as models may unintentionally reproduce sensitive or copyrighted data. Existing analyses focus on average-case scenarios, often neglecting the highly skewed distribution of memorization. This paper examines memorization in LLM supervised fine-tuning (SFT), exploring its relationships with training duration, dataset size, and inter-sample similarity. By analyzing memorization probabilities over sequence lengths, we link this skewness to the token generation process, offering insights for estimating memorization and comparing it to established metrics. Through theoretical analysis and empirical evaluation, we provide a comprehensive understanding of memorization behaviors and propose strategies to detect and mitigate risks, contributing to more privacy-preserving LLMs.