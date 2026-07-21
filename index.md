---
layout: default
title: Home
---

<div class="intro">
  <img class="portrait" src="/images/manav.jpg" alt="Manav Garg">
  <div>
    <h1>Hi, I'm Manav.</h1>
    <p class="lede">
      I work at Google on the <strong>Data Cloud Frontier AI</strong> team,
      building multi-agent deep research systems over enterprise data, along
      with the evaluation methodology to know whether they actually work.
    </p>
  </div>
</div>

My interests are in **AI, both applied and research**: multi-agent systems,
agent quality and evaluation, and learned optimization / program synthesis.
What I bring to it is nearly a decade of building large-scale distributed
systems, the infrastructure this generation of AI runs on.

Before joining the Frontier AI team, I worked on
[Cloud Dataflow](https://cloud.google.com/dataflow), Google's planet-scale
data processing service, and before that built big-data infrastructure at
Nutanix. That work was about making distributed systems fast, correct, and
boring at scale, and it shapes how I look at AI infrastructure: agents are
only as good as the data systems underneath them.

<h2 id="research">Research &amp; writing</h2>

<div class="item">
  <span class="title"><a href="https://arxiv.org/abs/2312.08472">AutoNumerics-Zero: Automated Discovery of State-of-the-Art Mathematical Functions</a></span>
  <span class="meta">· ICML 2026</span>
  <p>Evolutionary search that discovers transcendental function
  implementations from empty code, beating classical approximation methods
  at limited precision. Our entry won the Gold Award at the 23rd annual
  <a href="https://www.human-competitive.org/23rd-annual-humies-awards-san-jose-costa-rica">Humies</a>,
  the GECCO awards for human-competitive results produced by evolutionary
  computation.</p>
  <p class="meta">
    <a href="https://arxiv.org/abs/2312.08472">arXiv</a> ·
    <a href="https://openreview.net/forum?id=n7F2nwPcYB">OpenReview</a> ·
    <a href="https://github.com/google-deepmind/autonumerics_zero">Code</a> ·
    <a href="https://www.human-competitive.org/23rd-annual-humies-awards-san-jose-costa-rica">Humies Gold Award</a>
  </p>
</div>

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/evaluate-agent-performance">Frontier and Center: Who evaluates the evaluations?</a></span>
  <span class="meta">· Google Cloud Blog, July 2026</span>
  <p>Introduces Discovery Bench: query difficulty quantified in bits of
  surprisal rather than "easy/hard" vibes, controlled query variations, and
  capability maps that expose exactly where agent performance falls off a
  cliff. The approach also surfaced mislabeled ground truth in existing
  benchmarks, and sweet spots where moderate ambiguity beats maximum
  specificity.</p>
</div>

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/manage-your-dataflow-jobs-at-scale-with-dataflow-pipelines/">Dataflow Pipelines, deploy and manage data pipelines at scale</a></span>
  <span class="meta">· Google Cloud Blog, October 2021</span>
  <p>Launch post for the Dataflow Pipelines management plane.</p>
</div>

<h2 id="work">Work</h2>

<div class="item">
  <span class="title">Google</span>
  <span class="meta">· 2020 – current</span>
  <div class="subitem">
    <span class="subtitle">Data Cloud Frontier AI</span>
    <p>Building multi-agent deep research agents over enterprise data:
    systems where specialized agents plan, retrieve, and reason together over
    governed data estates. My focus is agent quality and evaluation:
    information-theoretic benchmark generation for data-discovery agents
    (<a href="https://cloud.google.com/blog/products/data-analytics/evaluate-agent-performance">Discovery
    Bench</a>), capability maps that localize failure modes instead of
    averaging them away, and the eval methodology behind shipping agentic
    products.</p>
  </div>
  <div class="subitem">
    <span class="subtitle">Cloud Dataflow</span>
    <p>Tech lead in Dataflow's service &amp; platform area. Took two products
    from zero to launch:
    <a href="https://cloud.google.com/blog/products/data-analytics/manage-your-dataflow-jobs-at-scale-with-dataflow-pipelines/">Data
    Pipelines</a> (grew past 1,000 external customer accounts at 4x YoY) and
    Google Managed Flink (through Public Preview). Also worked on enabling
    Dataflow in Trusted Private Cloud environments and contributed to
    <a href="https://beam.apache.org/">Apache Beam</a> in open source.</p>
  </div>
</div>

<div class="item">
  <span class="title">Nutanix</span>
  <span class="meta">· 2017 – 2020</span>
  <p>Built a fault-tolerant big-data insights platform connecting on-prem
  telemetry to cloud analytics pipelines. Owned the cloud metering &amp;
  billing service (HA, monitored, audit-trailed) and contributed to the
  real-time alerting engine built on Spark SQL.</p>
</div>

<div class="item">
  <span class="title">Education</span>
  <span class="meta"></span>
  <p>M.S., University of Wisconsin–Madison<br>
  B.E., BITS Pilani</p>
</div>

<h2 id="elsewhere">Off hours</h2>

Runs on chai. Never walks alone on matchdays.
