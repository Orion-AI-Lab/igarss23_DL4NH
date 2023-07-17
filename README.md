# Deep Learning for monitoring and forecasting natural hazards with earth observation data

This is the repository for the Tutorial on [Deep Learning for Natural Hazards (DL4NH)](https://2023.ieeeigarss.org/tutorials.php#tut109) in IGARSS 2023.

Presented by [Nikolaos-Ioannis Bountos](https://ngbountos.github.io/) (1), [Ioannis Prapas](https://iprapas.github.io) (1, 2), [Spyros Kondylatos](https://github.com/skondylatos/) (1, 2), [Maria Sdraka](https://github.com/paren8esis/) (1), and [Ioannis Papoutsis](https://scholar.google.gr/citations?user=46cBUO8AAAAJ) (1) 

(1) [Orion Lab](http://orionlab.space.noa.gr/), Institute for Astronomy, Astrophysics, Space Applications and Remote Sensing, National Observatory of Athens

(2) [Image & Signal Processing Group](https://isp.uv.es/), Universitat de València

## 🕸️ Agenda & Quick Links

| Time          | Title          | Resources                       | Presenter         |
|---------------|----------------|---------------------------------|-------------------|
| 9.00 - 9.30   | Introduction   | [Presentation](https://docs.google.com/presentation/d/1RC0MaaI6ZRM1-LDD_IQILZz78W1JK2aT/edit?usp=drive_link&ouid=103666319609428787109&rtpof=true&sd=true)                | Ioannis Papoutsis |
| 9.30 - 10.15  |                | [Presentation](https://docs.google.com/presentation/d/1zJm792cPx72i-il6PeZDV9XuwclACroSvFSjJiccgGY/edit?usp=drive_link), [Hands-on](https://colab.research.google.com/drive/11uJKHF67ifle2iWtANrYgxu7KiK48Tjb?usp=drive_link)  | Ioannis Prapas    |
| 10.15 - 11.00 | A blessing and a curse - Class imbalance in Natural Hazards| [Presentation](https://docs.google.com/presentation/d/1XTRsU9FhsFWhLhYTRK-bodpgTA1_BNcMVF6bMq0jL4c/edit?usp=sharing)                | Nikolaos Bountos  |
| 11.00 - 11.10 | *Coffee Break* |                                 |                   |
| 11.10 - 11.55 |                | [Presentation](https://docs.google.com/presentation/d/1GepCuzLx3SxiWxO3aszqR79uaUGGmd6FRC_KdJRY5qg/edit?usp=drive_link), [Hands-on](https://colab.research.google.com/drive/1LMihcZHW_YePbR0sUlGeiUvyjspp5Z24?usp=drive_link)  | Spyros Kondylatos |
| 11.55 - 12.00 | Conclusion     | -                | Ioannis Papoutsis |

- [Presentations](https://drive.google.com/drive/folders/1YX_whI7i8lgbvZqita2bKLUGWw3hKEoR?usp=drive_link)
- [Hands-on Notebooks](https://drive.google.com/drive/folders/18DXoU-OpgDcgNrbIZB3LOtnnjkD7kg6y?usp=drive_link)

## Description

The rapid advances of Deep Learning (DL) combined with the diverse and massive amount of freely available earth observation (EO) data open new paths for monitoring and predicting the risk of natural hazards and assessing their impact. Monitoring (e.g. providing early warnings or estimating the extent of the disaster promptly), as well as risk prediction (e.g. forecasting disasters) can prove to be crucial for decision making, allowing for improved emergency response, potentially reducing the casualties and negative effects. This tutorial will provide a complete guide on the subject, starting from foundational ideas and data handling, to state-of-the-art artificial intelligence methods dealing with a diverse set of natural hazards including wildfires, volcanic activity, floods and earthquakes. The ultimate goal is to attract researchers and geoscientists to work on such crucial tasks and equip them with the necessary tools and knowledge needed to tackle them. In particular, the tutorial will cover applications of DL for all the three stages of the emergency management cycle (forecasting and preparedness, early warning, monitoring and impact assessment), covering the curation of spatio-temporal datasets and presenting common problems in the context of DL for Natural Hazards management, such as lack of labels and naturally occurring class imbalance as well as methods to work around them. Finally, as emergency management requires action, the last part of the tutorial will cover methods that enhance the interpretability of the models with focus on explainable AI and Bayesian methods that provide an estimate of uncertainty. The tutorial will cover different types of remote sensing datasets, including multi-spectral, synthetic aperture (SAR) data, interferometric SAR data along with meteorological, landscape and other geospatial data.

## Learning Objectives

This tutorial aims to train the attending researchers on the use of state-of-the-art artificial intelligence methods to develop early warning, forecasting and monitoring systems for natural hazards using multi-modal remote sensing datasets. The tutorial will be split into two parts. The first part will focus on theoretical aspects, common problems, workarounds, tips and tricks. The second part will involve the demonstration of SoTA methods through Python Jupyter notebooks that can be run by the participants. Due to the nature of DL algorithms requiring significant time to train, toy dataset examples and/or pretrained models will be prepared.

The tutorial will cover the following subjects in particular:

* Creation and curation of spatio-temporal datacubes
* Handling data scarcity for natural disaster monitoring
  * Transfer learning / Domain Adaptation approaches to address label scarcity.
  * Noisy labels and methods to select positive and negative samples under uncertainty.
  * Self-supervised learning for earth system variables that drive natural disasters.
*    Tips for successful spatiotemporal forecasting
*    Uncertainty in Earth Observation for disaster management with emphasis on Bayesian machine learning methods
*    Challenges yet to be addressed: A glimpse into the future of the field

## Prerequisites

We assume basic knowledge of ML/DL methods, python and earth observation.

In this tutorial, we will provide working examples in the form of Jupyter notebooks along with the necessary data. The users are required to have a laptop equipped with a modern browser. 

**An account is required for access to [google colab](https://colab.research.google.com)**.

## Access 

For access to the in-person tutorial, [registration](https://2023.ieeeigarss.org/registration.asp) is needed. All material (jupyter notebooks, presentations) will be made freely available through this repository.

Time: Sun, 16 Jul, 09:00 - 12:00 Pacific Time (UTC -7)

Location: Room 101 (Pasadena Convention Center)

## Contact us 

For any communication about this tutorial, [please submit an issue](https://github.com/Orion-AI-Lab/igarss23_DL4NH/issues/new/choose) or [email us](mailto:ipapoutsis@noa.gr).

## Acknowledgements

This work has received funding from the European Union’s Horizon 2020 Research and Innovation
Projects DeepCube and TREEADS, under Grant Agreement Numbers 101004188 and 101036926
respectively.
