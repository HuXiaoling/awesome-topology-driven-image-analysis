# Awesome Topology-Driven Deep Image Analysis
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources for topology-driven deep image analysis, inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision) and [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Contributing
Please feel free to [pull requests](https://github.com/HuXiaoling/awesome-topology-driven-image-analysis/pulls) or send me email (xihu3@mgh.harvard.edu) to contribute.

## Table of Contents
- [Books](#books)
- [Tools](#tools)
- [Software](#software)
- [Tutorials](#tutorials)
- [Workshops](#workshops)
- [Papers](#papers)
  - [Segmentation](#segmentation)
  - [Classification](#classification)
  - [Detection](#detection)
  - [Registration](#registration)
  - [Reconstruction](#reconstruction)
  - [Counting](#counting)
  - [Uncertainty Estimation](#uncertainty-estimation)
  - [Generative Models](#generative-models)
  - [Other Topics](#other-topics)
  
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

## Tutorials
* [Topology-Driven Image Analysis](https://topology-miccai.github.io/)

## Workshops
* [The First Workshop on Topology- and Graph-Informed Imaging Informatics (TGI3)](https://topology-miccai.github.io/First_TGI_2024.html)
* [Topology- and Graph-Informed Imaging Informatics (TGI) Track at 7th Workshop on GRaphs in biomedicAl Image anaLysis](https://topology-miccai.github.io/TGI_2025.html)

## Papers
### Segmentation
* Xiaoling Hu, Fuxin Li, Dimitris Samaras, and Chao Chen. "Topology-preserving deep image segmentation." NeurIPS'2019. [[Paper](https://proceedings.neurips.cc/paper/2019/file/2d95666e2649fcfc6e3af75e09f5adb9-Paper.pdf)]
* Zuoyue Li, Jan Dirk Wegner, and Aurélien Lucchi. "Topological map extraction from overhead images." ICCV'2019. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Topological_Map_Extraction_From_Overhead_Images_ICCV_2019_paper.pdf)]
* Samik Banerjee, Lucas Magee, Dingkang Wang, Xu Li, Bing-Xing Huo, Jaikishan Jayakumar, Katherine Matho et al. "Semantic segmentation of microscopic neuroanatomical data by combining topological priors with encoder–decoder deep networks."  NMI'2020. [[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8486300/)]
* Seung Yeon Shin, Sungwon Lee, Daniel Elton, James L. Gulley, and Ronald M. Summers. "Deep small bowel segmentation with cylindrical topological constraints." MICCAI'2020. [[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9107797/)]
* James R. Clough, Nicholas Byrne, Ilkay Oksuz, Veronika A. Zimmer, Julia A. Schnabel, Andrew P. King. "A topological loss function for deep-learning based image segmentation using persistent homology." TPAMI'2020. [[Paper](https://arxiv.org/pdf/1910.01877)]
* Xiaoling Hu, Yusu Wang, Li Fuxin, Dimitris Samaras, and Chao Chen. "Topology-aware segmentation using discrete morse theory." ICLR'2021. [[Paper](https://openreview.net/pdf?id=LGgdb4TS4Z)].
* Suprosanna Shit, Johannes C. Paetzold, Anjany Sekuboyina, Ivan Ezhov, Alexander Unger, Andrey Zhylka, Josien PW Pluim, Ulrich Bauer, and Bjoern H. Menze. "clDice-a novel topology-preserving loss function for tubular structure segmentation." CVPR'2021. [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Shit_clDice_-_A_Novel_Topology-Preserving_Loss_Function_for_Tubular_Structure_CVPR_2021_paper.pdf)]
* Mingfei Cheng, Kaili Zhao, Xuhong Guo, Yajing Xu, and Jun Guo. "Joint topology-preserving and feature-refinement network for curvilinear structure segmentation." ICCV'2021. [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Cheng_Joint_Topology-Preserving_and_Feature-Refinement_Network_for_Curvilinear_Structure_Segmentation_ICCV_2021_paper.pdf)].
* Minh Ôn Vû Ngoc, Yizi Chen, Nicolas Boutry, Joseph Chazalon, Edwin Carlinet, Jonathan Fabrizio, Clément Mallet, and Thierry Géraud. "Introducing the Boundary-Aware loss for deep image segmentation." BMVC'2021. [[Paper](https://hal.science/hal-03417244/document)]
* Doruk Oner, Mateusz Koziński, Leonardo Citraro, Nathan C. Dadap, Alexandra G. Konings, and Pascal Fua. "Promoting connectivity of network-like structures by enforcing region separation." TPAMI'2021. [[Paper](https://arxiv.org/pdf/2009.07011)]
* Xiaoling Hu. "Structure-aware image segmentation with homotopy warping." NeurIPS'2022. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/98143953a7fd1319175b491888fc8df5-Paper-Conference.pdf)]
* Saumya Gupta, Xiaoling Hu, James Kaan, Michael Jin, Mutshipay Mpoy, Katherine Chung, Gagandeep Singh et al. "Learning topological interactions for multi-class medical image segmentation." ECCV'2022. [[Paper](https://arxiv.org/pdf/2207.09654)]
* Tianyi Shi, Nicolas Boutry, Yongchao Xu, and Thierry Géraud. "Local intensity order transformation for robust curvilinear object segmentation." TIP'2022. [[Paper](https://ieeexplore.ieee.org/abstract/document/9733198)]
* Nick Byrne, James R. Clough, Israel Valverde, Giovanni Montana, and Andrew P. King. "A persistent homology-based topological loss for CNN-based multiclass segmentation of CMR." TMI'2022. [[Paper](https://ieeexplore.ieee.org/abstract/document/9872052)]
* Haotian Wang, Min Xian, and Aleksandar Vakanski. "Ta-net: Topology-aware network for gland segmentation." WACV'2022. [[Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Wang_TA-Net_Topology-Aware_Network_for_Gland_Segmentation_WACV_2022_paper.pdf)]
* Nico Stucki, Johannes C. Paetzold, Suprosanna Shit, Bjoern Menze, and Ulrich Bauer. "Topologically faithful image segmentation via induced matching of persistence barcodes." ICML'2023. [[Paper](https://proceedings.mlr.press/v202/stucki23a/stucki23a.pdf)]
* Yaolei Qi, Yuting He, Xiaoming Qi, Yuan Zhang, and Guanyu Yang. "Dynamic snake convolution based on topological geometric constraints for tubular structure segmentation." ICCV'2023. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Qi_Dynamic_Snake_Convolution_Based_on_Topological_Geometric_Constraints_for_Tubular_ICCV_2023_paper.pdf)]
* Hongliang He, Jun Wang, Pengxu Wei, Fan Xu, Xiangyang Ji, Chang Liu, and Jie Chen. "Toposeg: Topology-aware nuclear instance segmentation." CVPR'2023. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/He_TopoSeg_Topology-Aware_Nuclear_Instance_Segmentation_ICCV_2023_paper.pdf)]
* Ziyun Yang, and Sina Farsiu. "Directional connectivity-based segmentation of medical images." CVPR'2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Directional_Connectivity-Based_Segmentation_of_Medical_Images_CVPR_2023_paper.pdf)]
* Manxi Lin, Kilian Zepf, Anders Nymark Christensen, Zahra Bashir, Morten Bo Søndergaard Svendsen, Martin Tolsgaard, and Aasa Feragen. "Dtu-net: Learning topological similarity for curvilinear structure segmentation." IPMI'2023. [[Paper](https://arxiv.org/pdf/2205.11115)]
* Liu Li, Qiang Ma, Cheng Ouyang, Zeju Li, Qingjie Meng, Weitong Zhang, Mengyun Qiao et al. "Robust segmentation via topology violation detection and feature synthesis." MICCAI'2023. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_7)]
* Ainkaran Santhirasekaram, Karen Pinto, Mathias Winkler, Andrea Rockall, and Ben Glocker. "A Sheaf Theoretic Perspective for Robust Prostate Segmentation." MICCAI'2023. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_24)]
* Doruk Oner, Adélie Garin, Mateusz Koziński, Kathryn Hess, and Pascal Fua. "Persistent homology with improved locality information for more effective delineation." TPAMI'2023. [[Paper](https://arxiv.org/pdf/2110.06295)]
* Meilong Xu, Xiaoling Hu, Saumya Gupta, Shahira Abousamra, and Chao Chen. "TopoSemiSeg: Enforcing Topological Consistency for Semi-Supervised Segmentation of Histopathology Images." ECCV'2024. [[Paper](https://arxiv.org/pdf/2311.16447)]
* Jiaxing Huang, Yanfeng Zhou, Yaoru Luo, Guole Liu, Heng Guo, and Ge Yang. "Representing Topological Self-Similarity Using Fractal Feature Maps for Accurate Segmentation of Tubular Structures." ECCV'24. [[Paper](https://arxiv.org/pdf/2407.14754)]
* Qian Wu, Yufei Chen, Wei Liu, Xiaodong Yue, and Xiahai Zhuang. "Deep Closing: Enhancing Topological Connectivity in Medical Tubular Segmentation." TMI'2024 [[Paper](https://ieeexplore.ieee.org/abstract/document/10540037?casa_token=FOES6ZemAOkAAAAA:r3lRafFgWh08fThQhiOwd6orIuuKG_G4GtzhCRulhVv9bBKTjh9mTJ9UjQs-QFw1ymPtsU9M67g)]
* Alexander H. Berger, Laurin Lux, Nico Stucki, Vincent Bürgin, Suprosanna Shit, Anna Banaszak, Daniel Rueckert, Ulrich Bauer, and Johannes C. Paetzold. "Topologically faithful multi-class segmentation in medical images." MICCAI'2024. [[Paper](https://arxiv.org/pdf/2403.11001)]
* Pengcheng Shi, Jiesi Hu, Yanwu Yang, Zilve Gao, Wei Liu, and Ting Ma. "Centerline boundary dice loss for vascular segmentation." MICCAI'2024. [[Paper](https://arxiv.org/pdf/2407.01517)]
* Liu Li, Hanchun Wang, Matthew Baugh, Qiang Ma, Weitong Zhang, Cheng Ouyang, Daniel Rueckert, and Bernhard Kainz. "Universal Topology Refinement for Medical Image Segmentation with Polynomial Feature Synthesis." MICCAI'2024. [[Paper](https://arxiv.org/pdf/2409.09796)]
* Cesar Acebes, Abdel Hakim Moustafa, Oscar Camara, and Adrian Galdran. "The Centerline-Cross Entropy Loss for Vessel-Like Structure Segmentation: Better Topology Consistency Without Sacrificing Accuracy." MICCAI'2024. [[Paper](https://papers.miccai.org/miccai-2024/paper/1081_paper.pdf)]
* Madeleine K. Wyburd, Nicola K. Dinsdale, Mark Jenkinson, and Ana IL Namburete. "Anatomically plausible segmentations: Explicitly preserving topology through prior deformations." MedIA'2024. [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841524001476)]
* Nina I. Shamsi, Alec S. Xu, Lars A. Gjesteby, and Laura J. Brattain. "Improved Topological Preservation in 3D Axon Segmentation and Centerline Detection using Geometric Assessment-driven Topological Smoothing (GATS)." WACV'2024. [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Shamsi_Improved_Topological_Preservation_in_3D_Axon_Segmentation_and_Centerline_Detection_WACV_2024_paper.pdf)]
* Laurin Lux, Alexander H. Berger, Alexander Weers, Nico Stucki, Daniel Rueckert, Ulrich Bauer, Johannes C. Paetzold. "Topograph: An efficient Graph-Based Framework for Strictly Topology Preserving Image Segmentation". ICLR'2025. [[Paper](https://arxiv.org/pdf/2411.03228)]
* Liu Li, Qiang Ma, Cheng Oyang, Johannes C. Paetzold, Daniel Rueckert, and Bernhard Kainz. "Topology Optimization in Medical Image Segmentation with Fast χ Euler Characteristic." TMI'2025.[[Paper](https://arxiv.org/pdf/2507.23763)]
* Wittmann, Bastian and Wattenberg, Yannick and Amiranashvili, Tamaz and Shit, Suprosanna and Menze, Bjoern. "vesselFM: A Foundation Model for Universal 3D Blood Vessel Segmentation." CVPR'2025. [[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Wittmann_vesselFM_A_Foundation_Model_for_Universal_3D_Blood_Vessel_Segmentation_CVPR_2025_paper.pdf)]
* Ziwei Zhao and Zhixing Zhang and Yuhang Liu and Zhao Zhang and Haojun Yu and Dong Wang and Liwei Wang. "DeformCL: Learning Deformable Centerline Representation for Vessel Extraction in 3D Medical Image." CVPR'2025. [[Paper](https://arxiv.org/pdf/2506.05820v1)]
* Meilong Xu and Xiaoling Hu and Shahira Abousamra and Chen Li and Chao Chen. "MATCH: Multi-faceted Adaptive Topo-Consistency for Semi-Supervised Histopathology Segmentation." NeurIPS'2025. [[Paper](https://arxiv.org/pdf/2510.01532)]
  
### Classification
* Fan Wang, Saarthak Kapse, Steven Liu, Prateek Prasanna, and Chao Chen. "TopoTxR: a topological biomarker for predicting treatment response in breast cancer." MICCAI'2021. [[Paper](https://arxiv.org/pdf/2105.06049)]
* Yaopeng Peng, Hongxiao Wang, Milan Sonka, and Danny Z. Chen. "PHG-Net: Persistent Homology Guided Medical Image Classification." WACV'2024. [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Peng_PHG-Net_Persistent_Homology_Guided_Medical_Image_Classification_WACV_2024_paper.pdf)]
* Fan Wang, Zhilin Zou, Nicole Sakla, Luke Partyka, Nil Rawal, Gagandeep Singh, Wei Zhao et al. "TopoTxR: A topology-guided deep convolutional network for breast parenchyma learning on DCE-MRIs." MedIA'2025. [[Paper](https://arxiv.org/pdf/2411.03464)]

### Detection
* Shahira Abousamra, David Belinsky, John Van Arnam, Felicia Allard, Eric Yee, Rajarsi Gupta, Tahsin Kurc, Dimitris Samaras, Joel Saltz, and Chao Chen. "Multi-class cell detection using spatial context representation." ICCV'2021. [[Paper](https://arxiv.org/pdf/2110.04886)]

### Registration
* Madeleine K. Wyburd, Nicola K. Dinsdale, Ana IL Namburete, and Mark Jenkinson. "TEDS-Net: enforcing diffeomorphisms in spatial transformers to guarantee topology preservation in segmentations." MICCAI'2021. [[Paper](https://arxiv.org/pdf/2107.13542)]
* Yohai Reani, and Omer Bobrowski. "Cycle registration in persistent homology with applications in topological bootstrap." TPAMI'2022. [[Paper](https://arxiv.org/pdf/2101.00698)]

### Reconstruction
* Junyi Pan, Xiaoguang Han, Weikai Chen, Jiapeng Tang, and Kui Jia. "Deep mesh reconstruction from single rgb images via topology modification networks." ICCV'2019. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Pan_Deep_Mesh_Reconstruction_From_Single_RGB_Images_via_Topology_Modification_ICCV_2019_paper.pdf)]
* Dominik JE Waibel, Scott Atwell, Matthias Meier, Carsten Marr, and Bastian Rieck. "Capturing shape information with multi-scale topological loss terms for 3d reconstruction." MICCAI'2022. [[Paper](https://arxiv.org/pdf/2203.01703)]
* Doruk Oner, Hussein Osman, Mateusz Koziński, and Pascal Fua. "Enforcing connectivity of 3D linear structures using their 2D projections." MICCAI'2022. [[Paper](https://arxiv.org/pdf/2207.06832)]

### Counting
* Shahira Abousamra, Minh Hoai, Dimitris Samaras, and Chao Chen. "Localization in the crowd with topological constraints." AAAI'2021. [[Paper](https://arxiv.org/pdf/2012.12482)]

### Uncertainty Estimation
* Xiaoling Hu, Dimitris Samaras, and Chao Chen. "Learning probabilistic topological representations using discrete morse theory." ICLR'2023. [[Paper](https://openreview.net/pdf?id=cXMHQD-xQas)]
* Saumya Gupta, Yikai Zhang, Xiaoling Hu, Prateek Prasanna, and Chao Chen. "Topology-aware uncertainty for image segmentation." NeurIPS'2023. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/19ded4cfc36a7feb7fce975393d378fd-Paper-Conference.pdf)]
  
### Generative Models
* Fan Wang, Huidong Liu, Dimitris Samaras, and Chao Chen. "Topogan: A topology-aware generative adversarial network." ECCV'2020. [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480120.pdf)]
* Shahira Abousamra, Rajarsi Gupta, Tahsin Kurc, Dimitris Samaras, Joel Saltz, and Chao Chen. "Topology-guided multi-class cell context generation for digital pathology." CVPR'2023. [[Paper](https://arxiv.org/pdf/2304.02255)]
* Meilong Xu, Saumya Gupta, Xiaoling Hu, Chen Li, Shahira Abousamra, Dimitris Samaras, Prateek Prasanna, and Chao Chen. "TopoCellGen: Generating Histopathology Cell Topology with a Diffusion Model." CVPR'2025. [[Paper](https://arxiv.org/pdf/2412.06011)]

### Other Topics
* Mathieu Carriere, and Andrew Blumberg. "Multiparameter persistence image for topological machine learning." NeurIPS'2020. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2020/file/fdff71fcab656abfbefaabecab1a7f6d-Paper.pdf)]
* Fan Wang, Hubert Wagner, and Chao Chen. "GPU Computation of the Euler Characteristic Curve for Imaging Data." SoCG'2022. [[Paper](https://arxiv.org/pdf/2203.09087)]
* Theodore Papamarkou, Tolga Birdal, Michael Bronstein, Gunnar Carlsson, Justin Curry, Yue Gao, Mustafa Hajij et al. "Position: Topological Deep Learning is the New Frontier for Relational Learning." arXiv'2024. [[Paper](https://scholar9.com/publication/15b1964641a8fa968b2e1f5d42b5a8bf.pdf)]
* Chia-Chia Chen, and Chi-Han Peng. "Topology-Preserving Downsampling of Binary Images." ECCV'2024. [[Paper](https://arxiv.org/pdf/2407.17786)]
* Ilya Trofimov, Daria Voronkova, Eduard Tulchinskii, Evgeny Burnaev, and Serguei Barannikov. "Scalar Function Topology Divergence: Comparing Topology of 3D Objects." ECCV'2024. [[Paper](https://arxiv.org/pdf/2407.08364)]

Maintainers - [Xiaoling Hu](https://github.com/HuXiaoling)
