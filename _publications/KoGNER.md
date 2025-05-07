---
title: "KoGNER: A Novel Framework for Knowledge Graph Distillation on Biomedical Named Entity Recognition"
collection: publications
category: manuscripts
permalink: /publication/KoGNER
excerpt: 'Heming Zhang, Wenyu Li, **Di Huang**, Yinjie Tang, Yixin Chen, Philip Payne, Fuhai Li'
date: 2025-03-19
venue: 'arXiv preprint: arXiv:2503.15737'
paperurl: 'https://arxiv.org/abs/2503.15737'
citation: ''
keywords: 'Named Entity Recognition, Biomedical NLP, Knowledge Distillation, Graph Neural Networks'
---
Named Entity Recognition (NER) is a fundamental task in Natural Language Processing (NLP) that plays a crucial role in information extraction, question answering, and knowledge-based systems. Traditional deep learning-based NER models often struggle with domain-specific generalization and suffer from data sparsity issues. In this work, we introduce Knowledge Graph distilled for Named Entity Recognition (KoGNER), a novel approach that integrates Knowledge Graph (KG) distillation into NER models to enhance entity recognition performance. Our framework leverages structured knowledge representations from KGs to enrich contextual embeddings, thereby improving entity classification and reducing ambiguity in entity detection. KoGNER employs a two-step process: (1) Knowledge Distillation, where external knowledge sources are distilled into a lightweight representation for seamless integration with NER models, and (2) Entity-Aware Augmentation, which integrates contextual embeddings that have been enriched with knowledge graph information directly into GNN, thereby improving the model's ability to understand and represent entity relationships. Experimental results on benchmark datasets demonstrate that KoGNER achieves state-of-the-art performance, outperforming finetuned NER models and LLMs by a significant margin. These findings suggest that leveraging knowledge graphs as auxiliary information can significantly improve NER accuracy, making KoGNER a promising direction for future research in knowledge-aware NLP.