---
title: "Wavelength Calibration of Historical Spectrographic Plates with Dynamic Time Warping"
description: >
  The Facultad de Ciencias Astronómicas y Geofísicas at the UNLP holds 15,000 spectroscopic records on glass plates. Processing these records is currently manual and complex, especially for wavelength calibration. This work presents an automated pipeline using Dynamic Time Warping (DTW) to match lamp spectra to simulated data, achieving a 93% average IoU on 32 manually calibrated plates.
pubDate: "Oct 7 2024" #11
heroImage: "/assets/dtw_fcaglp.png"
badge: "Conference paper"
tags: ["Dynamic Time Warping", "Spectrographic records", "Spectrographic plates", "Optimization", "Wavelength calibration"]
authors: ["Santiago Andres Ponte Ahón", "Juan Martín Seery", "Facundo Quiroga", "Franco Ronchetti", "Oscar Stanchi", "Pedro Dal Bianco", "Waldo Hasperué", "Yael Aidelman", "Roberto Gamen"]
---

## Abstract

The Facultad de Ciencias Astronómicas y Geofísicas of the Universidad Nacional de La Plata counts with 15,000 spectroscopic records on glass plates with valuable and unique astronomical data.

Currently, processing these plates requires a complex manual process that involves several stages, requiring several hours to process a single plate. In particular, the wavelength calibration requires the determination of the wavelength range in which the data were observed. This is achieved by matching the spectrum of the comparison lamp on the plate to the reference spectrum. Since many times neither the metadata of the lamps nor the physical lamps are available, automating the tasks requires a semi-blind approach that uses simulated data as a reference. However, the simulated data differs significantly from the physical lamps, given that many peaks determined by theoretical calculations are rarely observed in practice, and conversely the physical lamps and spectrograph carry imperfections that cause unexpected peaks.

In this work, we propose an wavelength calibration pipeline that enables automated matching of the wavelength of the comparison lamps via Dynamic Time Warping (DTW) between the samples and simulated data. Our best model achieves a 93% average Intersection-over-Union (IoU) over a set of 32 manually calibrated plates.

<div class="mt-8">
    <a class="btn" href="https://link.springer.com/chapter/10.1007/978-3-031-70807-7_5" target="_blank"> Full paper</a>
</div>

## Citation

```bibtex
@inproceedings{ponte2024wavelength,
  title={Wavelength Calibration of Historical Spectrographic Plates with Dynamic Time Warping},
  author={Ponte Ah{\'o}n, Santiago Andres and Seery, Juan Mart{\'\i}n and Quiroga, Facundo and Ronchetti, Franco and Stanchi, Oscar and Dal Bianco, Pedro and Hasperu{\'e}, Waldo and Aidelman, Yael and Gamen, Roberto},
  booktitle={Conference on Cloud Computing, Big Data \& Emerging Topics},
  pages={59--73},
  year={2024},
  organization={Springer}
}
