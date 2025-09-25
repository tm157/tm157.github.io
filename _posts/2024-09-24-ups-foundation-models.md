---
title: "UPS: Efficiently Building Foundation Models for PDE Solving via Cross-Modal Adaptation"
category: academic
featured: true
author: Junhong Shen, Tanya Marwah, Ameet Talwalkar
actual_url: https://arxiv.org/abs/2403.07187
url: https://arxiv.org/abs/2403.07187
abstract:
|
    Unified PDE Solvers adapts pretrained language models to learn efficient neural operators across diverse spatiotemporal PDEs.
bullets:
|
    - [TMLR 2024](https://arxiv.org/abs/2403.07187)
    - {:.highlight} ICML AI4Science Workshop Spotlight
---

<p class="abstract">
We present Unified PDE Solvers (UPS), a data- and compute-efficient approach to developing unified neural operators for diverse families of spatiotemporal PDEs from various domains, dimensions, and resolutions. UPS embeds different PDEs into a shared representation space and processes them using a FNO-transformer architecture. Rather than training the network from scratch, which is data-demanding and computationally expensive, we warm-start the transformer from pretrained LLMs and perform explicit alignment to reduce the modality gap while improving data and compute efficiency. The cross-modal UPS achieves state-of-the-art results on a wide range of 1D and 2D PDE families from PDEBench, outperforming existing unified models using 4 times less data and 26 times less compute. Meanwhile, it is capable of few-shot transfer to unseen PDE families and coefficients.
</p>

[PDF](https://arxiv.org/pdf/2403.07187)
