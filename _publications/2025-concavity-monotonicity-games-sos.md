---
title: "Certifying Concavity and Monotonicity in Games via Sum‑of‑Squares Hierarchies"
collection: publications
category: preprints
permalink: /publication/2025-concavity-monotonicity-games-sos
excerpt: 'Vincent Leon, Iosif Sakos, Ryann Sim, and Antonios Varvitsiotis'
date: 2025-05-15
venue: 'Preprint, accepted to NeurIPS 2025'
---

Concavity and its refinements underpin tractability in multiplayer games, where players independently choose actions to maximize their own payoffs which depend on other players’ actions.  In _concave_ games, where players' strategy sets are compact and convex, and their payoffs are concave in their own actions, strong guarantees follow: Nash equilibria always exist and decentralized algorithms converge to equilibria. If the game is furthermore _monotone_, an even stronger guarantee holds: Nash equilibria are unique under strictness assumptions. Unfortunately, we show that _certifying_ concavity or monotonicity is NP-hard, already for games where utilities are multivariate polynomials and compact, convex basic semialgebraic strategy sets --- an expressive class that captures extensive-form games with imperfect recall. On the positive side, we develop two hierarchies of sum-of-squares programs that certify concavity and monotonicity of a given game, and each level of the hierarchies can be solved in polynomial time. We show that almost all concave/monotone games are certified at some finite level of the hierarchies. Subsequently, we introduce the classes of SOS-concave/monotone games, which  globally approximate concave/monotone games, and show that for any given game we can compute the closest SOS-concave/monotone game in polynomial time. Finally, we apply our techniques to canonical examples of extensive-form games with imperfect recall.

[OpenReview](https://openreview.net/forum?id=8ftsTxZOLQ)
