---
permalink: /
title: "Runyu Han"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an undergraduate student in Computer Science at Dalian University of Technology, interested in the efficient adaptation of foundation models — how parameter-efficient methods behave across different transformer architectures, and what that means for adapting and deploying large language models.

Research Interests
======
- Foundation Models and Large Language Models
- Parameter-Efficient Fine-Tuning (PEFT)
- Efficient AI Systems and Model Adaptation

Education
======
**Dalian University of Technology (DUT)**, China — B.Sc. in Computer Science and Technology, Sep 2023 – Expected Jun 2027. GPA: 4.21/5.00 (Rank: 3rd/155).

**University of California, Santa Barbara (UCSB)** — Exchange Student, Computer Science, Mar 2026 – Jun 2026 (funded by CSC). Coursework included CMPSC 291K: Special Topics in Foundation Models (Grade: A).

Selected Research
======
### Layer Importance of Houlsby Adapters in Decoder-Only Transformers: An Ablation Study on GPT-2
*Course Research Project, UCSB CMPSC 291K (2-person team), advised by Prof. Xifeng Yan*

**Research question:** Do the adapter layer-importance patterns found in BERT (encoder-only) transfer to decoder-only, causal-attention architectures?

**Method:** Inserted Houlsby adapters into all 24 layers of GPT-2 Medium and ran post-training ablations — single-layer bypass on three GLUE benchmarks and an exhaustive 24×24 contiguous layer-span analysis — across SST-2, benchmarked against BERT-large.

**Findings:**
- GPT-2's adapter importance pattern differs from BERT's, with lower-to-middle layers mattering more
- The pattern is task-dependent: SST-2 peaks at Layer 0, while MNLI is bimodal and peaks at Layer 7
- Extending the pipeline to a third task (RTE) showed that meaningful layer-importance analysis requires sufficient task learning, as limited training data resulted in near-chance performance and noisy ablation patterns

Other Projects
======
More detail on both is available on the [CV](/cv/) page.

- **C Compiler Development** — a miniature C compiler built through an LLM-directed, prompt-engineering-based workflow, covering lexical/syntax analysis, intermediate code generation, and a stack-based virtual machine.
- **Vehicle Emissions and Fuel Efficiency Analysis** — statistical analysis (permutation testing, correlation, regression) of a multi-thousand-row vehicle dataset.
