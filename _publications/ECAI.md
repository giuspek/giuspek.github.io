---
title: "Canonical Decision Diagrams Modulo Theories"
collection: publications
permalink: /publication/Disjoint-Partial-Enumeration-without-Blocking-Clauses
excerpt: ''
date: 2024-10-22
venue: 'ECAI24'
---

Decision diagrams (DDs) are powerful tools to represent effectively propositional formulas, which are largely used in many domains, in particular in formal verification and in knowledge compilation. Some forms of DDs (e.g., OBDDs, SDDs) are canonical, that is, (under given conditions on the atom list) they univocally represent equivalence classes of formulas. Given the limited expressiveness of propositional logic, a few attempts to leverage DDs to SMT level have been presented in the literature. Unfortunately, these techniques still suffer from some limitations: most procedures are theory-specific; some produce theory DDs (T-DDs) which do not univocally represent T-valid formulas or T-inconsistent formulas; none of these techniques provably produces theory-canonical T-DDs, which (under given conditions on the T-atom list) univocally represent T-equivalence classes of formulas. Also, these procedures are not easy to implement, and very few implementations are actually available. In this paper, we present a novel very-general technique to leverage DDs to SMT level, which has several advantages: it is very easy to implement on top of an AllSMT solver and a DD package, which are used as blackboxes; it works for every form of DDs and every theory, or combination thereof, supported by the AllSMT solver; it produces theory-canonical T-DDs if the propositional DD is canonical. We have implemented a prototype tool for both T-OBDDs and T-SDDs on top of OBDD and SDD packages and the MathSAT SMT solver. Some preliminary empirical evaluation supports the effectiveness of the approach.

[Download paper here](http://academicpages.github.io/files/ECAI24.pdf)