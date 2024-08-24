---
title: "Knowledge-Guided Learning for Transceiver Design in Over-the-Air Federated Learning"
collection: publications
category: manuscripts
permalink: /publication/paper3
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2022-07-27
venue: 'IEEE Trans. Wireless Commun.'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10032291'
citation: 'Y. Zou, Z. Wang, X. Chen, H. Zhou and Y. Zhou. &quot;Knowledge-Guided Learning for Transceiver Design in Over-the-Air Federated Learning&quot; <i>IEEE Trans. Wireless Commun.</i>. vol. 22, no. 1, pp. 270-285, Jan. 2023.'
---

In this paper, we consider communication-efficient over-the-air federated learning (FL), where multiple edge devices with non-independent and identically distributed datasets perform multiple local iterations in each communication round and then concurrently transmit their updated gradients to an edge server over the same radio channel for global model aggregation using over-the-air computation (AirComp). We derive the upper bound of the time-average norm of the gradients to characterize the convergence of AirComp-assisted FL, which reveals the impact of the model aggregation errors accumulated over all communication rounds on convergence. Based on the convergence analysis, we formulate an optimization problem to minimize the upper bound to enhance the learning performance, followed by proposing an alternating optimization algorithm to facilitate the transceiver design for AirComp-assisted FL. As the alternating optimization algorithm suffers from high computation complexity, we further develop a knowledge-guided learning algorithm that exploits the structure of the analytic expression of the transmit power to achieve computation-efficient transceiver design. Simulation results demonstrate that the proposed knowledge-guided learning algorithm achieves a comparable performance as the alternating optimization algorithm, but with a much lower computation complexity. Moreover, both proposed algorithms outperform the baseline methods in terms of convergence speed and test accuracy.