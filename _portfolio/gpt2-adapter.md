---
title: "Layer Importance of Houlsby Adapters in Decoder-Only Transformers"
excerpt: "An ablation study of adapter layers in GPT-2 Medium"
collection: portfolio
date: 2026-09-19
importance: 3
---

**Course Research Project, UCSB CMPSC 291K**  
**2-person team, advised by Prof. Xifeng Yan**  
**May 2026 – Sep 2026**

[Project Report](https://drive.google.com/file/d/10z02CQdfxV6V7-Z_d5HB_o42BR-AWXsP/view?usp=sharing)

This project investigated whether adapter layer-importance patterns observed in BERT transfer to decoder-only transformer architectures.

We inserted Houlsby adapters into all 24 layers of GPT-2 Medium and designed a post-training ablation framework, including single-layer bypass and contiguous layer-span analysis.

Experiments were conducted on SST-2, MNLI, and RTE, with comparisons against BERT-large on SST-2.

Key findings:
- GPT-2 exhibits different adapter importance patterns from BERT.
- Adapter importance is task-dependent: SST-2 emphasizes Layer 0, while MNLI shows a bimodal pattern with a peak at Layer 7.
- RTE experiments showed that meaningful ablation analysis requires sufficient task learning and dataset scale.

Technologies:
PyTorch, Transformers, GPT-2, Parameter-Efficient Fine-Tuning (PEFT)

