---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I’m Xueqi Cheng, a Ph.D. student in [Computer Science](https://www.cs.fsu.edu/) at [Florida State University](https://www.fsu.edu/), advised by [Dr. Yushun Dong](https://yushundong.github.io/) in the Responsible AI (RAI) Lab. I have published first-author papers at top venues including **NeurIPS**, **KDD** (Oral), and **WSDM**, and co-authored papers at **ICLR** and in journals including **ACM Computing Surveys**, **IEEE TKDE**, and **ACM TIST**. I have conducted industrial research as a research intern at **Nokia Applied Research** and **AT&T Labs**. I have received awards including the **Naaman Franklin Faile Jr. Graduate Fellowship**, the **Osher Lifelong Learning Institute Scholarship**, the **IBM PhD Fellowship**, and the **WSDM NSF Travel Award**, and I serve as a reviewer for venues such as NeurIPS, ICML, KDD, and WWW.

Feel free to drop me an [Email](mailto:xc25@fsu.edu) if you are interested in collaboration!

## Research Interests

- **Agentic AI**: agent distillation, which transfers the capabilities of large LLM-based agents into smaller and more efficient models, and model routing, which dispatches each query to the most suitable model.
- **LLM Compression**: making LLMs cheaper to deploy and serve through knowledge distillation, pruning, quantization, and related techniques.
- **Multimodal Models**: improving the capability, efficiency, and reliability of multimodal large language models (MLLMs).
- **AI for Social Good and Real-World Applications**: applying AI to societally important problems, including social network analysis and civil and infrastructure engineering.

## Selected Publications

<div class="selected-pubs">
{% assign selected = site.data.publications | where: "selected", true %}
{% for p in selected %}{% include pub-entry.html pub=p %}{% endfor %}
</div>

<p class="pub-footnote"><sup>&#42;</sup> Equal contribution. See the <a href="/publications/">full publication list</a>.</p>

## News

- **[10/2026]** 📄 Our preprint [**HazardWeaver: Scientific Route Selection for Hazard Analysis Agents**](https://arxiv.org/abs/2610.03591) is now available online!
- **[10/2026]** 📄 Our preprint [**Capability Scaling-Down Laws for LLM Compression**](https://arxiv.org/abs/2610.02462) is now available online!
- **[09/2026]** 🎉 Our paper [**LatentRouter: Can We Choose the Right Multimodal Large Language Model Before Seeing Its Answer?**](https://arxiv.org/abs/2605.11301) has been accepted at **NeurIPS'26**!
- **[09/2026]** 🎉 Our survey [**Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey**](https://dl.acm.org/doi/10.1145/3837074) has been published in **ACM Computing Surveys**!
- **[06/2026]** 📄 Our preprint [**Adverse Online Social Interactions: A Multi-Level Evolutionary Analysis of Local Patterns, Diffusion, and Community Disruption**](https://arxiv.org/abs/2606.20846) is now available online!
- **[06/2026]** 📄 Our preprint [**A Nationwide Benchmark for Wildfire Initial Attack Failure Prediction with Public Environmental Data**](https://arxiv.org/abs/2606.15529) is now available online!
- **[05/2026]** 🎯 Excited to join **Nokia Applied Research** as a research intern working on agent distillation!
- **[05/2026]** 📄 Our preprint [**ReAD: Reinforcement-Guided Capability Distillation for Large Language Models**](https://arxiv.org/abs/2605.11290) is now available online!


<details>
  <summary style="cursor: pointer;"><strong>More News</strong></summary>
  
  <ul style="padding-left: 20px; margin-top: 10px;">
    <li><strong>[05/2026]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2605.11301"><strong>LatentRouter: Can We Choose the Right Multimodal Large Language Model Before Seeing Its Answer?</strong></a> is now available online!</li>
    <li><strong>[05/2026]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2605.11317"><strong>SOMA: Efficient Multi-turn LLM Serving via Small Language Model</strong></a> is now available online!</li>
    <li><strong>[04/2026]</strong> 🏅 Received the <strong>Osher Lifelong Learning Institute Scholarship</strong> from Florida State University!</li>
    <li><strong>[01/2026]</strong> 🏅 Received the <strong>NSF Travel Award</strong> for WSDM'26, see you in Boise!</li>
    <li><strong>[01/2026]</strong> 🌋 Our open-source Python library <a href="https://labrai.github.io/PyHazards/"><strong>PyHazards</strong></a> is now online! PyHazards is an AI-based toolkit for natural hazard prediction, and we’d love to collaborate, get feedback, and welcome contributions!</li>
    <li><strong>[11/2025]</strong> 🏅 Won the <strong>Best Presentation Runner-Up</strong> at the FSU CS Student Seminar!</li>
    <li><strong>[09/2025]</strong> 🏅 Received the <strong>Naaman Franklin Faile Jr. Graduate Fellowship</strong> from Florida State University!</li>
    <li><strong>[06/2025]</strong> 📄 Our paper <a href="https://arxiv.org/abs/2506.02362"><strong>MISLEADER: Defending against Model Extraction with Ensembles of Distilled Models</strong></a> is now available online!</li>
    <li><strong>[06/2025]</strong> 🎯 Excited to join <strong>AT&amp;T Labs</strong> as a research intern to enhance the serviceability of Large Language Models (LLMs).</li>
    <li><strong>[05/2025]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2505.01698"><strong>Amplifying Your Social Media Presence: Personalized Influential Content Generation with LLMs</strong></a> is now available online!</li>
    <li><strong>[05/2025]</strong> 🎉 Our paper <a href="https://arxiv.org/abs/2410.19214"><strong>BTS: A Comprehensive Benchmark for Tie Strength Prediction</strong></a> has been accepted for an <strong>oral</strong> presentation at <strong>KDD’25</strong>!</li>
    <li><strong>[02/2025]</strong> 📄 Our survey <a href="https://arxiv.org/abs/2502.06872"><strong>Towards Trustworthy Retrieval Augmented Generation for Large Language Models: A Survey</strong></a> is now available online!</li>
    <li><strong>[11/2024]</strong> 🎉 Our paper <a href="https://dl.acm.org/doi/abs/10.1145/3701551.3707418"><strong>Edge-Centric Network Analytics</strong></a> has been accepted at <strong>WSDM'25 Doctoral Consortium</strong>!</li>
    <li><strong>[10/2024]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2410.19214"><strong>A Comprehensive Analysis of Social Tie Strength: Definitions, Prediction Methods, and Future Directions</strong></a> is now available online!</li>
    <li><strong>[10/2024]</strong> 🎉 Our paper <a href="https://dl.acm.org/doi/10.1145/3701551.3703518"><strong>Edge Classification on Graphs: New Directions in Topological Imbalance</strong></a> has been accepted at <strong>WSDM'25</strong>!</li>
    <li><strong>[08/2024]</strong> 🎉 Our paper <a href="https://arxiv.org/abs/2308.16375"><strong>A Survey on Privacy in Graph Neural Networks: Attacks, Preservation, and Applications</strong></a> has been accepted by <strong>IEEE TKDE</strong>!</li>
    <li><strong>[04/2024]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2406.11685"><strong>Edge Classification on Graphs: New Directions in Topological Imbalance</strong></a> is now available online!</li>
    <li><strong>[04/2024]</strong> 🎉 Our paper <a href="https://arxiv.org/abs/2307.04644"><strong>Fairness and Diversity in Recommender Systems: A Survey</strong></a> has been accepted by <strong>ACM TIST</strong>!</li>
    <li><strong>[01/2024]</strong> 🎉 Our paper <a href="https://arxiv.org/abs/2310.04612"><strong>A Topological Perspective on Demystifying GNN-Based Link Prediction Performance</strong></a> has been accepted at <strong>ICLR'24</strong>!</li>
    <li><strong>[11/2023]</strong> 📝 Invited to serve as the Publicity Chair for <strong>The 5th International Workshop on Machine Learning on Graphs (MLoG)</strong> at <strong>WSDM’24</strong>!</li>
    <li><strong>[10/2023]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2310.04612"><strong>A Topological Perspective on Demystifying GNN-Based Link Prediction Performance</strong></a> is now online!</li>
    <li><strong>[08/2023]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2308.16375"><strong>A Survey on Privacy in Graph Neural Networks: Attacks, Preservation, and Applications</strong></a> is now online!</li>
    <li><strong>[08/2023]</strong> 📝 Invited as a PC member for the <strong>IEEE workshop BigData CTA3 2023</strong>!</li>
    <li><strong>[08/2023]</strong> 🏅 Awarded the <strong>Engineering Graduate Fellowship</strong> at Vanderbilt University!</li>
    <li><strong>[07/2023]</strong> 📄 Our preprint <a href="https://arxiv.org/abs/2307.04644"><strong>Fairness and Diversity in Recommender Systems: A Survey</strong></a> is now online!</li>
    <li><strong>[05/2023]</strong> 🚀 Excited to join <strong>NDS Lab</strong> under the supervision of Dr. Derr!</li>
  </ul>
</details>



