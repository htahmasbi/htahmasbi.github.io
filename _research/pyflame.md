---
title: "PyFLAME"
excerpt: "An automated workflow for developing neural network interatomic potentials with FLAME, minimizing human intervention in data generation and training."
collection: research
---

PyFLAME automates the development of neural network interatomic potentials using the methods implemented in the FLAME library. Starting from ab initio calculations of bulk structures, the workflow iterates between training the potential and crystal-structure prediction to grow a diverse, representative training dataset — all with minimal human intervention.

This automation supports the kind of reproducible, high-throughput MLIP pipelines I build and evaluate: datasets are generated deterministically, potentials are trained to a defined protocol, and performance is checked against reference DFT results before use.

- **GitHub:** [github.com/flame-code/PyFLAME](https://github.com/flame-code/PyFLAME)
- **Publication:** [Comput. Mater. Sci. 197, 110567 (2021)](https://doi.org/10.1016/j.commatsci.2021.110567)
- **arXiv:** [arXiv:2102.04085](https://arxiv.org/abs/2102.04085)