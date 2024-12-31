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
* Seung Yeon Shin, Sungwon Lee, Daniel Elton, James L. Gulley, and Ronald M. Summers. "Deep small bowel segmentation with cylindrical topological constraints." MICCAI'2020. [[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9107797/)]
* James R. Clough, Nicholas Byrne, Ilkay Oksuz, Veronika A. Zimmer, Julia A. Schnabel, Andrew P. King. "A topological loss function for deep-learning based image segmentation using persistent homology." TPAMI'2020. [[Paper](https://arxiv.org/pdf/1910.01877)]
* Xiaoling Hu, Yusu Wang, Li Fuxin, Dimitris Samaras, and Chao Chen. "Topology-aware segmentation using discrete morse theory." ICLR'2021. [[Paper](https://openreview.net/pdf?id=LGgdb4TS4Z)].
* Suprosanna Shit, Johannes C. Paetzold, Anjany Sekuboyina, Ivan Ezhov, Alexander Unger, Andrey Zhylka, Josien PW Pluim, Ulrich Bauer, and Bjoern H. Menze. "clDice-a novel topology-preserving loss function for tubular structure segmentation." CVPR'2021. [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Shit_clDice_-_A_Novel_Topology-Preserving_Loss_Function_for_Tubular_Structure_CVPR_2021_paper.pdf)]
* Mingfei Cheng, Kaili Zhao, Xuhong Guo, Yajing Xu, and Jun Guo. "Joint topology-preserving and feature-refinement network for curvilinear structure segmentation." ICCV'2021. [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheng_Joint_Topology-Preserving_and_Feature-Refinement_Network_for_Curvilinear_Structure_Segmentation_ICCV_2021_paper.pdf)].
* Oner, Doruk, Mateusz Koziński, Leonardo Citraro, Nathan C. Dadap, Alexandra G. Konings, and Pascal Fua. "Promoting connectivity of network-like structures by enforcing region separation." TPAMI'2021. [[Paper](https://arxiv.org/pdf/2009.07011)]
* Xiaoling Hu. "Structure-aware image segmentation with homotopy warping." NeurIPS'2022. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/98143953a7fd1319175b491888fc8df5-Paper-Conference.pdf)]
* Saumya Gupta, Xiaoling Hu, James Kaan, Michael Jin, Mutshipay Mpoy, Katherine Chung, Gagandeep Singh et al. "Learning topological interactions for multi-class medical image segmentation." ECCV'2022. [[Paper](https://arxiv.org/pdf/2207.09654)]
* Nico Stucki, Johannes C. Paetzold, Suprosanna Shit, Bjoern Menze, and Ulrich Bauer. "Topologically faithful image segmentation via induced matching of persistence barcodes." ICML'2023. [[Paper](https://proceedings.mlr.press/v202/stucki23a/stucki23a.pdf)]
* Yaolei Qi, Yuting He, Xiaoming Qi, Yuan Zhang, and Guanyu Yang. "Dynamic snake convolution based on topological geometric constraints for tubular structure segmentation." ICCV'2023. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Qi_Dynamic_Snake_Convolution_Based_on_Topological_Geometric_Constraints_for_Tubular_ICCV_2023_paper.pdf)]
* Hongliang He, Jun Wang, Pengxu Wei, Fan Xu, Xiangyang Ji, Chang Liu, and Jie Chen. "Toposeg: Topology-aware nuclear instance segmentation." CVPR'2023. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/He_TopoSeg_Topology-Aware_Nuclear_Instance_Segmentation_ICCV_2023_paper.pdf)]
* Manxi Lin, Kilian Zepf, Anders Nymark Christensen, Zahra Bashir, Morten Bo Søndergaard Svendsen, Martin Tolsgaard, and Aasa Feragen. "Dtu-net: Learning topological similarity for curvilinear structure segmentation." IPMI'2023. [[Paper](https://arxiv.org/pdf/2205.11115)]
* Meilong Xu, Xiaoling Hu, Saumya Gupta, Shahira Abousamra, and Chao Chen. "TopoSemiSeg: Enforcing Topological Consistency for Semi-Supervised Segmentation of Histopathology Images." ECCV'2024. [[Paper](https://arxiv.org/pdf/2311.16447)]
* Qian Wu, Yufei Chen, Wei Liu, Xiaodong Yue, and Xiahai Zhuang. "Deep Closing: Enhancing Topological Connectivity in Medical Tubular Segmentation." TMI'2024 [[Paper](https://ieeexplore.ieee.org/abstract/document/10540037?casa_token=FOES6ZemAOkAAAAA:r3lRafFgWh08fThQhiOwd6orIuuKG_G4GtzhCRulhVv9bBKTjh9mTJ9UjQs-QFw1ymPtsU9M67g)]
* Alexander H. Berger, Laurin Lux, Nico Stucki, Vincent Bürgin, Suprosanna Shit, Anna Banaszak, Daniel Rueckert, Ulrich Bauer, and Johannes C. Paetzold. "Topologically faithful multi-class segmentation in medical images." MICCAI'2024. [[Paper](https://arxiv.org/pdf/2403.11001)]
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
* Meilong Xu, Saumya Gupta, Xiaoling Hu, Chen Li, Shahira Abousamra, Dimitris Samaras, Prateek Prasanna, and Chao Chen. "TopoCellGen: Generating Histopathology Cell Topology with a Diffusion Model." arXiv'2024. [[Paper](https://arxiv.org/pdf/2412.06011)]

### Other Topics

## Tutorials
* [Topology-Driven Image Analysis](https://topology-miccai.github.io/)

## Workshops
* [The First Workshop on Topology- and Graph-Informed Imaging Informatics (TGI3)](https://topology-miccai.github.io/First_TGI_2024.html)

Maintainers - [Xiaoling Hu](https://github.com/HuXiaoling)
