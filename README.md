# 🚀 Compression to Expansion

## 📄 From Compression to Expansion: A Layerwise Analysis of In-Context Learning

This repository accompanies our paper:

> **From Compression to Expansion: A Layerwise Analysis of In-Context Learning**  
> [📄 arXiv 2505.17322](https://arxiv.org/abs/2505.17322)

We investigate how transformer models internally organize information during In-Context Learning (ICL), revealing a two-phase dynamic: **compression** of input demonstrations into compact task representations, followed by **expansion** for prediction generation.

---

## 🔍 Key Contributions

- 📉 **Task Distinguishability via Normalized Variance (TDNV):**  
  A novel metric that quantifies how well tasks are separated in hidden space during ICL.

- 🧪 **Robustness to Noise:**  
  ICL performance remains stable as long as task compression is preserved (TDNV < 1); performance collapses when within-task variance exceeds between-task distance (TDNV > 1).

- 🧠 **Layerwise Analysis:**  
  Shows that early layers compress task information, while later layers expand it into task-specific outputs.

---

## 📊 Visual Summary

<p align="center">
  <img src="static/figures/compression_to_expansion.png" alt="Compression to Expansion Diagram" width="600">
</p>

---

## 📦 Coming Soon

We are actively preparing a clean and modular codebase. Planned modules include:

- ✅ Representation extraction tools
- ✅ Scripts for TDNV/CDNV computation
- ✅ Visualization of compression/expansion dynamics
- ✅ Layerwise probing and ablation tools

---

## 🧠 Citation

If you find this work useful, please cite:

```bibtex
@article{compression_expansion_icl2025,
  title={From Compression to Expansion: A Layerwise Analysis of In-Context Learning},
  author={Your Name and Coauthors},
  journal={arXiv preprint arXiv:2505.17322},
  year={2025}
}
