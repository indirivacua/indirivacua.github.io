---
title: "The Implementation of the RISE Algorithm for the Captum Framework"
description: >
  This paper introduces an efficient implementation of the RISE method in PyTorch using the Captum library. RISE generates explanations for deep learning model predictions by randomly masking input parts. Experiments highlight the significance of the number and size of masks for achieving accurate and versatile interpretations.
pubDate: "Aug 11 2023"
heroImage: "/assets/rise.png"
badge: "Conference paper"
tags: ["Black Box", "Computer Vision", "Deep Learning", "Interpretability", "RISE"]
authors: ["Oscar Stanchi", "Franco Ronchetti", "Facundo Quiroga"]
---

## Abstract

This paper introduces an implementation of the RISE method, using the Captum library in PyTorch. RISE is an algorithm that generates explanations for the predictions of a deep learning model by randomly masking parts of the input image and observing the changes in the model’s output. Our focus is on the implementation and its performance, rather than on the RISE method itself. Through a series of experiments, we have obtained results that demonstrate the importance of the number of masks used in the RISE method. We found that the number of masks can have a significant impact on the interpretability of the outcome. Additionally, we conducted tests to determine the effect of mask size on the interpretability of the results. Our findings indicate that the size of the masks, whether larger or smaller, is also a decisive factor in achieving a good interpretable outcome. Furthermore, we demonstrate how tuning RISE parameters can yield in different results, making RISE effective for several tasks and neural network architectures. Overall, our implementation of RISE over Captum provides a powerful tool for interpreting deep learning models in PyTorch.

<div class="mt-8">
    <a class="btn" href="https://link.springer.com/chapter/10.1007/978-3-031-40942-4_7" target="_blank"> Full paper</a>
</div>

## Citation

```bibtex
@inproceedings{stanchi2023implementation,
  title={The Implementation of the RISE Algorithm for the Captum Framework},
  author={Stanchi, Oscar and Ronchetti, Franco and Quiroga, Facundo},
  booktitle={Conference on Cloud Computing, Big Data \& Emerging Topics},
  pages={91--104},
  year={2023},
  organization={Springer}
}
