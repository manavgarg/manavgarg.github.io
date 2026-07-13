---
layout: post
title: "From Dataflow to data agents: what distributed systems taught me about agent infrastructure"
---

<!-- DRAFT OUTLINE — files in _drafts/ never publish until moved to _posts/
     with a date in the filename. -->

Idea: your strongest "applied AI transition" story. Six years of Dataflow →
the problems agent infra is hitting now (state, exactly-once effects,
autoscaling, backpressure) are problems streaming systems solved a decade ago.

Possible sections:
- Agents are long-running, stateful, failure-prone workflows. So were
  streaming pipelines.
- Durable execution / resumption ≈ checkpointing and snapshots.
- Tool-call side effects ≈ exactly-once sinks.
- What's genuinely NEW in agent infra (non-determinism, evals as tests,
  context as a resource to schedule).
- Concrete lessons, each anchored in a real Dataflow war story (sanitized).
