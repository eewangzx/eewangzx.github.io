---
title: "Decentralized Multi-Agent Power Control in Wireless Networks with Frequency Reuse"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2021-12-14
venue: 'IEEE Trans. Commun.'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9650909'
citation: 'Z. Wang, J. Zong, Y. Zhou, Y. Shi, and V. W.S. Wong.. &quot;Decentralized Multi-Agent Power Control in Wireless Networks with Frequency Reuse&quot; <i>IEEE Trans. Commun</i>. vol. 70, no. 3, pp. 1666-1681, Mar. 2022.'
---

Many of the existing optimization-based transmit power control algorithms suffer from high computational complexity and require instantaneous global channel state information (CSI), both of which hinder their practical implementation. In this paper, we consider a wireless network with multiple transmitter-receiver pairs, where each transmitter only has access to its local CSI fed back from its intended receiver and does not require local CSI exchange with its neighboring transmitters. In such a network scenario, we propose a deep reinforcement learning based decentralized multi-agent power control (DEC-MAPC) algorithm for sum-rate maximization, where each transmitter acts as an intelligent agent. By leveraging the value decomposition technique, we establish a nonlinear mapping from the local reward of each agent to the global reward. Such a design allows each agent to independently control its transmit power based on its local CSI while enabling global collaboration among the agents. The proposed algorithm is scalable to large-scale networks as only local CSI is required, and is robust to the channel and interference variations via interacting with the environment. Simulation results show that the proposed DEC-MAPC algorithm with local CSI achieves comparable sum-rate performance with the centralized optimization algorithms with global CSI, while significantly reducing the computational complexity.