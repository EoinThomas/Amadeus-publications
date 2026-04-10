---
layout: default
title: "Variational Inference for Quantum HyperNetworks"
year: 2025
---

# Variational Inference for Quantum HyperNetworks

[← Back to Publications](/Amadeus-publications/)

## Publication Details

- **Authors:** Nepote, L.; Lhéritier, A.; Bondoux, N.; Kountouris, M.; Filippone, M.
- **Venue:** IJCNN Workshop (QCNN) 2025
- **Year:** 2025
- **Link:** [arXiv](https://arxiv.org/abs/2506.05888)

## Abstract

Binary Neural Networks (BiNNs), which employ single-bit precision weights, have emerged as a promising solution to reduce memory usage and power consumption while maintaining competitive performance in large-scale systems. However, training BiNNs remains a significant challenge due to the limitations of conventional training algorithms. Quantum HyperNetworks offer a novel paradigm for enhancing the optimization of BiNN by leveraging quantum computing. Specifically, a Variational Quantum Algorithm is employed to generate binary weights through quantum circuit measurements, while key quantum phenomena such as superposition and entanglement facilitate the exploration of a broader solution space. In this work, we establish a connection between this approach and Bayesian inference by deriving the Evidence Lower Bound (ELBO), when direct access to the output distribution is available (i.e., in simulations), and introducing a surrogate ELBO based on the Maximum Mean Discrepancy (MMD) metric for scenarios involving implicit distributions, as commonly encountered in practice. Our experimental results demonstrate that the proposed methods outperform standard Maximum Likelihood Estimation (MLE), improving trainability and generalization.

## Key Contributions

- Variational inference framework for quantum hypernetworks
- Integration of quantum computing with neural network meta-learning
- Novel approach to uncertainty quantification in quantum ML

## Citation

{% raw %}
```bibtex
@inproceedings{Nepote2025QCNN,
  author    = {Luca Nepote and Alix Lh{\'e}ritier and Nicolas Bondoux and Marios Kountouris and Maurizio Filippone},
  title     = {Variational Inference for Quantum HyperNetworks},
  booktitle = {Proceedings of the Quantum Communication, Computation and Networking Workshop (QCNN) at IJCNN 2025},
  year      = {2025}
}
```
{% endraw %}

---

[← Back to Publications](/Amadeus-publications/)
