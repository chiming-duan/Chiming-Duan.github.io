---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div id="about-me" class="intro-panel">
  <p class="eyebrow">Ph.D. student · Peking University</p>
  <h1>Building reliable software and AI systems.</h1>
  <p>I am a Ph.D. student at the School of Software and Microelectronics, Peking University, advised by <strong>Prof. Ying Li</strong>. I received my master's degree in Software Engineering from Peking University in 2025 and my bachelor's degree in Computer Science and Technology from Beijing University of Posts and Telecommunications in 2022.</p>
  <p>My research brings AI into the software engineering lifecycle, with a focus on anomaly detection, root cause analysis, and failure management for software and AI systems.</p>
  <div class="research-tags" aria-label="Research interests"><span>AIOps</span><span>Root cause analysis</span><span>Log analysis</span><span>AI systems</span></div>
  <div class="intro-actions"><a href="mailto:duanchiming@stu.pku.edu.cn">Email me ↗</a><a href="https://scholar.google.com/citations?user=O8dm8OcAAAAJ">Google Scholar ↗</a></div>
</div>

<h2 id="news">Latest news</h2>
- *2026.10*: &nbsp;Our new survey, [Anomaly Detection in LLM-Based Systems: A Survey](https://method-notes.github.io/LLM-Anomaly-Detection-Survey/), is now available! We organize existing methods into **Boundary-Modeling AD** and **Alignment-Based AD**, covering five method families. Explore the preprint and an interactive directory of 181 taxonomy examples on the project website.
- *2026.09*: &nbsp;Our paper *Bifrost* has been accepted by **ASE 2026**.
- *2026.07*: &nbsp;Four papers were presented at **FSE 2026**, including our first-author paper *AIMS*.
- *2026.04*: &nbsp;Our papers *Agentic Memory* and *Hypothesize-Then-Verify* were presented at **ICSE 2026**.
- *2025.12*: &nbsp;*Agentic Memory* and *Hypothesize-Then-Verify* were accepted by **ICSE 2026**.
- *2025.09*: &nbsp;*LogAction*, *CollaborLog*, and *United We Stand* were accepted by **ASE 2025**.
- *2025.05*: &nbsp;My master's thesis was recommended as outstanding by the review experts.
- *2025.01*: &nbsp;Our work on web service anomaly detection was accepted by **WWW 2025**.
- *2025.01*: &nbsp;Our paper on weakly supervised log anomaly detection was accepted by **ICSE 2025**.
- *2024.12*: &nbsp;Our work was featured by [Alibaba Cloud’s official WeChat account](https://mp.weixin.qq.com/s/xJs3I9jyX-xkuUpRu7_NWg).
- *2024.11*: &nbsp;*FAMOS* was accepted by **ICSE 2025**.
- *2024.03*: &nbsp;*SOIL* was accepted by **WWW 2024** as an oral presentation.

<h2 id="publications">Publications</h2>
<p class="section-note">First- and co-first-author papers are shown first, newest first within each group. * denotes equal contribution.</p>

{% assign priority_papers = site.data.publications | where: "priority", true | sort: "sort_date" | reverse %}
{% assign other_papers = site.data.publications | where: "priority", false | sort: "sort_date" | reverse %}

<h3 class="year-heading" id="first-author-publications">First &amp; co-first author papers</h3>
<div class="publication-grid" aria-labelledby="first-author-publications">
{% for paper in priority_papers %}
  {% include publication-card.html paper=paper %}
{% endfor %}
</div>

<h3 class="year-heading" id="coauthored-publications">Other coauthored papers</h3>
<div class="publication-grid" aria-labelledby="coauthored-publications">
{% for paper in other_papers %}
  {% include publication-card.html paper=paper %}
{% endfor %}
</div>

<h2 id="service">Academic service</h2>
<h3>Peer review</h3>
- *2026*, ICWS, TSE
- *2025*, TNNLS, PeerJ, TCSVT

<h2 id="experience">Experience & recognition</h2>
<h3>Education</h3>
- *2025.06 - Present*, Ph.D. student, Peking University.
- *2022.09 - 2025.06*, Master's degree, Peking University.
- *2018.09 - 2022.06*, Bachelor's degree, Beijing University of Posts and Telecommunications.

<h3>Research internships</h3>
- *2025.01 - 2026.02*, Research intern, ByteDance, China.
- *2023.10 - 2024.10*, Research intern, Alibaba Cloud, China.
- *2022.10 - 2023.10*, Research intern, Microsoft Research Asia, China.

<h3>Honors and awards</h3>
- *2025* Outstanding Graduation Thesis.
- *2023* Peking University Excellent Student Award.
- *2022* Beijing Outstanding Graduate.
