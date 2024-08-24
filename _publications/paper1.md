---
title: "A Graph Neural Network Learning Approach to Optimize RIS-Assisted Federated Learning"
collection: publications
category: manuscripts
permalink: /publication/paper1
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2023-01-30
venue: 'IEEE Trans. Commun.'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10032291'
citation: 'Z. Wang, Y. Zou, Q. An, Y. Zhou, Y. Shi, and M. Bennis. &quot;A Graph Neural Network Learning Approach to Optimize RIS-Assisted Federated Learning&quot; <i>IEEE Trans. Commun</i>. vol. 22, no. 9, pp. 6092-6106, Sept. 2023.'
---

Over-the-air federated learning (FL) is a promising privacy-preserving edge artificial intelligence paradigm, where over-the-air computation enables spectral-efficient model aggregation by achieving simultaneous communication and aggregation. However, due to limited transmit power, the performance of over-the-air FL is limited by the device with the worst channel condition toward the edge server. In this paper, we leverage reconfigurable intelligent surface (RIS) to mitigate the communication bottleneck of over-the-air FL and explicitly characterize the corresponding convergence upper bound. The convergence analysis illustrates the detrimental impact of the accumulated aggregation error over all rounds and inspires us to formulate a time-average transmission distortion minimization problem by jointly optimizing the transceiver and RIS phase-shifts. To reduce the computation complexity and enhance the model aggregation accuracy, we develop a graph neural network (GNN) based learning algorithm to directly map channel coefficients to the optimized network parameters. By exploiting permutation equivalence and invariance properties of graphs, the parameter dimension of the proposed algorithm is independent of the number of edge devices, which reduces the computational complexity and improves the algorithmic scalability. Simulations show that the proposed algorithm speeds up the computation by three orders of magnitude compared to the baselines, while achieving performance superiority and algorithmic robustness.