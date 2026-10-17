title: "CiteAlign-Table: Verifying Citation Faithfulness when LLMs Attribute to Structured Data"
collection: publications
permalink: /ag-publication/CiteAlign-Table
excerpt: ''
date: 2025-11-07
venue: '35th ACM International Conference on Information and Knowledge Management (CIKM '26)'
citation: '@inproceedings{gupta2026citealign,
  author    = {Gupta, Ashish and Naik M C, Manjunath},
  title     = {CiteAlign-Table: Verifying Citation Faithfulness when LLMs Attribute to Structured Data},
  booktitle = {Proceedings of the 35th ACM International Conference on Information and Knowledge Management (CIKM '26)},
  year      = {2026},
  location  = {Rome, Italy},
  publisher = {ACM}
}'
---

**Abstract:** Attributed Question Answering systems increasingly ground answers in tabular structured corpora—Wikipedia infoboxes and relational tables, the dominant structured evidence in open-domain RAG—yet citation faithfulness methods remain designed for text passages. This mismatch allows LLMs to cite the correct table but the wrong row, silently aggregate values without justification, or attribute claims to schema fields that do not semantically entail them. We formalize multiple structural hallucination modes specific to structured-data attribution and introduce CiteAlign-Table, a hybrid neuro-symbolic verifier that checks schema-path validity, cell-level semantic alignment, and arithmetic consistency between claims and their cited records. A schema-aware entailment module detects entity and content misalignments, while a lightweight program synthesizer verifies numerical aggregation, temporal consistency, and unit correctness. Experiments on a hybrid benchmark of Wikipedia infoboxes and WikiTables show that CiteAlign-Table achieves 0.84 F1 in detecting unfaithful structured citations, while text-only baselines degrade to 0.61 F1. By extending citation faithfulness from passages to structured records, our work makes attributed QA trustworthy over the heterogeneous data that production RAG systems actually retrieve.

[Download paper here](https://github.com/Ashish-Gupta03/Ashish-Gupta03.github.io/blob/master/files/CIKM_CiteAlign.pdf)
