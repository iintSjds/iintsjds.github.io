---
permalink: /
title: "About"
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

<span class='anchor' id='about-me'></span>
My research interests encompass theoretical and numerical
quantum many-body physics, with a particular emphasis on correlated electrons
and frustrated magnetism. My recent research primarily centers on first principle study of superconductivity with quantum field theoretical approach and modern
numerical techniques. 
I have published several papers total google scholar <a href='https://scholar.google.com/citations?user=BTVksHYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
I'm also working in collaboration with other developers to develop a Julia project of numerical framework for effective field theory in quantum many-body systems:
<a href="https://github.com/numericalEFT">numericalEFT</a>.

# Publications 
<span class='anchor' id='-publications'></span>

- [Feynman Diagrams as Computational Graphs](https://arxiv.org/abs/2403.18840), Pengcheng Hou, Tao Wang, Daniel Cerkoney, **Xiansheng Cai**, Zhiyi Li, Youjin Deng, Lei Wang, Kun Chen, **arXiv 2403.18840**(2024) <strong><span class='show_paper_citations' data='BTVksHYAAAAJ:hqOjcs7Dif8C'></span></strong>

- [Precursory Cooper flow in ultralow-temperature superconductors](http://link.aps.org/doi/10.1103/PhysRevResearch.6.013099), Pengcheng Hou, **Xiansheng Cai**, Tao Wang, Youjin Deng, Nikolay Prokof'ev\*, Boris Svistunov\*, and Kun Chen\*, **Phys. Rev. Research 6, 013099**(2024) <strong><span class='show_paper_citations' data='BTVksHYAAAAJ:UebtZRa9Y70C'></span></strong>

- [Origin of Coulomb Pseudopotential](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.107.L140507), Tao Wang, **Xiansheng Cai**, Kun Chen\*, Nikolay Prokof'ev\*, and Boris Svistunov\*,  **Phys. Rev. B 107, L140507**(2023) <strong><span class='show_paper_citations' data='BTVksHYAAAAJ:LkGwnXOMwfcC'></span></strong>

- [Superconductivity in the Uniform Electron Gas: Irrelevance of Kohn-Luttinger Mechanism](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.106.L220502), **Xiansheng Cai**, Tao Wang, Nikolay Prokof'ev\*,  Boris Svistunov\*, and Kun Chen\*, **Phys. Rev. B 106, L220502**(2022)<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:YsMSGLbcyi4C'></span></strong>

- [Quantum-to-classical correspondence in two-dimensional Heisenberg models](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.101.035132), Tao Wang, **Xiansheng Cai**, Kun Chen, Nikolay Prokof'ev, Boris Svistunov. **Phys. Rev. B 101, 035132**(2020)<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:zYLM7Y9cAGgC'></span></strong>

# Talks
<span class='anchor' id='-invited-talks'></span>

- *2023.3*, **APS March Meeting**, Linear Response Approach to Superconducting Phase Transition Temperature.

- *2022.10*, **CCQ Seminar** (Flatiron, New York City), Linear response approach to the superconducting transition temperature.

- *2022.4*, **Simons Collab. on the Many Electron Problem Lectures** (Flatiron, New York City), Superconductivity in the Uniform Electron Gas with and without electron-phonon interactions.

- *2021.3*, **APS March Meeting**, Cooper instability in the Jellium model: Implicit renormalization approach.


# Educations
<span class='anchor' id='-educations'></span>

- *Sep 2017 - Feb 2025*, PhD, University of Massachusetts Amherst, Massachusetts, USA

- *Sep 2013 - Jun 2017*, B.S. University of Science and Technology of China, Hefei, China
