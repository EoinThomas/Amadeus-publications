---
layout: default
title: "A Cramér Distance Perspective on Quantile Regression Based Distributional Reinforcement Learning"
year: 2022
---

# A Cramér Distance Perspective on Quantile Regression Based Distributional Reinforcement Learning

[← Back to Publications](/Amadeus-publications/)

## Publication Details

- **Authors:** Lhéritier, A.; Bondoux, N.
- **Venue:** AISTATS 2022
- **Year:** 2022
- **Link:** [arXiv](https://arxiv.org/abs/2110.00535)

## Abstract

Distributional reinforcement learning (DRL) extends the value-based approach by approximating the full distribution over future returns instead of the mean only, providing a richer signal that leads to improved performances. Quantile Regression (QR) based methods like QR-DQN project arbitrary distributions into a parametric subset of staircase distributions by minimizing the 1-Wasserstein distance. However, due to biases in the gradients, the quantile regression loss is used instead for training, guaranteeing the same minimizer and enjoying unbiased gradients. Non-crossing constraints on the quantiles have been shown to improve the performance of QR-DQN for uncertainty-based exploration strategies. The contribution of this work is in the setting of fixed quantile levels and is twofold. First, we prove that the Cramér distance yields a projection that coincides with the 1-Wasserstein one and that, under non-crossing constraints, the squared Cramér and the quantile regression losses yield collinear gradients, shedding light on the connection between these important elements of DRL. Second, we propose a low complexity algorithm to compute the Cramér distance.

## Key Contributions

- Novel theoretical perspective on distributional RL using Cramér distance
- Analysis of quantile regression-based approaches
- Theoretical guarantees for convergence
- Connection between distributional RL and optimal transport

## Citation

{% raw %}
```bibtex
@inproceedings{Lheritier2022Cramer,
  author    = {Alix Lh{\'e}ritier and Nicolas Bondoux},
  title     = {A Cram{\'e}r Distance Perspective on Quantile Regression Based Distributional Reinforcement Learning},
  booktitle = {Proceedings of the 25th International Conference on Artificial Intelligence and Statistics (AISTATS 2022)},
  year      = {2022},
  publisher = {PMLR}
}
```
{% endraw %}

---

[← Back to Publications](/Amadeus-publications/)
