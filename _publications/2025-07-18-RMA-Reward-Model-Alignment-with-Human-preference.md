---
title: "RMA: Reward Model Alignment with Human preference"
collection: publications
permalink: /ag-publication/RMA-Reward-Model-Alignment-with-Human-preference
excerpt: ''
date: 2025-07-18
venue: 'ICML 2025 Assessing World Models'
citation: '@inproceedings{
gupta2025rma,
title={{RMA}: Reward Model Alignment with Human preference},
author={Ashish Gupta and Manjunatha Naik MC},
booktitle={ICML 2025 Workshop on Assessing World Models},
year={2025},
url={https://openreview.net/forum?id=SMIDF8gbku}
}'
---

**Abstract:** Reward models (RMs) are essential for aligning large language models (LLMs) with human preferences. These models are typically trained on datasets containing an input prompt, two model-generated responses, and a preference label indicating which response is preferred. However, current approaches often suffer from limited generalization, exhibiting inconsistent performance across different contexts and displaying biases such as position bias (favoring the first response), verbosity bias (preferring longer outputs), or self-enhancement bias (favoring self-reinforcing statements).

In this work, we propose Preference Prediction, a novel framework that leverages high-quality preference data validated by human annotators along with open source data, combined with a preference selector trained via supervised fine-tuning (SFT), to dynamically choose the most suitable model for a given context. Through comprehensive experiments on a variety of datasets, we show that our proposed Reward Model Alignment (RMA) not only surpasses existing reward models in performance but also significantly boosts the effectiveness of other distinct reward models when applied to synthetic data. Additionally, RMA promotes the generation of more diverse and high-quality responses by integrating multiple quality dimensions—such as helpfulness, relevance, and completeness—into the prompting process.

[Download paper here](http://Ashish-Gupta03.github.io/files/17_RMA_Reward_Model_Alignment.pdf)
