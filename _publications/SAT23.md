---
title: "On CNF Conversion for Disjoint SAT Enumeration"
collection: publications
permalink: /publication/On-CNF-Conversion-for-Disjoint-SAT-Enumeration
excerpt: ''
date: 2023-08-09
venue: 'SAT23'
---
Modern SAT solvers are designed to handle problems expressed in Conjunctive Normal Form (CNF) so that non-CNF problems must be CNF-ized upfront, typically by using variants of either Tseitin or Plaisted and Greenbaum transformations. When passing from solving to enumeration, however, the capability of producing partial satisfying assignments that are as small as possible becomes crucial, which raises the question of whether such CNF encodings are also effective for enumeration.
In this paper, we investigate both theoretically and empirically the effectiveness of CNF conversions for SAT enumeration. On the negative side, we show that: (i) Tseitin transformation prevents the solver from producing short partial assignments, thus seriously affecting the effectiveness of enumeration; (ii) Plaisted and Greenbaum transformation overcomes this problem only in part. On the positive side, we show that combining Plaisted and Greenbaum transformation with NNF preprocessing upfront -- which is typically not used in solving -- can fully overcome the problem and can drastically reduce both the number of partial assignments and the execution time.

[Download paper here](http://academicpages.github.io/files/SAT23.pdf)