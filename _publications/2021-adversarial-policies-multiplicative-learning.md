---
title: "Optimal Adversarial Policies in the Multiplicative Learning System With a Malicious Expert"
collection: publications
category: manuscripts
permalink: /publication/2021-adversarial-policies-multiplicative-learning
excerpt: 'S. Rasoul Etesami, Negar Kiyavash, Vincent Leon, H. Vincent Poor'
date: 2021-01-18
venue: 'IEEE Transactions on Information Forensics and Security'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

In this paper, we consider a learning system based on the conventional multiplicative weight (MW) rule that combines experts' advice to predict a sequence of true outcomes. It is assumed that one of the experts is malicious and aims to impose the maximum loss on the system. The system's loss is naturally defined to be the aggregate absolute difference between the sequence of predicted outcomes and the true outcomes. We consider this problem under both offline and online settings. In the offline setting where the malicious expert must choose its entire sequence of decisions a priori, we show somewhat surprisingly that a simple greedy policy of always reporting false prediction is asymptotically optimal with an approximation ratio of $1+O\sqrt{(\ln N)/N}$, where $N$ is the total number of prediction stages. In particular, we describe a policy that closely resembles the structure of the optimal offline policy. For the online setting where the malicious expert can adaptively make its decisions, we show that the optimal online policy can be efficiently computed by solving a dynamic program in $O(N^3)$. We also discuss a generalization of our model to multi-expert settings. Our results provide a new direction for vulnerability assessment of commonly-used learning algorithms to internal adversarial attacks.

[publisher link](https://doi.org/10.1109/TIFS.2021.3052360), [arXiv link](https://arxiv.org/abs/2001.00543)
