# Awesome Topology-Driven (Deep) Image Analysis
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources for topology-driven (deep) image analysis, inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision) and [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Contributing
Please feel free to [pull requests](https://github.com/HuXiaoling/awesome-topology-driven-image-analysis/pulls) or send me email (xihu3@mgh.harvard.edu) to contribute.

## Table of Contents
- [Books](#books)
- [Tools](#tools)
- [Software](#software)
- [Papers](#papers)
  - [Segmentation](#segmentation)
  - [Classification](#classification)
  - [Detection](#detection)
  - [Registration](#registration)
  - [Counting](#counting)
  - [Uncertainty Estimation](#uncertainty-estimation)
  - [Generative Models](#generative-models)
  - [Other Topics](#other-topics)
- [Tutorials](#tutorials)
- [Workshops](#workshops)
## Books
* [Computational Topology. An Introduction](https://www.maths.ed.ac.uk/~v1ranick/papers/edelcomp.pdf) by [Herbert Edelsbrunner](https://pub.ista.ac.at/~edels/)
* [Computational Topology for Data Analysis](http://yusu.belkin-wang.org/CTDAbook-DeyWang.pdf) by [Tamal Krishna Dey](https://www.cs.purdue.edu/homes/tamaldey/), and [Yusu Wang](http://yusu.belkin-wang.org/)

## Tools
* [Persistent homology](https://en.wikipedia.org/wiki/Persistent_homology)
* [Morse theory](https://en.wikipedia.org/wiki/Morse_theory)

## Software
* [GUDHI library](https://gudhi.inria.fr/)
* [Ripser](https://ripser.scikit-tda.org/en/latest/)
* [Scikit-TDA](https://github.com/scikit-tda)

## Papers
### Segmentation
* Xiaoling Hu, Fuxin Li, Dimitris Samaras, and Chao Chen. "Topology-preserving deep image segmentation." NeurIPS'2019. [[Paper](https://proceedings.neurips.cc/paper/2019/file/2d95666e2649fcfc6e3af75e09f5adb9-Paper.pdf)]
* Banerjee, Samik, Lucas Magee, Dingkang Wang, Xu Li, Bing-Xing Huo, Jaikishan Jayakumar, Katherine Matho et al. "Semantic segmentation of microscopic neuroanatomical data by combining topological priors with encoder–decoder deep networks."  NMI'2020. [[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8486300/)]
* James R. Clough, Nicholas Byrne, Ilkay Oksuz, Veronika A. Zimmer, Julia A. Schnabel, Andrew P. King. "A topological loss function for deep-learning based image segmentation using persistent homology." TPAMI'2020. [[Paper](https://arxiv.org/pdf/1910.01877)]
* Xiaoling Hu, Yusu Wang, Li Fuxin, Dimitris Samaras, and Chao Chen. "Topology-aware segmentation using discrete morse theory." ICLR'2021. [[Paper](https://openreview.net/pdf?id=LGgdb4TS4Z)].
* Xiaoling Hu. "Structure-aware image segmentation with homotopy warping." NeurIPS'2022. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/98143953a7fd1319175b491888fc8df5-Paper-Conference.pdf)]
* Saumya Gupta, Xiaoling Hu, James Kaan, Michael Jin, Mutshipay Mpoy, Katherine Chung, Gagandeep Singh et al. "Learning topological interactions for multi-class medical image segmentation." ECCV'2022. [[Paper](https://arxiv.org/pdf/2207.09654)]
* Meilong Xu, Xiaoling Hu, Saumya Gupta, Shahira Abousamra, and Chao Chen. "TopoSemiSeg: Enforcing Topological Consistency for Semi-Supervised Segmentation of Histopathology Images." ECCV'2024. [[Paper](https://arxiv.org/pdf/2311.16447)]
* Qian Wu, Yufei Chen, Wei Liu, Xiaodong Yue, and Xiahai Zhuang. "Deep Closing: Enhancing Topological Connectivity in Medical Tubular Segmentation." TMI'2024 [[Paper](https://ieeexplore.ieee.org/abstract/document/10540037?casa_token=FOES6ZemAOkAAAAA:r3lRafFgWh08fThQhiOwd6orIuuKG_G4GtzhCRulhVv9bBKTjh9mTJ9UjQs-QFw1ymPtsU9M67g)]
### Classification
* Fan Wang, Saarthak Kapse, Steven Liu, Prateek Prasanna, and Chao Chen. "TopoTxR: a topological biomarker for predicting treatment response in breast cancer." MICCAI'2021. [[Paper](https://arxiv.org/pdf/2105.06049)]
* Yaopeng Peng, Hongxiao Wang, Milan Sonka, and Danny Z. Chen. "PHG-Net: Persistent Homology Guided Medical Image Classification." WACV'2024. [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Peng_PHG-Net_Persistent_Homology_Guided_Medical_Image_Classification_WACV_2024_paper.pdf)]

### Detection
* Shahira Abousamra, David Belinsky, John Van Arnam, Felicia Allard, Eric Yee, Rajarsi Gupta, Tahsin Kurc, Dimitris Samaras, Joel Saltz, and Chao Chen. "Multi-class cell detection using spatial context representation." ICCV'2021. [[Paper](https://arxiv.org/pdf/2110.04886)]

### Registration

### Counting
* Shahira Abousamra, Minh Hoai, Dimitris Samaras, and Chao Chen. "Localization in the crowd with topological constraints." AAAI'2021. [[Paper](https://arxiv.org/pdf/2012.12482)]

### Uncertainty Estimation
* Xiaoling Hu, Dimitris Samaras, and Chao Chen. "Learning probabilistic topological representations using discrete morse theory." ICLR'2023. [[Paper](https://openreview.net/pdf?id=cXMHQD-xQas)]
* Saumya Gupta, Yikai Zhang, Xiaoling Hu, Prateek Prasanna, and Chao Chen. "Topology-aware uncertainty for image segmentation." NeurIPS'2023. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/19ded4cfc36a7feb7fce975393d378fd-Paper-Conference.pdf)]
  
### Generative Models
* Fan Wang, Huidong Liu, Dimitris Samaras, and Chao Chen. "Topogan: A topology-aware generative adversarial network." ECCV'2020. [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480120.pdf)]
* Shahira Abousamra, Rajarsi Gupta, Tahsin Kurc, Dimitris Samaras, Joel Saltz, and Chao Chen. "Topology-guided multi-class cell context generation for digital pathology." CVPR'2023. [[Paper](https://arxiv.org/pdf/2304.02255)]

### Other Topics

## Tutorials
* [Topology-Driven Image Analysis](https://topology-miccai.github.io/)

## Workshops
* [The First Workshop on Topology- and Graph-Informed Imaging Informatics (TGI3)](https://topology-miccai.github.io/First_TGI_2024.html)

Maintainers - [Xiaoling Hu](https://github.com/HuXiaoling)
