---
layout: default
title: "Inclusive normalization of face images to passport format"
year: 2023
---

# Inclusive normalization of face images to passport format

[← Back to Publications](/Amadeus-publications/)

## Publication Details

- **Authors:** Hongliu CAO; Minh Nhat Do; Alexis Ravanel; Eoin Thomas
- **Venue:** arXiv preprint
- **Year:** 2023
- **Link:** [arXiv](https://arxiv.org/abs/2312.14544)

## Abstract

Face recognition has been used more and more in real world applications in recent years. However, when the skin color bias is coupled with intra-personal variations like harsh illumination, the face recognition task is more likely to fail, even during human inspection. Face normalization methods try to deal with such challenges by removing intra-personal variations from an input image while keeping the identity the same. However, most face normalization methods can only remove one or two variations and ignore dataset biases such as skin color bias. The outputs of many face normalization methods are also not realistic to human observers. In this work, a style based face normalization model (StyleFNM) is proposed to remove most intra-personal variations including large changes in pose, bad or harsh illumination, low resolution, blur, facial expressions, and accessories like sunglasses among others. The dataset bias is also dealt with in this paper by controlling a pretrained GAN to generate a balanced dataset of passport-like images. The experimental results show that StyleFNM can generate more realistic outputs and can improve significantly the accuracy and fairness of face recognition systems.

## Key Contributions

- First framework to normalize face images to passport-like standard format, handling multiple variations simultaneously
- Novel approach to address dataset bias by controlling pretrained GANs to generate balanced training data
- Generation of more realistic images that improve both accuracy and fairness of face recognition systems
- Fast inference speed suitable for real-world applications

## Citation

{% raw %}
```bibtex
@article{cao2023inclusive,
  title={Inclusive normalization of face images to passport format},
  author={Cao, Hongliu and Do, Minh Nhat and Ravanel, Alexis and Thomas, Eoin},
  journal={arXiv preprint arXiv:2312.14544},
  year={2023}
}
```
{% endraw %}

---

[← Back to Publications](/Amadeus-publications/)
