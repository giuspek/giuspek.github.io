---
title: "Enhancing SMT-based Weighted Model Integration by Structure Awareness"
collection: publications
permalink: /publication/Enhancing-SMT-based-Weighted-Model-Integration-by-Structure-Awareness
excerpt: ''
date: 2024-01-12
venue: 'AIJ'
---
The development of efficient exact and approximate algorithms for probabilistic inference is a long-standing goal of artificial intelligence research. Whereas substantial progress has been made in dealing with purely discrete or purely continuous domains, adapting the developed solutions to tackle hybrid domains, characterised by discrete and continuous variables and their relationships, is highly non-trivial. Weighted Model Integration (WMI) recently emerged as a unifying formalism for probabilistic inference in hybrid domains. Despite a considerable amount of recent work, allowing WMI algorithms to scale with the complexity of the hybrid problem is still a challenge. In this paper we highlight some substantial limitations of existing state-of-the-art solutions, and develop an algorithm that combines SMT-based enumeration, an efficient technique in formal verification, with an effective encoding of the problem structure. This allows our algorithm to avoid generating redundant models, resulting in drastic computational savings. Additionally, we show how SMT-based approaches can seamlessly deal with different integration techniques, both exact and approximate, significantly expanding the set of problems that can be tackled by WMI technology. An extensive experimental evaluation on both synthetic and real-world datasets confirms the substantial advantage of the proposed solution over existing alternatives. The application potential of this technology is further showcased on a prototypical task aimed at verifying the fairness of probabilistic programs.

[Download paper here](http://academicpages.github.io/files/AIJ23.pdf)