# Importance of Disjoint Sampling

## This demo is associated with [Improving Generalization for Hyperspectral Image Classification: The Impact of Disjoint Sampling on Deep Models](https://www.sciencedirect.com/org/science/article/pii/S1546221824007070) [CMC](https://doi.org/10.32604/cmc.2024.056318).

![model1](https://github.com/user-attachments/assets/406ba370-9e6d-41d3-b047-f650087a568f)

@article{AHMAD2024503,
title = {Improving Generalization for Hyperspectral Image Classification: The Impact of Disjoint Sampling on Deep Models},
journal = {Computers, Materials and Continua},
volume = {81},
number = {1},
pages = {503-532},
year = {2024},
issn = {1546-2218},
doi = {https://doi.org/10.32604/cmc.2024.056318},
url = {https://www.sciencedirect.com/science/article/pii/S1546221824007070},
author = {Muhammad Ahmad and Manuel Mazzara and Salvatore Distefano and Adil Mehmood Khan and Hamad Ahmed Altuwaijri}}

# Models implemented in this work:
## 2D CNN
## 3D CNN
## Hybrid CNN
## 2D Inception Net
## 3D Inception Net
## Hybrid Inception Net
## Attention Graph CNN
## Spatial-Spectral Transformer

# Requirements

This tool is compatible with Python 2.7 and Python 3.5+ and executed over Colab.

# Hyperspectral datasets

Several public hyperspectral datasets are available on the [EHU]([http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)). Users can download those beforehand. 

An example dataset folder has the following structure:
```
Datasets
├── University of Houston
│   ├── UH.mat
│   └── UG_gt.mat
├── IndianPines
│   ├── Indian_pines_corrected.mat
│   ├── Indian_pines_gt.mat
├── Pavia University
│   ├── PU.mat
│   └── PU_gt.mat
├── Botswana
│   ├── BS.mat
│   └── BS_gt.mat
├── Salinas
│   ├── SA.mat
│   └── SA_gt.mat
```
