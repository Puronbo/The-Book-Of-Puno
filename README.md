# The-Book-Of-Puno
**Derivatives as Folds, Integrals as Unfolds, and Creases as Primary Objects**

**Author**: Michael Grafiel Sayson Puno  
**Version**: 1.0 (July 2026)  
**License**: Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## Overview
This repository contains the complete work *The Book of Puno* — a geometric reframing of calculus operations. Differentiation is viewed as *folding* (compression to local slope information), and integration as *unfolding* (expansion to global structure). The 90-degree crease (e.g., the graph of |x|) is the central visual and mathematical anchor.

The project includes:
- The full paper
- Code for visualizations and experiments
- Supporting images and data from toy experiments

## Core Intuition
Imagine folding the graph of |x| at the 90-degree crease. This reveals the set of possible slopes (subdifferential). Unfolding local slopes reconstructs the global function. This perspective unifies classical calculus with modern applications in neural networks (ReLU layers as folding operations).

## Contents
- Main paper (Markdown)
- Ready-to-read PDF
- Generates the key 90-degree crease visualization
- and experiment scripts — Reproducible code from the work
- Images — Plots and figures used in the paper

## How to Use
1. Open `The Book of Puno.pdf` to read the paper.
2. Run `python fold_visual.py` to see the core 90-degree fold intuition (requires numpy + matplotlib).
3. Explore experiments in the provided scripts.

## License
**Creative Commons Attribution 4.0 International (CC BY 4.0)**  
You are free to share and adapt this work for any purpose, including commercial use, **as long as you give appropriate credit** to Michael Grafiel Sayson Puno.  
Full license: https://creativecommons.org/licenses/by/4.0/

Copyright © 2026 Michael Grafiel Sayson Puno

## Citation
```bibtex
@misc{puno2026folding,
  author       = {Puno, Michael Grafiel Sayson},
  title        = {Folding Calculus: Derivatives as Folds, Integrals as Unfolds, and Creases as Primary Objects},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21221044},
  url          = {https://github.com/Puronbo/folding-calculus}
}
