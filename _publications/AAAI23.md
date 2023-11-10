---
title: "Enumerating Disjoint Partial Models without Blocking Clauses"
collection: publications
permalink: /publication/Enumerating-Disjoint-Partial-Models-without-Blocking-Clauses
excerpt: ''
date: 2023-06-01
venue: 'Under submission'
---
A basic algorithm for enumerating disjoint propositional models (disjoint AllSAT) is based on adding blocking clauses incrementally, ruling out previously found models. On the one hand, blocking clauses have the potential to reduce the number of generated models exponentially, as they can handle partial models. On the other hand, they need exponential space and slow down unit propagation. We propose a new approach that allows for enumerating disjoint partial models with no need for blocking clauses by integrating: Conflict-Driven Clause-Learning (CDCL), Chronological Backtracking (CB), and methods for shrinking models (Implicant Shrinking). Experiments clearly show the benefits of our novel approach.

[Download paper here](http://academicpages.github.io/files/AAAI23.pdf)