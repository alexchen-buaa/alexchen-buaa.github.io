---
title: "ACTIVE: Offline Reinforcement Learning via Adaptive Imitation and In-sample V-Ensemble"
collection: publications
category: conferences
permalink: /publication/2025-02-18-active-iclr
excerpt: ''
date: 2025-02-18
venue: 'International Conference on Learning Representations (ICLR) 2025'
paperurl: 'https://openreview.net/pdf?id=qiluFujVc8'
citation: '<span class="author-highlight">Tianyuan Chen</span>, Ronglong Cai, Faguo Wu, and Xiao Zhang. "ACTIVE: Offline Reinforcement Learning via Adaptive Imitation and In-Sample V-Ensemble." In International Conference on Learning Representations, 2025.'
---

Offline reinforcement learning (RL) aims to learn from static datasets and thus faces the challenge of value estimation errors for out-of-distribution actions. The in-sample learning scheme addresses this issue by performing implicit TD backups that does not query the values of unseen actions. However, pre-existing in-sample value learning and policy extraction methods suffer from over-regularization, limiting their performance on suboptimal or compositional datasets. In this paper, we analyze key factors in in-sample learning that might potentially hinder the use of a milder constraint. We propose Actor-Critic with Temperature adjustment and In-sample Value Ensemble (ACTIVE), a novel in-sample offline RL algorithm that leverages an ensemble of V-functions for critic training and adaptively adjusts the constraint level using dual gradient descent. We theoretically show that the V-ensemble suppresses the accumulation of initial value errors, thereby mitigating overestimation. Our experiments on the D4RL benchmarks demonstrate that ACTIVE alleviates overfitting of value functions and outperforms existing in-sample methods in terms of learning stability and policy optimality.