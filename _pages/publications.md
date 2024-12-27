---
permalink: /publications
title: "Publications"
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# Publications 

## [Feynman Diagrams as Computational Graphs](https://arxiv.org/abs/2403.18840)
<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:hqOjcs7Dif8C'></span></strong>

Pengcheng Hou, Tao Wang, Daniel Cerkoney, **Xiansheng Cai**, Zhiyi Li, Youjin Deng, Lei Wang, Kun Chen, **arXiv 2403.18840**(2024)

We propose a computational graph representation of high-order Feynman diagrams in Quantum Field Theory (QFT), applicable to any combination of spatial, temporal, momentum, and frequency domains. Utilizing the Dyson-Schwinger and parquet equations, our approach effectively organizes these diagrams into a fractal structure of tensor operations, significantly reducing computational redundancy. This approach not only streamlines the evaluation of complex diagrams but also facilitates an efficient implementation of the field-theoretic renormalization scheme, crucial for enhancing perturbative QFT calculations. Key to this advancement is the integration of Taylor-mode automatic differentiation, a key technique employed in machine learning packages to compute higher-order derivatives efficiently on computational graphs. To operationalize these concepts, we develop a Feynman diagram compiler that optimizes diagrams for various computational platforms, utilizing machine learning frameworks. Demonstrating this methodology's effectiveness, we apply it to the three-dimensional uniform electron gas problem, achieving unprecedented accuracy in calculating the quasiparticle effective mass at metal density. Our work demonstrates the synergy between QFT and machine learning, establishing a new avenue for applying AI techniques to complex quantum many-body problems. 

## [Precursory Cooper Flow in Ultralow-Temperature Superconductors](http://link.aps.org/doi/10.1103/PhysRevResearch.6.013099)
<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:_FxGoFyzp5QC'></span></strong>

Pengcheng Hou, **Xiansheng Cai**, Tao Wang, Youjin Deng, Nikolay Prokof'ev\*, Boris Svistunov\*, and Kun Chen\*, **Phys. Rev. Research 6, 013099**(2024)

Superconductivity at low temperature --- observed in lithium and bismuth, as well as in various low-density superconductors --- calls for developing reliable theoretical and experimental tools for predicting ultralow critical temperatures, $T_c$, of Cooper instability in a system demonstrating nothing but normal Fermi liquid behavior in a broad range of temperatures below the Fermi energy, $T_F$. Equally important are controlled predictions of stability in a given Cooper channel. We identify such a protocol within the paradigm of precursory Cooper flow --- a universal ansatz describing logarithmically slow temperature evolution of the linear response of the normal state to the pair-creating perturbation. Applying this framework to the two-dimensional uniform electron gas, we reveal a series of exotic superconducting states, pushing controlled theoretical predictions of $T_c$ to the unprecedentedly low scale of $10^{−100}T_F$. 

## [Origin of Coulomb Pseudopotential](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.101.035132)
<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:zYLM7Y9cAGgC'></span></strong>

Tao Wang, **Xiansheng Cai**, Kun Chen\*, Nikolay Prokof'ev\*, and Boris Svistunov\*, **Phys. Rev. B 101, 035132** (2023)

We address the outstanding problem of electron pairing in the presence of strong Coulomb repulsion at small to moderate values of the Coulomb parameter, $r_s\leq 2$, and demonstrate that the pseudopotential framework is fundamentally biased and uncontrolled. Instead, one has to break the net result into two distinctively different effects: the Fermi liquid renormalization factor and the change in the effective low-energy coupling. The latter quantity is shown to behave nonmonotonically with an extremum at $r_s\approx 0.75$. Within the random-phase approximation, Coulomb interaction starts to enhance the effective pairing coupling at $r_s>2$, and the suppression of the critical temperature is entirely due to the renormalized Fermi liquid properties. Leading vertex corrections change this picture only quantitatively. Our results call for radical reconsideration of the widely accepted repulsive pseudopotential approach and show the need for precise microscopic treatment of Coulomb interactions in the problem of superconducting instability.

## [Superconductivity in the Uniform Electron Gas: Irrelevance of Kohn-Luttinger Mechanism](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.106.L220502)
<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:YsMSGLbcyi4C'></span></strong>

**Xiansheng Cai**, Tao Wang, Nikolay Prokof'ev\*,  Boris Svistunov\*, and Kun Chen\*, **Phys. Rev. B 106, L220502**(2022)

We study the Cooper instability in jellium model in the controlled regime of small to intermediate values of the Coulomb parameter $r_s\leq 2$. We confirm that superconductivity naturally emerges from purely repulsive interactions described by the Kukkonen-Overhauser vertex function. By employing the implicit renormalization approach and the discrete Lehmann representation we reveal that even in the small-$r_s$ limit, the dominant mechanism behind Cooper instability is based on dynamic screening of the Coulomb interaction---accurately captured by the random phase approximation, whereas the Kohn-Luttinger contribution is negligibly small and, thus, not relevant.

## [Quantum-to-classical correspondence in two-dimensional Heisenberg models](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.101.035132)
<strong><span class='show_paper_citations' data='BTVksHYAAAAJ:zYLM7Y9cAGgC'></span></strong>

Tao Wang, **Xiansheng Cai**, Kun Chen, Nikolay Prokof'ev, Boris Svistunov. **Phys. Rev. B 101, 035132**(2020)

The quantum-to-classical correspondence (QCC) in spin models is a puzzling phenomenon where the static susceptibility of a quantum system agrees with its classical-system counterpart, at a different corresponding temperature, within the systematic error at a subpercent level. We employ the bold diagrammatic Monte Carlo method to explore the universality of QCC by considering three different two-dimensional spin-1/2 Heisenberg models. In particular, we reveal the existence of QCC in models with two parameters.