---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download: [Short CV (technical)](/files/CV_HTahmasbi_Short_Technical.pdf) |
[Full CV (academic)](/files/CV_HTahmasbi2026_Full_Academic.pdf)

Education
======
* **Ph.D. in Hard Condensed-Matter Physics**, Institute for Advanced Studies in Basic Sciences (IASBS), Zanjan, Iran, 2014–2019
  * Thesis: *Interatomic Potentials based on Artificial Neural Network: Structural and Thermal Properties of Matters*
  * Visiting Ph.D. Researcher at Leiden University, Netherlands (2017–2018)
* **M.Sc. in Solid-State Physics**, Iran University of Science and Technology (IUST), Tehran, Iran, 2005–2008
* **B.Sc. in Applied Physics**, Arak University, Arak, Iran, 2001–2005

Work experience
======
* **Postdoctoral Researcher**, CASUS–HZDR, Görlitz, Germany, 2021–present
  * High-throughput calculations with MongoDB/AiiDA for training ML interatomic potentials
  * MLIP development for Aluminium and iron hydride
  * Benchmarking universal ML interatomic potentials
* **Postdoctoral Researcher**, Leiden University, Netherlands, 2019–2021
  * IR spectroscopic characterization of H₂ and CO₂ on cationic Cu clusters
  * Systematic DFT studies aligned with experimental IR spectra
  * Neural network potential simulations for large-scale atomic modeling

Skills
======
* **Programming:** Python (NumPy, SciPy, Pandas, PyTorch), FORTRAN, Bash
* **HPC & Workflows:** Slurm, GPU computing, AiiDA, MongoDB
* **DFT & MD:** FHI-aims, VASP, LAMMPS, PHONOPY
* **ML:** Neural Network Potentials, Machine Learning Interatomic Potentials (MLIPs)
* **Visualization:** VESTA, V-Sim, VMD
* **Tools:** Git, GitHub/GitLab, LaTeX, Jupyter Notebooks

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
