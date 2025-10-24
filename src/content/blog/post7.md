---
title: "AI Debaters are More Persuasive when Arguing in Alignment with Their Own Beliefs"
description: >
  This paper explores how LLMs perform in AI debates when their arguments align or conflict with their prior beliefs. By measuring models’ priors and comparing debate protocols, we find that models are more persuasive when defending positions consistent with their beliefs, offering insights into persuasion dynamics and bias in scalable oversight.
pubDate: "Oct 15 2025"
heroImage: "/assets/aidebaters.png"
badge: "Conference paper"
tags: ["AI Debate", "Scalable Oversight", "Persuasiveness", "AI Safety", "Large Language Models", "Alignment"]
authors: ["María Victoria Carro", "Denise Alejandra Mester", "Facundo Nieto", "Oscar Agustín Stanchi", "Guido Ernesto Bergman", "Mario Leiva", "Luca Nicolás Forziati Gangi", "Eitan Sprejer", "Francisca Gauna Selasco", "Juan Gustavo Corvalan", "Maria Vanina Martinez", "Gerardo Simari"]
# award: ""
award_name: "Poster @ NeurIPS 2025"
---

## Abstract

The core premise of AI debate as a scalable oversight technique is that it is harder to lie convincingly than to refute a lie, thereby enabling the judge to identify the correct position. Yet, existing debate experiments have relied on datasets with ground truth, where “lying” is reduced to defending an incorrect proposition. This overlooks a subjective dimension: lying also requires the belief that the claim defended is false. In this work, we apply debate to subjective questions and explicitly measure large language models’ prior beliefs before experiments. Debaters were asked to select the position they preferred to defend, then presented with a judge persona deliberately designed to conflict with their identified priors. This setup allowed us to test whether models would adopt sycophantic strategies, aligning with the judge’s presumed perspective to maximize persuasiveness, or instead remain faithful to their prior beliefs as a persuasion strategy. We further implemented and compared two debate protocols, sequential and simultaneous, to evaluate potential systematic biases. Finally, we assessed whether models were more persuasive, and produced higher-quality arguments, when defending positions consistent with their prior beliefs versus when arguing against them. We report four main findings: (1) models tend to prefer defending stances aligned with the judge persona rather than with their prior beliefs; (2) sequential debate introduces a significant bias favoring the second debater; (3) models are more persuasive when defending positions aligned with their prior beliefs; and (4) paradoxically, arguments misaligned with prior beliefs are rated as higher quality in pairwise comparison. These results can inform human judges to provide higher-quality training signals and contribute to more aligned AI systems, while also revealing an important aspect of human–AI interaction about the dynamics of persuasion in language models when engaging with end users in every-day contexts.

<div class="mt-8">
    <a class="btn" href="https://arxiv.org/abs/2510.13912" target="_blank"> Full paper</a>
    <span style="margin:10px"></span>
    <a class="btn" href="https://github.com/FAIR-IALAB-UBA/Debate-NeurIPS25" target="_blank"> Code on GitHub</a>
</div>

## Citation

```bibtex
@inproceedings{carro2025ai,
  title={AI Debaters are More Persuasive when Arguing in Alignment with Their Own Beliefs},
  author={Carro, Mar{\'\i}a Victoria and Mester, Denise Alejandra and Nieto, Facundo and Stanchi, Oscar Agust{\'\i}n and Bergman, Guido Ernesto and Leiva, Mario Alejandro and Sprejer, Eitan and Gangi, Luca Nicol{\'a}s Forziati and Selasco, Francisca Gauna and Corval{\'a}n, Juan Gustavo and others},
  booktitle={First Workshop on Multi-Turn Interactions in Large Language Models @ NeurIPS 2025},
  year={2025}
}
