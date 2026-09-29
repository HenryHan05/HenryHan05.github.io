---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Sc. in Computer Science and Technology, Dalian University of Technology (DUT), China, Sep 2023 – Expected Jun 2027
  * GPA: 4.21/5.00, Rank: 3rd/155
  * Core Coursework: Compiler Principles (100), Discrete Mathematics (99), Artificial Intelligence (97), Data Structures and Algorithms (97), Computer Composition (95), C++ Programming (94)
* Exchange Student, Computer Science, University of California, Santa Barbara (UCSB), Mar 2026 – Jun 2026
  * Funded by China Scholarship Council (CSC)
  * Coursework: CMPSC 291K Special Topics in Foundation Models (A), CMPSC 5B Introduction to Data Science II (A+)

Research Experience
======
**Layer Importance of Houlsby Adapters in Decoder-Only Transformers: An Ablation Study on GPT-2**
*Course Research Project, UCSB CMPSC 291K (2-person team), advised by Prof. Xifeng Yan — May 2026 – Sep 2026*

* Investigated whether the adapter layer-importance pattern found in BERT (encoder-only) generalizes to decoder-only, causal-attention architectures
* Inserted Houlsby adapters into all 24 layers of GPT-2 Medium and designed a post-training ablation methodology — single-layer bypass and an exhaustive 24×24 contiguous layer-span analysis
* Benchmarked GPT-2 against BERT-large across SST-2, MNLI, and RTE
* Found that GPT-2's layer-importance pattern differs from BERT's and is task-dependent (SST-2 peaks at Layer 0; MNLI is bimodal, peaking at Layer 7), and that inter-adapter coupling makes single-layer importance alone insufficient for pruning decisions
* Extended the pipeline to RTE, showing that meaningful layer-importance analysis requires sufficient task learning — limited training data produced near-chance performance and noisy ablation patterns

Projects
======
**C Compiler Development**
* Built a miniature C compiler through an LLM-assisted, prompt-engineering-based development workflow
* Implemented lexical analysis, syntax analysis, intermediate code generation, and virtual-machine execution
* Verified correctness through systematic testing and debugging

**Vehicle Emissions and Fuel Efficiency Analysis**
* Analyzed a multi-thousand-row vehicle dataset using Python (Pandas, NumPy)
* Applied permutation testing, Pearson correlation, and linear regression to quantify the relationship between engine size and CO2 emissions
* Compared fuel efficiency between diesel and gasoline vehicles

Honors & Awards
======
* First-Class Scholarship (Top 5% students), Sep 2024 & Sep 2025
* Third Prize, 24th DUT Undergraduate Computer Programming Contest, Dec 2025

Skills
======
* Programming: C, C++, Python
* Data Analysis / Tools: PyTorch, Transformers, Pandas, NumPy, Matplotlib, Git/GitHub
* Languages: English (TOEFL 108)

Additional Information
======
* Competitive runner — 10K PB: 43:22, 5K PB: 20:56
