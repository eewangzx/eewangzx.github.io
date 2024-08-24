---
title: "GAN and Multi-Agent DRL based Decentralized Traffic Light Signal Control"
collection: publications
category: manuscripts
permalink: /publication/2015-10-01-paper-title-number-3
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2021-12-13
venue: 'IEEE Trans. Veh. Technol'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9647926'
citation: 'Z. Wang, H. Zhu, M. He, Y. Zhou, X. Luo, and N. Zhang. &quot;GAN and Multi-Agent DRL based Decentralized Traffic Light Signal Control.&quot; <i>IEEE Trans. Veh. Technol</i>. vol. 71, no. 2, pp. 1333-1348, Feb. 2022.'
---


Adaptive traffic light signal control (ATSC) is a promising paradigm for alleviating traffic congestion in intelligent transportation systems. Most of the existing methods require heavy traffic data exchange among neighboring intersections to achieve collaborative ATSC, which may not be supported by bandwidth-limited communication links in practice. In this article, we develop a communication-efficient decentralized ATSC framework for traffic networks with multiple intersections, where each intersection only exchanges traffic statistics with its neighboring intersections. In particular, the proposed framework consists of a generative adversarial network (GAN) based algorithm for traffic data recovery, and a multi-agent deep reinforcement learning (DRL) based decentralized ATSC algorithm for traffic efficiency enhancement. By adopting the value decomposition technique that establishes a nonlinear mapping from the local state-action values to the global reward, each intersection can independently determine its traffic light signal based on its local traffic data while achieving collaboration among neighboring intersections. Our proposed decentralized ATSC framework is scalable to large-scale traffic networks, and is also robust to traffic flow variations via interacting with the environment. Simulations show that our proposed algorithm can significantly reduce the vehicle travel time while maintaining high and stable traffic throughput.