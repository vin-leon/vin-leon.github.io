---
title: "Online Reinforcement Learning in Markov Decision Process Using Linear Programming"
collection: publications
category: conferences
permalink: /publication/2023-online-rl-lp
excerpt: 'Vincent Leon, S. Rasoul Etesami'
date: 2023-12-13
venue: '2023 62nd IEEE Conference on Decision and Control (CDC)'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

In this paper, we consider online reinforcement learning in episodic Markov decision process (MDP) with unknown transition function and stochastic rewards drawn from some fixed but unknown distribution. The learner aims to learn the optimal policy and minimize their regret over a finite time horizon through interacting with the environment. We devise a simple and efficient model-based algorithm that achieves $\tilde{O}(LX \sqrt{TA})$ regret with high probability, where $L$ is the episode length, $T$ is the number of episodes, and $X$ and $A$ are the cardinalities of the state space and the action space, respectively. The proposed algorithm, which is based on the concept of “optimism in the face of uncertainty”, maintains confidence sets of transition and reward functions and uses occupancy measures to connect the online MDP with linear programming. It achieves a tighter regret bound compared to the existing works that use a similar confidence set framework and improves computational effort compared to those that use a different framework but with a slightly tighter regret bound.

[publisher link](https://doi.org/10.1109/CDC49753.2023.10383839), [arXiv link](https://arxiv.org/abs/2304.00155)
