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
<p class="section-note">Selected conference papers, newest first. Titles link to the conference program.</p>

<h3 class="year-heading">2026</h3>
<div class="publication-grid">
  <article class="publication-card featured"><div class="publication-meta"><span>FSE 2026 · IVR</span><span>First author</span></div><h4><a href="https://conf.researchr.org/details/fse-2026/fse-2026-ideas-visions-and-reflections/11/AIMS-A-Content-Aware-Resource-Management-Approach-for-AI-Assistant-Systems">AIMS: A Content-Aware Resource Management Approach for AI Assistant Systems</a></h4><p><strong>Chiming Duan</strong>, Tong Jia, Minghua He, Pei Xiao, Lingzhe Zhang, Zhewei Zhong, Xin Zhang, Ying Li.</p><a class="publication-link" href="https://doi.org/10.1145/3803437.3805562">DOI ↗</a></article>
  <article class="publication-card"><div class="publication-meta"><span>ASE 2026 · Research</span></div><h4><a href="https://conf.researchr.org/track/ase-2026/ase-2026-research-track">Bifrost: Empowering Pretrained Language Model with Fallibility Representation for Log-Based Fault Diagnosis</a></h4><p>Minghua He, Tong Jia, Lingzhe Zhang, <strong>Chiming Duan</strong>, Xinlong Zhao, Leyi Pan, Cheng Wang, Kangjin Wang, Yinghao Yu, Liping Zhang, Yifan Wu, Ying Li.</p></article>
  <article class="publication-card"><div class="publication-meta"><span>FSE 2026 · Industry</span></div><h4><a href="https://conf.researchr.org/details/fse-2026/fse-2026-industry-papers/5/E2E-REME-Towards-End-to-End-Microservices-Auto-Remediation-via-Experience-Simulation">E2E-REME: Towards End-to-End Microservices Auto-Remediation via Experience-Simulation Reinforcement Fine-Tuning</a></h4><p>Lingzhe Zhang, Yunpeng Zhai, Tong Jia, Minghua He, <strong>Chiming Duan</strong>, Zhaoyang Liu, Bolin Ding, Ying Li.</p></article>
  <article class="publication-card"><div class="publication-meta"><span>FSE 2026 · IVR</span></div><h4><a href="https://conf.researchr.org/details/fse-2026/fse-2026-ideas-visions-and-reflections/8/RuntimeSlicer-Towards-Generalizable-Unified-Runtime-State-Representation-for-Failure">RuntimeSlicer: Towards Generalizable Unified Runtime State Representation for Failure Management</a></h4><p>Lingzhe Zhang, Tong Jia, Weijie Hong, Mingyu Wang, <strong>Chiming Duan</strong>, Minghua He, Rongqian Wang, Xi Peng, Meiling Wang, Nicholas Zhang, Renhai Chen, Ying Li.</p></article>
  <article class="publication-card"><div class="publication-meta"><span>FSE 2026 · IVR</span></div><h4><a href="https://conf.researchr.org/details/fse-2026/fse-2026-ideas-visions-and-reflections/9/Efficient-Failure-Management-for-Multi-Agent-Systems-with-Reasoning-Trace-Representat">Efficient Failure Management for Multi-Agent Systems with Reasoning Trace Representation</a></h4><p>Lingzhe Zhang, Tong Jia, Mingyu Wang, Weijie Hong, <strong>Chiming Duan</strong>, Minghua He, Rongqian Wang, Xi Peng, Meiling Wang, Nicholas Zhang, Renhai Chen, Ying Li.</p></article>
  <article class="publication-card"><div class="publication-meta"><span>ICSE 2026 · SEIP</span></div><h4><a href="https://conf.researchr.org/details/icse-2026/icse-2026-software-engineering-in-practice/4/Agentic-Memory-Enhanced-Recursive-Reasoning-for-Root-Cause-Localization-in-Microservi">Agentic Memory Enhanced Recursive Reasoning for Root Cause Localization in Microservices</a></h4><p>Lingzhe Zhang, Tong Jia, Yunpeng Zhai, Leyi Pan, <strong>Chiming Duan</strong>, Minghua He, Mengxi Jia, Ying Li.</p></article>
  <article class="publication-card"><div class="publication-meta"><span>ICSE 2026 · NIER</span></div><h4><a href="https://conf.researchr.org/details/icse-2026/icse-2026-nier/5/Hypothesize-Then-Verify-Speculative-Root-Cause-Analysis-for-Microservices-with-Pathw">Hypothesize-Then-Verify: Speculative Root Cause Analysis for Microservices with Pathwise Parallelism</a></h4><p>Lingzhe Zhang, Tong Jia, Yunpeng Zhai, Leyi Pan, <strong>Chiming Duan</strong>, Minghua He, Pei Xiao, Ying Li.</p></article>
</div>

<h3 class="year-heading">2025 and earlier</h3>

- 📑 <span style="color: #3b82f6;">*ASE'25 (CCF-A)*</span>,  <span>LogAction: Consistent Cross-system Anomaly Detection through Logs via Active Domain Adaptation.</span>
  - <span>**Chiming Duan\***, Minghua He\*, Pei Xiao\*, Tong Jia, Xin Zhang, Zhewei Zhong, Xiang Luo, Yan Niu, Lingzhe Zhang, Yifan Wu, Siyu Yu, Weijie Hong, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ASE'25 (CCF-A)*</span>,  <span>CollaborLog: Efficient-Generalizable Log Anomaly Detection via Large-Small Model Collaboration in Software Evolution.</span>
  - <span>Pei Xiao\*, **Chiming Duan\***, Minghua He\*, Tong Jia, Yifan Wu, Jing Xu, Gege Gao, Lingzhe Zhang, Weijie Hong, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ASE'25 (CCF-A)*</span>,  <span>United We Stand: Towards End-to-End Log-based Fault Diagnosis 
  via Interactive Multi-Task Learning.</span>
  - <span>Minghua He\*, **Chiming Duan\***, Pei Xiao\*, Tong Jia, Siyu Yu, Lingzhe Zhang, Weijie Hong, Jing Han, Yifan Wu, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*EMNLP-Findings'25*</span>,  <span>ICL-Bandit: Relevance Labeling in Advertisement Recommendation Systems via LLM.</span>
  - <span>Lu Wang, **Chiming Duan**, Pu Zhao, Fangkai Yang, Yong Shi, Xuefeng Luo, Bingjing Xu, Weiwei Deng, Qingwei Lin and Dongmei Zhang.</span>

- 📑 <span style="color: #3b82f6;">*ISSRE'25*</span>,  <span>CSLParser: A Collaborative Framework Using Small and Large Language Models for Log Parsing.</span>
  - <span>Weijie Hong, Yifan Wu, Lingzhe Zhang, **Chiming Duan**, Pei Xiao, Minghua He, Xixuan Yang and Ying Li.</span>

- 📑 <span style="color: #3b82f6;">*FSE-IVR'25*</span>,  <span>Agentfm: Role-aware failure management for distributed databases with llm-driven multi-agents.</span>
  - <span>Lingzhe Zhang, Yunpeng Zhai, Tong Jia, Xiaosong Huang, **Chiming Duan** and Ying Li.</span>

- 📑 <span style="color: #3b82f6;">*FSE-IVR'25*</span>,  <span>CLSLog: Collaborating Large and Small Models for Log-based Anomaly Detection.</span>
  - <span>Pei Xiao, Tong Jia, **Chiming Duan**, Minghua He, Weijie Hong, Xixuan Yang, Yihan Wu, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*WWW'25 (CCF-A)*</span>,  <span>Enhancing web service anomaly detection via fine-grained multi-modal association and frequency domain analysis.</span>
  - <span>Xixuan Yang, Xin Huang, **Chiming Duan**, Tong Jia, Shandong Dong, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ICASSP'25 (CCF-B)*</span>,  <span>EagerLog: Active Learning Enhanced Retrieval Augmented Generation for Log-based Anomaly Detection.</span>
  - <span>**Chiming Duan**, Tong Jia, Yong Yang, Guiyang Liu, Jinbu Liu, Huxing Zhang, Qi Zhou, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ICSE'25 (CCF-A)*</span>,  <span>FAMOS: Fault diagnosis for Microservice Systems through Effective Multi-modal Data Fusion.</span>
  - <span>**Chiming Duan**, Yong Yang, Tong Jia, Guiyang Liu, Jinbu Liu, Huxing Zhang, Qi Zhou, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ICSE'25 (CCF-A)*</span>,  <span>Weakly-Supervised Log-Based Anomaly Detection with Inexact Labels via Multi-Instance Learning.</span>
  - <span>Minghua He, Tong Jia, **Chiming Duan**, Huaqian Cai, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ISSRE'24 (CCF-B)*</span>,  <span>Logcae: An approach for log-based anomaly detection with active learning and contrastive learning.</span>
  - <span>Pei Xiao, Tong Jia, **Chiming Duan**, Huaqian Cai, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ISSRE'24 (CCF-B)*</span>,  <span>Llmelog: An approach for anomaly detection based on llm-enriched log events.</span>
  - <span>Minghua He, Tong Jia, **Chiming Duan**, Huaqian Cai, Ying Li and Gang Huang.</span>
  
- 📑 <span style="color: #3b82f6;">*WWW'24 (CCF-A)*</span>,  <span>Soil: Score conditioned diffusion model for imbalanced cloud failure prediction.</span>
  - <span>**Chiming Duan**, Fangkai Yang, Pu Zhao, Lingling Zheng, Yash Dagli, Yudong Liu, Qingwei Lin and Dongmei Zhang.</span>
  
- 📑 <span style="color: #3b82f6;">*ISSRE'23 (CCF-B)*</span>,  <span>Afalog: A general augmentation framework for log-based anomaly detection with active learning.</span>
  - <span>**Chiming Duan**, Tong Jia, Huaqian Cai, Ying Li and Gang Huang.</span>

- 📑 <span style="color: #3b82f6;">*ICWS'23 (CCF-B)*</span>,  <span>Aclog: An approach to detecting anomalies from system logs with active learning.</span>
  - <span>**Chiming Duan**, Tong Jia, Ying Li and Gang Huang.</span>



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
