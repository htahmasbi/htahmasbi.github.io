---
title: "aiida-gw"
excerpt: "AiiDA plugin for automated CP2K GW workflows targeting 2D materials: single-point, relaxation, and G0W0 band-gap calculations with HPC/SLURM support."
collection: research
sort_order: 1
---

aiida-gw is an [AiiDA](https://aiida.readthedocs.io/) plugin I have been developing for automated GW calculations of two-dimensional materials with CP2K. It provides a Typer-based command-line interface, a config-driven CP2K input builder (basis sets, pseudopotentials, and RI resolution), and three reproducible workchains — single-point, relaxation, and SCF→GW — together with OPTIMADE structure fetching and automated result parsing for G0W0 band gaps.

It powers high-throughput, reproducible workflows of the kind I build and evaluate: calculations are tracked in a database, configured via environment or `config.toml`, and submitted to SLURM-managed HPC clusters with full provenance.

- **GitHub:** [github.com/htahmasbi/aiida-gw](https://github.com/htahmasbi/aiida-gw)
- **Stack:** Python · AiiDA · CP2K · OPTIMADE · SLURM · CI (GitHub Actions)