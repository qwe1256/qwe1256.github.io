---
title: "OmniCellTOSG: The First Cell Text-Omic Signaling Graphs Dataset for Joint LLM and GNN Modeling"
collection: publications
category: manuscripts
permalink: /publication/OmniCellTOSG
excerpt: 'Heming Zhang, Tim Xu, Dekang Cao, Shunning Liang, Lars Schimmelpfennig, Levi Kaster, **Di Huang**, Carlos Cruchaga, Guangfu Li, Michael Province, Yixin Chen, Philip Payne, Fuhai Li'
date: 2025-04-02
venue: 'arXiv preprint arXiv:2504.02148'
paperurl: 'https://arxiv.org/abs/2504.02148'
citation: ''
keywords: 'Biomedical Knowledge Graphs, Single-Cell Omics, Cell Text-Omic Signaling Graphs'
---

Complex cell signaling systems -- governed by varying protein abundances and interactions -- generate diverse cell types across organs. These systems evolve under influences such as age, sex, diet, environmental exposures, and diseases, making them challenging to decode given the involvement of tens of thousands of genes and proteins. Recently, hundreds of millions of single-cell omics data have provided a robust foundation for understanding these signaling networks within various cell subpopulations and conditions. Inspired by the success of large foundation models (for example, large language models and large vision models) pre-trained on massive datasets, we introduce OmniCellTOSG, the first dataset of cell text-omic signaling graphs (TOSGs). Each TOSG represents the signaling network of an individual or meta-cell and is labeled with information such as organ, disease, sex, age, and cell subtype. OmniCellTOSG offers two key contributions. First, it introduces a novel graph model that integrates human-readable annotations -- such as biological functions, cellular locations, signaling pathways, related diseases, and drugs -- with quantitative gene and protein abundance data, enabling graph reasoning to decode cell signaling. This approach calls for new joint models combining large language models and graph neural networks. Second, the dataset is built from single-cell RNA sequencing data of approximately 120 million cells from diverse tissues and conditions (healthy and diseased) and is fully compatible with PyTorch. This facilitates the development of innovative cell signaling models that could transform research in life sciences, healthcare, and precision medicine. The OmniCellTOSG dataset is continuously expanding and will be updated regularly. 