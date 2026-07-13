---
layout: default
title: Home
---

<div class="intro">
  <img class="portrait" src="/images/manav.jpg" alt="Manav Garg">
  <div>
    <h1>Hi, I'm Manav.</h1>
    <p class="lede">
      I'm a software engineer at Google, where I work on the
      <strong>Data Cloud Frontier</strong> team building agentic AI systems on
      top of Google's Data Cloud &mdash; the infrastructure that lets AI agents
      reason over and act on enterprise data.
    </p>
  </div>
</div>

Before this, I spent about six years on [Cloud Dataflow](https://cloud.google.com/dataflow),
Google's planet-scale distributed data processing service, working deep in the
guts of large-scale streaming and batch systems and contributing to
[Apache Beam](https://beam.apache.org/) along the way. That background —
making distributed systems fast, correct, and boring at scale — is the lens I
bring to the current wave of AI infrastructure: agents are only as good as the
data systems underneath them.

I'm interested in the intersection of **large-scale systems and applied AI**:
agent runtimes and tooling, retrieval and context engines over structured data,
evaluation of agentic workflows, and program synthesis / learned optimization.

<h2 id="work">Work</h2>

Some of my work, in public:

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/evaluate-agent-performance">Frontier and Center: Who evaluates the evaluations?</a></span>
  <span class="meta">· Google Cloud Blog, July 2026 · with Sunil Pedapudi</span>
  <p>Introduces Discovery Bench, an information-theoretic meta-benchmark for
  data-discovery agents. Instead of subjective "easy/hard" labels, it
  quantifies query difficulty in bits of surprisal and generates controlled
  variations of each query — producing capability maps that show exactly
  where an agent's performance falls off a cliff. Along the way it surfaced
  mislabeled ground truth in existing benchmarks and some counterintuitive
  sweet spots where moderate ambiguity beats maximum specificity.</p>
</div>

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/manage-your-dataflow-jobs-at-scale-with-dataflow-pipelines/">Dataflow Pipelines, deploy and manage data pipelines at scale</a></span>
  <span class="meta">· Google Cloud Blog, October 2021 · with Shan Kulandaivel</span>
  <p>Launch of a management plane for data pipelines: a logical abstraction
  over Dataflow jobs with recurring-job scheduling, SLO tracking with native
  alerting, and aggregated health metrics across projects and pipelines.</p>
</div>

<div class="item">
  <span class="title"><a href="https://github.com/manavgarg">Apache Beam contributions</a></span>
  <span class="meta">· open source</span>
  <p>Contributions to Apache Beam, the programming model behind Dataflow.</p>
</div>

<h2 id="publications">Publications</h2>

<div class="item">
  <span class="title"><a href="https://arxiv.org/abs/2312.08472">AutoNumerics-Zero: Automated Discovery of State-of-the-Art Mathematical Functions</a></span>
  <span class="meta">· ICML 2026</span>
  <p>Esteban Real, Yao Chen, Mirko Rossini, Connal de Souza, <strong>Manav
  Garg</strong>, Akhil Verghese, Moritz Firsching, Quoc V. Le, Ekin Dogus
  Cubuk, David H. Park.</p>
  <p class="meta">
    <a href="https://arxiv.org/abs/2312.08472">arXiv</a> ·
    <a href="https://openreview.net/forum?id=n7F2nwPcYB">OpenReview</a> ·
    <a href="https://github.com/google-deepmind/autonumerics_zero">Code</a> ·
    <a href="{{ site.scholar_url }}">Google Scholar</a>
  </p>
</div>

<h2 id="writing">Writing</h2>

<ul class="post-list">
  {% for post in site.posts limit: 5 %}
  <li>
    <span class="date">{{ post.date | date: "%b %-d, %Y" }}</span>
    <span>
      {% if post.external_url %}
      <a href="{{ post.external_url }}">{{ post.title }}</a>
      <span class="meta">&nearr; {{ post.source }}</span>
      {% else %}
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {% endif %}
    </span>
  </li>
  {% endfor %}
</ul>

<p><a href="{{ '/writing/' | relative_url }}">All writing &rarr;</a></p>

<h2 id="elsewhere">Off hours</h2>

Strong opinions about chai. Stronger opinions about Liverpool F.C.
