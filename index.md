---
layout: default
title: Home
---

<div class="intro">
  <img class="portrait" src="/images/manav.png" alt="Manav Garg">
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
guts of large-scale streaming and batch systems. That background — making
distributed systems fast, correct, and boring at scale — is the lens I bring
to the current wave of AI infrastructure: agents are only as good as the data
systems underneath them.

I'm interested in the intersection of **large-scale systems and applied AI**:
agent runtimes and tooling, retrieval and context engines over structured data,
evaluation of agentic workflows, and program synthesis / learned optimization.

<h2 id="work">Work</h2>

A few public write-ups of what my team's product area has been shipping:

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/data-agent-kit-brings-data-skills-and-tools-to-your-ide-or-cli">Data Agent Kit: data skills and tools in your IDE or CLI</a></span>
  <span class="meta">· Google Cloud Blog, May 2026</span>
  <p>An open-source collection of agentic skills, MCP tools, and plugins that
  connect coding agents (VS Code, Claude Code, Codex, Gemini CLI, Antigravity)
  to BigQuery, AlloyDB, and the rest of the Data Cloud.</p>
</div>

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/new-data-agents-across-the-agentic-data-cloud">New data agents across the Agentic Data Cloud</a></span>
  <span class="meta">· Google Cloud Blog, June 2026</span>
  <p>Data Engineering, Data Science, Deep Research, and database agents —
  grounding agentic workflows in enterprise data with governance built in.</p>
</div>

<div class="item">
  <span class="title"><a href="https://cloud.google.com/blog/products/data-analytics/whats-new-in-the-agentic-data-cloud">What's new in the Agentic Data Cloud</a></span>
  <span class="meta">· Google Cloud Blog, April 2026</span>
  <p>The bigger picture: turning the data platform from a static repository
  into a reasoning engine for autonomous agents.</p>
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
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

<p><a href="{{ '/writing/' | relative_url }}">All writing &rarr;</a></p>

<h2 id="elsewhere">Off hours</h2>

Strong opinions about chai. Stronger opinions about Liverpool F.C.
