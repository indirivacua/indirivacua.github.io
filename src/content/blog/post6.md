---
title: "Bringing balance to hand shape classification: Mitigating data imbalance through generative models"
description: >
  This paper improves hand-shape classification in sign language by using GAN-generated images for pre-training. This boosts accuracy (up to 5% overall, 100% on rare classes), halves training time, and enables cross-dataset generalization. Pre-training with synthetic data outperforms other augmentation methods.
pubDate: "Oct 7 2023"
heroImage: "/assets/handshape.png"
badge: "Journal paper"
tags: ["Handshape Recognition", "Unbalanced Data", "Limited Data", "Sign Language", "Generative Adversarial Networks"]
authors: ["Gaston Gustavo Rios", "Pedro Dal Bianco", "Franco Ronchetti", "Facundo Quiroga", "Oscar Agustín Stanchi", "Santiago Ponte Ahón", "Waldo Hasperué"]
---

## Abstract

Most sign language handshape datasets are severely limited and unbalanced, posing significant challenges to effective model training. In this paper, we explore the effectiveness of augmenting the training data of a handshape classifier by generating synthetic data. We use an EfficientNet classifier trained on the RWTH German sign language handshape dataset, which is small and heavily unbalanced, applying different strategies to combine generated and real images. We compare two Generative Adversarial Networks (GAN) architectures for data generation: ReACGAN, which uses label information to condition the data generation process through an auxiliary classifier, and SPADE, which utilizes spatially-adaptive normalization to condition the generation on pose information. ReACGAN allows for the generation of realistic images that align with specific handshape labels, while SPADE focuses on generating images with accurate spatial handshape configurations. Our proposed techniques improve the current state-of-the-art accuracy on the RWTH dataset by 5%, addressing the limitations of small and unbalanced datasets. Additionally, our method demonstrates the capability to generalize across different sign language datasets by leveraging pose-based generation trained on the extensive HaGRID dataset. We achieve comparable performance to single-source trained classifiers without the need for retraining the generator.

<div class="mt-8">
    <a class="btn" href="https://arxiv.org/abs/2507.17008" target="_blank"> Full paper</a>
    <span style="margin:10px"></span>
    <a class="btn" href="https://github.com/okason97/Bringing-Balance-to-Hand-Shape-Classification" target="_blank"> Code on GitHub</a>
</div>

## Citation

```bibtex
@article{rios2025bringing,
  title={Bringing balance to hand shape classification: Mitigating data imbalance through generative models},
  author={Rios, Gaston Gustavo and Dal Bianco, Pedro and Ronchetti, Franco and Quiroga, Facundo and Stanchi, Oscar and Ah{\'o}n, Santiago Ponte and Hasperu{\'e}, Waldo},
  journal={Applied Soft Computing},
  pages={113586},
  year={2025},
  publisher={Elsevier}
}
