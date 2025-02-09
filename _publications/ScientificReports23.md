---
title: "Effective Prime Factorization via Quantum Annealing by Modular Locally-structured Embedding"
collection: publications
permalink: /publication/Effective-Prime-Factorization-via-Quantum-Annealing-by-Modular-Locally-structured-Embedding
excerpt: ''
date: 2023-10-26
venue: 'Scientific Reports - Nature'
---
This paper investigates novel techniques to solve prime factorization by quantum annealing (QA). Our contribution is twofold. First, we present a novel and very compact modular encoding of a binary multiplier circuit into the Pegasus architecture of current D-Wave QA devices. The key contribution is a compact encoding of a controlled full-adder into an 8-qubit module in the Pegasus topology, which we synthesized offline by means of Optimization Modulo Theories. This allows us to encode up to a 21*12-bit multiplier (and a 22*8-bit one) into the Pegasus 5760-qubit topology of current annealers. To the best of our knowledge, these are the largest factorization problems ever encoded into a quantum annealer. Second, we have investigated the problem of actually solving encoded PF problems by running an extensive experimental evaluation on a D-Wave Advantage 4.1 quantum annealer. In order to help the annealer in reaching the global minimum, in the experiments we introduced different approaches to initialize the multiplier qubits and adopted several performance enhancement techniques. Overall, exploiting all the encoding and solving techniques described in this paper, 8, 219, 999 = 32, 749 * 251 was the highest prime product we were able to factorize within the limits of our QPU resources. To the best of our knowledge, this is the largest number which was ever factorized by means of a quantum annealer, and, more generally, by a quantum device.

[Download paper here](http://academicpages.github.io/files/ScientificReports23.pdf)