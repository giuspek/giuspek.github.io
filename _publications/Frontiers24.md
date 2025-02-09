---
title: "Experimenting with D-Wave quantum annealers on prime factorization problems"
collection: publications
permalink: /publication/Experimenting-with-D-Wave-quantum-annealers-on-prime-factorization-problems
excerpt: ''
date: 2024-04-20
venue: 'Frontiers in Computer Science'
---
This paper builds on top of a paper we have published very recently, in which
we have proposed a novel approach to prime factorization (PF) by quantum
annealing, where 8, 219, 999 = 32, 749 × 251 was the highest prime product
we were able to factorize—which, to the best of our knowledge is the largest
number which was ever factorized by means of a quantum device. The series
of annealing experiments which led us to these results, however, did not follow
a straight-line path; rather, they involved a convoluted trial-and-error process,
full of failed or partially-failed attempts and backtracks, which only in the end
drove us to find the successful annealing strategies. In this paper, we delve into
the reasoning behind our experimental decisions and provide an account of
some of the attempts we have taken before conceiving the final strategies that
allowed us to achieve the results. This involves also a bunch of ideas, techniques,
and strategies we investigated which, although turned out to be inferior wrt.
those we adopted in the end,may instead provide insights to amore-specialized
audience of D-Wave users and practitioners. In particular, we show the following
insights: (i) di􀀀erent initialization techniques a􀀀ect performances, among which
flux biases are e􀀀ective when targeting locally-structured embeddings; (ii) chain
strengths have a lower impact in locally-structured embeddings compared to
problem relying on global embeddings; (iii) there is a trade-o􀀀 between broken
chain and excited CFAs, suggesting an incremental annealing o􀀀set remedy
approach based on the modules instead of single qubits. Thus, by sharing the
details of our experiences, we aimto provide insights into the evolving landscape
of quantum annealing, and help people access and e􀀀ectively use D-Wave
quantum annealers.

[Download paper here](http://academicpages.github.io/files/frontiers24.pdf)