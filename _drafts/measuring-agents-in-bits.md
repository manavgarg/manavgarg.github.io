---
layout: post
title: "Measuring agents in bits: the ideas behind Discovery Bench"
---

<!-- DRAFT OUTLINE — move to _posts/ with a date to publish. -->

Idea: the personal, deeper companion to the Google Cloud blog post
(cloud.google.com/blog/products/data-analytics/evaluate-agent-performance).
The official post is product-voiced; this one can be your voice — the
intuition, the dead ends, the parts that didn't fit.

Possible sections:
- Why pass/fail evals lie: two agents with the same score, wildly different
  failure surfaces.
- Surprisal as a difficulty dial: the intuition behind quantifying query
  difficulty in bits instead of "easy/medium/hard" vibes.
- iSQR: generating controlled query variations, and why iteration matters.
- The meta-lesson: we found mislabeled ground truth in the benchmarks we
  started from — evaluate your evaluator.
- The "sweet spot" result: why moderate ambiguity sometimes beats maximum
  specificity, and what that says about how agents retrieve.
- What this borrows from systems thinking: capability maps as load testing
  for agents.
