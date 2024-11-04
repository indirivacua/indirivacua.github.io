---
title: "VISTA: Vision Improvement via Split and Reconstruct Deep Neural Network for Fundus Image Quality Assessment"
description: >
  This paper introduces a deep learning model for assessing fundus image quality, essential for diagnosing eye conditions like cataracts and diabetic retinopathy. The model preserves high resolution and includes an autoencoder for reconstruction and classification. Results on the EyeQ dataset show 90.66% accuracy, 88.43% precision, 89.05% recall, and an F1-score of 88.68%.
pubDate: "Oct 9 2024"
heroImage: "/assets/vista.png"
badge: "Journal paper"
tags: ["Autoencoder Network", "Explainability", "Fundus Image", "Gradability", "Interpretability", "Quality Assessment", "Retinal Image"]
authors: ["Saif Khalid", "Saddam Abdulwahab", "Oscar Agustín Stanchi", "Facundo Manuel Quiroga", "Franco Ronchetti", "Domenec Puig", "Hatem A. Rashwan"]
---

## Abstract

Widespread eye conditions such as cataracts, diabetic retinopathy, and glaucoma impact people worldwide. Ophthalmology uses fundus photography for diagnosing these retinal disorders, but fundus images are prone to image quality challenges. Accurate diagnosis hinges on high-quality fundus images. Therefore, there is a need for image quality assessment methods to evaluate fundus images before diagnosis. Consequently, this paper introduces a deep learning model tailored for fundus images that supports large images. Our division method centres on preserving the original image’s high-resolution features while maintaining low computing and high accuracy. The proposed approach encompasses two fundamental components: an autoencoder model for input image reconstruction and image classification to classify the image quality based on the latent features extracted by the autoencoder, all performed at the original image size, without alteration, before reassembly for decoding networks. Through post hoc interpretability methods, we verified that our model focuses on key elements of fundus image quality. Additionally, an intrinsic interpretability module has been designed into the network that allows decomposing class scores into underlying concepts quality such as brightness or presence of anatomical structures. Experimental results in our model with EyeQ, a fundus image dataset with three categories (Good, Usable, and Rejected) demonstrate that our approach produces competitive outcomes compared to other deep learning-based methods with an overall accuracy of 0.9066, a precision of 0.8843, a recall of 0.8905, and an impressive F1-score of 0.8868. The code is publicly available at https://github.com/saifalkhaldiurv/VISTA_-Image-Quality-Assessment.

<div class="mt-8">
    <a class="btn" href="https://link.springer.com/article/10.1007/s00521-024-10174-6" target="_blank"> Full paper</a>
</div>

## Citation

```bibtex
@article{khalid2024vista,
  title={VISTA: vision improvement via split and reconstruct deep neural network for fundus image quality assessment},
  author={Khalid, Saif and Abdulwahab, Saddam and Stanchi, Oscar Agust{\'\i}n and Quiroga, Facundo Manuel and Ronchetti, Franco and Puig, Domenec and Rashwan, Hatem A},
  journal={Neural Computing and Applications},
  pages={1--20},
  year={2024},
  publisher={Springer}
}
