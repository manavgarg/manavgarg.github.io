---
layout: post
title: "AutoNumerics-Zero at ICML 2026"
---

A paper I co-authored, [AutoNumerics-Zero: Automated Discovery of
State-of-the-Art Mathematical Functions](https://arxiv.org/abs/2312.08472),
appeared at ICML 2026 in Seoul this month.

The question behind it: computers approximate transcendental functions like
`exp(x)` using implementations that humans have refined over decades. Can a
search process discover better ones from scratch, with no knowledge of
asymptotics, perturbation theory, or any classical approximation method?

AutoNumerics-Zero is an evolutionary system that starts from empty code and,
using only simple operations, evolves programs that trade off precision
against efficiency. When full 64-bit precision isn't required (increasingly
the regime that matters for ML workloads), the discovered programs can reach
orders of magnitude more precision than classical approaches for the same
operation budget.

This was a collaboration with colleagues across Google DeepMind and Google
Research: Esteban Real, Yao Chen, Mirko Rossini, Connal de Souza, Akhil
Verghese, Moritz Firsching, Quoc V. Le, Ekin Dogus Cubuk, and David H. Park.

Links: [arXiv](https://arxiv.org/abs/2312.08472) ·
[OpenReview](https://openreview.net/forum?id=n7F2nwPcYB) ·
[code](https://github.com/google-deepmind/autonumerics_zero)
