---
layout: default
title: "Semantic Adapter for Universal Text Embeddings"
year: 2025
---

# Semantic Adapter for Universal Text Embeddings: Diagnosing and Mitigating Negation Blindness to Enhance Universality

[← Back to Publications](/Amadeus-publications/)

## Publication Details

- **Authors:** Cao, H.
- **Venue:** ECAI 2025
- **Year:** 2025
- **Link:** [arXiv](https://arxiv.org/abs/2504.00584)

## Abstract

Negation plays an important role in various natural language processing tasks such as Natural Language Inference and Sentiment Analysis tasks. Numerous prior studies have found that contextual text embedding models such as BERT, ELMO, RoBERTa or XLNet face challenges in accurately understanding negation. Recent advancements in universal text embeddings have demonstrated superior performance over contextual text embeddings in various tasks. However, due to the bias in popular evaluation benchmarks, the negation awareness capacity of these models remains unclear. To bridge the gap in existing literature, an in-depth analysis is initiated in this work to study the negation awareness of cutting-edge universal text embedding models. Our findings reveal a significant lack of negation awareness in these models, often interpreting negated text pairs as semantically similar. To efficiently deal with the conflict that different tasks need different trade-offs between topic and negation information among other semantic information, a data-efficient and computational-efficient embedding re-weighting method is proposed without modifying the parameters of text embedding models. The proposed solution is able to improve text embedding models' negation awareness significantly on both simple negation understanding task and complex negation understanding task. Furthermore, the proposed solution can also significantly improve the negation awareness of Large Language Model based task-specific high dimensional universal text embeddings.

## Key Contributions

- Diagnosis of negation blindness in universal text embeddings
- Novel semantic adapter architecture
- Improved handling of negation and semantic nuances
- Enhanced universality across diverse tasks

## Citation

{% raw %}
```bibtex
@inproceedings{Cao2025ECAI,
  author    = {Hongliu Cao},
  title     = {Semantic Adapter for Universal Text Embeddings: Diagnosing and Mitigating Negation Blindness to Enhance Universality},
  booktitle = {Proceedings of the 25th European Conference on Artificial Intelligence (ECAI 2024/2025)},
  year      = {2025},
  note      = {arXiv preprint arXiv:XXXX.YYYYY}
}
```
{% endraw %}

---

[← Back to Publications](/Amadeus-publications/)
