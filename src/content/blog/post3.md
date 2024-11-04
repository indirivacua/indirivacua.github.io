---
title: "CB-RISE: Improving the RISE Interpretability Method Through Convergence Detection and Blurred Perturbations"
description: >
  This paper enhances the RISE algorithm for image interpretation by introducing C-RISE, which reduces computation time, and CB-RISE, which uses blurred masks instead of black patches. These improvements lead to better heatmap quality and a speedup of about three times.
pubDate: "Oct 7 2024" #11
heroImage: "/assets/cbrise.png"
badge: "Conference paper"
tags: ["Black Box", "Blurred Masks", "Computer Vision", "Convergence Detection", "Deep Learning", "Interpretability", "RISE"]
authors: ["Oscar Stanchi", "Franco Ronchetti", "Pedro Dal Bianco", "Gastón Rios", "Santiago Ponte Ahon", "Waldo Hasperué", "Facundo Quiroga"]
---

## Abstract

This paper presents significant advancements in the RISE (Randomized Input Sampling for Explanation) algorithm, a popular black-box interpretability method for image data. RISE’s main weakness lies on the large number of model evaluations required to produce the importance heatmap. Furthermore, RISE’s strategy of occluding image regions with black patches is not advisable, as it may lead to unexpected predictions. Therefore, we introduce two new versions of the algorithm, C-RISE and CB-RISE, each incorporating novel features to address the two major challenges of the original implementation. C-RISE introduces a convergence detection based on the Welford algorithm which reduces the computational burden of the algorithm by ceasing computations once the importance map stabilizes. CB-RISE, additionally, introduces the use of blurred masks as perturbations, equivalent to applying Gaussian noise, as opposed to black patches. This allows for a more nuanced representation of the model’s decision-making process. Our experimental results demonstrate the effectiveness of these improvements, successfully enhancing the effectiveness of the generated heatmaps while improving their quality, qualitatively, and showing a speedup of approximately 3.

<div class="mt-8">
    <a class="btn" href="https://link.springer.com/chapter/10.1007/978-3-031-70807-7_4" target="_blank"> Full paper</a>
</div>

## Citation

```bibtex
@inproceedings{stanchi2024cb,
  title={CB-RISE: Improving the RISE Interpretability Method Through Convergence Detection and Blurred Perturbations},
  author={Stanchi, Oscar and Ronchetti, Franco and Bianco, Pedro Dal and Rios, Gast{\'o}n and Ahon, Santiago Ponte and Hasperu{\'e}, Waldo and Quiroga, Facundo},
  booktitle={Conference on Cloud Computing, Big Data \& Emerging Topics},
  pages={45--58},
  year={2024},
  organization={Springer}
}
