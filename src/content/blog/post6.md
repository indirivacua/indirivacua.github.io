---
title: "SignAttention: On the Interpretability of Transformer Models for Sign Language Translation"
description: >
  This paper studies a Transformer-based model for translating Greek Sign Language to glosses and text. It finds that the model focuses on clusters of frames, with alignment weakening as glosses increase, and shifts from video frames to predicted tokens during translation. This work enhances understanding of SLT models and promotes more transparent translation systems.
pubDate: "Oct 18 2024"
heroImage: "/assets/signattention.png"
badge: "Conference paper"
tags: ["Sign Language Translation", "Transformers", "Attention Mechanism", "Greek Sign Language", "Interpretability"]
authors: ["Oscar Agustín Stanchi", "Pedro Alejandro Dal Bianco", "Facundo Manuel Quiroga", "Franco Ronchetti", "Enzo Ferrante"]
---

## Abstract

This paper presents the first comprehensive interpretability analysis of a Transformer-based Sign Language Translation (SLT) model, focusing on the translation from video-based Greek Sign Language to glosses and text. Leveraging the Greek Sign Language Dataset, we examine the attention mechanisms within the model to understand how it processes and aligns visual input with sequential glosses. Our analysis reveals that the model pays attention to clusters of frames rather than individual ones, with a diagonal alignment pattern emerging between poses and glosses, which becomes less distinct as the number of glosses increases. We also explore the relative contributions of cross-attention and self-attention at each decoding step, finding that the model initially relies on video frames but shifts its focus to previously predicted tokens as the translation progresses. This work contributes to a deeper understanding of SLT models, paving the way for the development of more transparent and reliable translation systems essential for real-world applications.

<div class="mt-8">
    <a class="btn" href="https://arxiv.org/abs/2410.14506" target="_blank"> Full paper</a>
</div>

## Citation

```bibtex
@inproceedings{stanchi2024signattention,
  title={SignAttention: On the Interpretability of Transformer Models for Sign Language Translation},
  author={Stanchi, Oscar Agust{\'\i}n and Bianco, Pedro Alejandro Dal and Quiroga, Facundo Manuel and Ronchetti, Franco and Ferrante, Enzo},
  booktitle={Interpretable AI: Past, Present and Future @ NeurIPS 2024},
  year={2024}
}
