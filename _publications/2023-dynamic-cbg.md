---
title: "Online Learning in Budget-Constrained Dynamic Colonel Blotto Games"
collection: publications
category: manuscripts
permalink: /publication/2023-dynamic-cbg
excerpt: 'Vincent Leon, S. Rasoul Etesami'
date: 2023-07-27
venue: 'Dynamic Games and Applications'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://link.springer.com/article/10.1007/s13235-023-00518-7'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
In this paper, we study the strategic allocation of limited resources using a Colonel Blotto game (CBG) under a dynamic setting and analyze the problem using an online learning approach. In this model, one of the players is a learner who has limited troops to allocate over a finite time horizon, and the other player is an adversary. In each round, the learner plays a one-shot Colonel Blotto game with the adversary and strategically determines the allocation of troops among battlefields based on past observations. The adversary chooses its allocation action randomly from some fixed distribution that is unknown to the learner. The learner’s objective is to minimize its regret, which is the difference between the cumulative reward of the best mixed strategy and the realized cumulative reward by following a learning algorithm while not violating the budget constraint. The learning in dynamic CBG is analyzed under the framework of combinatorial bandits and bandits with knapsacks. We first convert the budget-constrained dynamic CBG to a path planning problem on directed graph. We then devise an efficient algorithm that combines a special combinatorial bandit algorithm for path planning problem and a bandits with knapsack algorithm to cope with the budget constraint. The theoretical analysis shows that the learner’s regret is bounded by a term sublinear in time horizon and polynomial in other parameters. Finally, we justify our theoretical results by carrying out simulations for various scenarios.

[publisher link](https://doi.org/10.1007/s13235-023-00518-7), [arXiv link](https://arxiv.org/abs/2103.12833)
