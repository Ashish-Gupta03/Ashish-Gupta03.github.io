
---
title: "Hyperparameter optimization with REINFORCE and Transformers"
collection: publications
permalink: /ag-publication/Hyperparameter-Optimization
excerpt: ''
date: 2020-10-20
venue: 'IEEE BigData 2020'
citation: 'C. Krishna, A. Gupta, S. Narayan, H. Rai, D. Manchanda, "IEEE BigData2020" BigData2020'
---

**Abstract:** Reinforcement Learning has yielded promising results for Neural Architecture Search (NAS). In this paper, we demonstrate how its performance can be improved by using a simplified Transformer block to model the policy network. The simplified Transformer uses a 2-stream attention-based mechanism to model hyper-parameter dependencies while avoiding layer normalization and position encoding. We posit that this parsimonious design balances model complexity against expressiveness, making it suitable for discovering optimal architectures in high-dimensional search spaces with limited exploration budgets. We demonstrate how the algorithm’s performance can be further improved by a) using an actor-critic style algorithm instead of plain vanilla policy gradient and b) ensembling Transformer blocks with shared parameters, each block conditioned on a different auto-regressive factorization order. Our algorithm works well as both a NAS and generic hyper-parameter optimization (HPO) algorithm: it outperformed most algorithms on NAS-Bench-101, a public data-set for benchmarking NAS algorithms. In particular, it outperformed RL based methods that use alternate architectures to model the policy network, underlining the value of using attentionbased networks in this setting. As a generic HPO algorithm, it outperformed Random Search in discovering more accurate multi-layer perceptron model architectures across 2 regression tasks.


