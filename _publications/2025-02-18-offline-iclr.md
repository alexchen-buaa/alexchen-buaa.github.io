---
title: "Offline RL with Smooth OOD Generalization in Convex Hull and Its Neighborhood"
collection: publications
category: conferences
permalink: /publication/2025-02-18-offline-iclr
excerpt: ''
date: 2025-02-17
venue: 'International Conference on Learning Representations (ICLR) 2025'
paperurl: 'https://openreview.net/pdf?id=eY5JNJE56i'
citation: 'Qingmao Yao, Zhichao Lei, <span class="author-highlight">Tianyuan Chen</span>, Ziyue Yuan, Xuefan Chen, Jianxiang Liu, Faguo Wu, and Xiao Zhang. “Offline RL with Smooth OOD Generalization in Convex Hull and Its Neighborhood.” In International Conference on Learning Representations, 2025.'
---

Offline Reinforcement Learning (RL) struggles with distributional shifts, leading to the Q-value overestimation for out-of-distribution (OOD) actions. Existing methods address this issue by imposing constraints; however, they often become overly conservative when evaluating OOD regions, which constrains the Q-function generalization. This over-constraint issue results in poor Q-value estimation and hinders policy improvement. In this paper, we introduce a novel approach to achieve better Q-value estimation by enhancing Q-function generalization in OOD regions within Convex Hull and its Neighborhood (CHN). Under the safety generalization guarantees of the CHN, we propose the Smooth Bellman Operator (SBO), which updates OOD Q-values by smoothing them with neighboring in-sample Q-values. We theoretically show that SBO approximates true Q-values for both in-sample and OOD actions within the CHN. Our practical algorithm, Smooth Q-function OOD Generalization (SQOG), empirically alleviates the over-constraint issue, achieving near-accurate Q-value estimation. On the D4RL benchmarks, SQOG outperforms existing state-of-the-art methods in both performance and computational efficiency. Code is available at [https://github.com/yqpqry/SQOG](https://github.com/yqpqry/SQOG).
