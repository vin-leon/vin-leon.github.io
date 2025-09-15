---
title: "Online Learning for Dynamic Vickrey-Clarke-Groves Mechanism in Sequential Auctions under Unknown Environments"
collection: publications
category: preprints
permalink: /publication/2025-online-learning-vcg
excerpt: 'Vincent Leon, S. Rasoul Etesami'
date: 2025-06-23
venue: 'arXiv Preprint'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

In this paper, we consider the problem of online dynamic mechanism design for sequential auctions in unknown environments, where the underlying market and, thus, the bidders' values vary over time as interactions between the seller and the bidders progress. We model the sequential auctions as an infinite-horizon average-reward Markov decision process (MDP). In each round, the seller determines an allocation and sets a payment for each bidder, while each bidder receives a private reward and submits a sealed bid to the seller. The state, which represents the underlying market, evolves according to an unknown transition kernel and the seller's allocation policy without episodic resets. We first extend the Vickrey-Clarke-Groves (VCG) mechanism to sequential auctions, thereby obtaining a dynamic counterpart that preserves the desired properties: efficiency, truthfulness, and individual rationality. We then focus on the online setting and develop a reinforcement learning algorithm for the seller to learn the underlying MDP and implement a mechanism that closely resembles the dynamic VCG mechanism. We show that the learned mechanism approximately satisfies efficiency, truthfulness, and individual rationality and achieves guaranteed performance in terms of various notions of regret.

[arXiv link](https://arxiv.org/abs/2506.19038)
