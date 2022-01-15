# Awesome Graph Contrastive Learning
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of Graph Contrastive Learning methods.

It's worth noting that many traditional unsupervised graph representation learning methods inherently follow the contrastive paradigm (e.g., DeepWalk, node2vec, GAE/VGAE etc.). We will not elaborate on them here.

# Quick Links:
- [Empirical Study](#empirical-study)
- [InfoMax Principle](#infomax-principle)
- [GNN Pre-Training](#gnn-pre-training)
- [Graph Augmentation](#graph-augmentation)
- [Others](#others)

# Paper references with implementation

## Empirical Study
### 2021
- **An Empirical Study of Graph Contrastive Learning (OpenReview)**
  - Authors: Yanqiao Zhu, Yichen Xu, Qiang Liu, Shu Wu
  - [[paper]](https://openreview.net/forum?id=fYxEnpY-__G)
  - [[code]](https://github.com/GraphCL/PyGCL)

- **Evaluating Modules in Graph Contrastive Learning (arXiv)**
  - Authors: Ganqu Cui, Yufeng Du, Cheng Yang, Jie Zhou, Liang Xu, Lifeng Wang, Zhiyuan Liu
  - [[paper]](https://arxiv.org/abs/2106.08171)
  - [[code]](https://github.com/thunlp/OpenGCL)

## InfoMax Principle
### 2021
- **Bipartite Graph Embedding via Mutual Information Maximization (WSDM)**
  - Authors: Jiangxia Cao, Xixun Lin, Shu Guo, Luchen Liu, Tingwen Liu, Bin Wang
  - [[paper]](https://arxiv.org/abs/2012.05442)
  - [[code]](https://github.com/caojiangxia/BiGI)

- **SUGAR: Subgraph Neural Network with Reinforcement Pooling and Self-Supervised Mutual Information Mechanism (WWW)**
  - [[paper]](https://arxiv.org/pdf/2101.08170.pdf)
  - [[code]](https://github.com/RingBDStack/SUGAR)

- **Graph Representation Learning by Ensemble Aggregating Subgraphs via Mutual Information Maximization (arXiv)**
  - Authors: Chenguang Wang, Ziwen Liu
  - [[paper]](https://arxiv.org/pdf/2103.13125.pdf)

- **Maximizing Mutual Information Across Feature and Topology Views for Learning Graph Representations (arXiv)**
  - Authors: Xiaolong Fan, Maoguo Gong, Yue Wu, Hao Li
  - [[paper]](https://arxiv.org/abs/2105.06715)

### 2020
- **Contrastive Multi-View Representation Learning on Graphs (ICML)**
  - Authors: Kaveh Hassani, Amir Hosein Khasahmadi
  - [[paper]](http://proceedings.mlr.press/v119/hassani20a/hassani20a.pdf)
  - [[code]](https://github.com/kavehhassani/mvgrl)

- **Graph Representation Learning via Graphical Mutual Information Maximization (WWW)**
  - Authors: Zhen Peng, Wenbing Huang, Minnan Luo, Qinghua Zheng, Yu Rong, Tingyang Xu, Junzhou Huang
  - [[paper]](https://arxiv.org/pdf/2002.01169.pdf)
  - [[code]](https://github.com/zpeng27/GMI)

- **InfoGraph: Unsupervised and Semi-supervised Graph-Level Representation Learning via Mutual Information Maximization (ICLR)**
  - Authors: Fan-Yun Sun, Jordan Hoffmann, Vikas Verma, Jian Tang
  - [[paper]](https://openreview.net/pdf/af171fb8c60fa180c4dcf349ccc51ff006211216.pdf)
  - [[code]](https://github.com/fanyun-sun/InfoGraph)

- **CommDGI: Community Detection Oriented Deep Graph Infomax (CIKM)**
  - Authors: Tianqi Zhang, Yun Xiong, Jiawei Zhang, Yao Zhang, Yizhu Jiao, Yangyong Zhu
  - [[paper]](https://yzjiao.github.io/CommDGI/paper.pdf)

- **Exploiting Mutual Information for Substructure-aware Graph Representation Learning (IJCAI)**
  - Authors: Pengyang Wang, Yanjie Fu, Yuanchun Zhou, Kunpeng Liu, Xiaolin Li, Kien Hua
  - [[paper]](https://dsg.cs.ucf.edu/wp-content/uploads/2020/06/IJCAI20_CAMERA_READY.pdf)

- **Attributed Network Embedding based on Mutual Information
Estimation (CIKM)**
  - Authors: Xiaomin Liang, Daifeng Li, Andrew Madden
  - [[paper]](https://dl.acm.org/doi/10.1145/3340531.3412008)
  - [[code]](https://github.com/lxm36/infomaxANE)

- **Graph Contrastive Learning with Local and Global Mutual Information Maximization (ICIT)**
  - Authors: Yifei Hu, Ya Zhang
  - [[paper]](https://dl.acm.org/doi/10.1145/3446999.3447013)

- **Unsupervised Attributed Multiplex Network Embedding (AAAI)**
  - Authors: Chanyoung Park, Donghyun Kim, Jiawei Han, Hwanjo Yu
  - [[paper]](https://arxiv.org/abs/1911.06750)
  - [[code]](https://github.com/pcy1302/DMGI)

### 2019
- **Deep Graph InfoMax (ICLR)**
  - Authors: Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm
  - [[paper]](https://openreview.net/pdf?id=rklz9iAcKQ)
  - [[code]](https://github.com/PetarV-/DGI)

- **Spatio-Temporal Deep Graph InfoMax (ICLR workshp @ RLGM)**
  - Authors: Felix L. Opolka, Aaron Solomon, Cătălina Cangea, Petar Veličković, Pietro Liò, R Devon Hjelm
  - [[paper]](https://rlgm.github.io/papers/48.pdf)


## GNN Pre-Training
### 2020
- **GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training (KDD)**
  - Authors: Jiezhong Qiu, Qibin Chen, Yuxiao Dong, Jing Zhang, Hongxia Yang, Ming Ding, Kuansan Wang, Jie Tang
  - [[paper]](https://arxiv.org/pdf/2006.09963.pdf)
  - [[code]](https://github.com/THUDM/GCC)

- **Graph Contrastive Learning with Augmentations (NeurIPS)**
  - Authors: Yuning You, Tianlong Chen, Yongduo Sui, Ting Chen, Zhangyang Wang, Yang Shen
  - [[paper]](https://proceedings.neurips.cc/paper/2020/file/3fe230348e9a12c13120749e3f9fa4cd-Paper.pdf)
  - [[code]](https://github.com/Shen-Lab/GraphCL)


## Graph Augmentation
### 2022
- **AutoGCL: Automated Graph Contrastive Learning via Learnable View Generators (AAAI)**
  - Authors: Yihang Yin, Qingzhong Wang, Siyu Huang, Haoyi Xiong, Xiang Zhang
  - [[paper]](https://arxiv.org/pdf/2109.10259.pdf)
  - [[code]](https://github.com/Somedaywilldo/AutoGCL)

### 2021

- **Graph Contrastive Learning with Adaptive Augmentation (WWW)**
  - Authors: Yanqiao Zhu, Yichen Xu, Feng Yu, Qiang Liu, Shu Wu, Liang Wang
  - [[paper]](https://arxiv.org/pdf/2010.14945.pdf)
  - [[code]](https://github.com/CRIPAC-DIG/GCA)

- **Graph Contrastive Learning Automated (ICML)**
  - Authors: Yuning You, Tianlong Chen, Yang Shen, Zhangyang Wang
  - [[paper]](https://arxiv.org/abs/2106.07594)
  - [[code]](https://github.com/Shen-Lab/GraphCL_Automated)

- **Adversarial Graph Augmentation to Improve Graph Contrastive Learning (NIPS)**
  - Authors: Susheel Suresh, Pan Li, Cong Hao, Jennifer Neville
  - [[paper]](https://arxiv.org/abs/2106.05819)
  - [[code]](https://github.com/susheels/adgcl)
  
- **Self-Supervised Graph Learning with Proximity-based Views and Channel Contrast (arXiv)**
  - Authors: Wei Zhuo, Guang Tan
  - [[paper]](https://arxiv.org/pdf/2106.03723.pdf)

- **Jointly Learnable Data Augmentations for Self-Supervised GNNs (arXiv)**
  - Authors: Zekarias T. Kefato, Sarunas Girdzijauskas, Hannes Stärk
  - [[paper]](https://arxiv.org/pdf/2108.10420.pdf)
  - [[code]](https://github.com/zekarias-tilahun/graph-surgeon)

## Others
### 2021
- **Directed Graph Contrastive Learning (NIPS)**
  - Authors: Zekun Tong, Yuxuan Liang, Henghui Ding, Yongxing Dai, Xinke Li, Changhu Wang
  - [[paper]](https://openreview.net/pdf?id=s6JD_xBS31)
  - [[code]](https://github.com/flyingtango/DiGCL)

- **InfoGCL: Information-Aware Graph Contrastive Learning (NIPS)**
  - Authors: Dongkuan Xu, Wei Cheng, Dongsheng Luo, Haifeng Chen, Xiang Zhang
  - [[paper]](https://openreview.net/pdf?id=519VBzfEaKW)

- **Graph Adversarial Self-Supervised Learning  (NIPS)**
  - Authors: Longqi Yang, Liangliang Zhang, Wenjing Yang
  - [[paper]](https://openreview.net/pdf?id=nVwJse40s1)
  - [[code]](https://github.com/LuckyZebra/GASSL)

- **Motif-Driven Contrastive Learning of Graph Representations (arXiv)**
  - Authors: Shichang Zhang, Ziniu Hu, Arjun Subramonian, Yizhou Sun
  - [[paper]](https://openreview.net/pdf?id=qcKh_Msv1GP)

- **Fairness-Aware Node Representation Learning (arXiv)**
  - Authors: Öykü Deniz Köse, Yanning Shen
  - [[paper]](https://arxiv.org/pdf/2106.05391.pdf)
  
- **Towards Domain-Agnostic Contrastive Learning (ICML)**
  - Authors: Vikas Verma, Minh-Thang Luong, Kenji Kawaguchi, Hieu Pham, Quoc V. Le
  - [[paper]](http://proceedings.mlr.press/v139/verma21a/verma21a.pdf)

- **Multi-view Graph Contrastive Representation Learning for Drug-Drug Interaction Prediction (WWW)**
  - Authors: Yingheng Wang, Yaosen Min, Xin Chen, Ji Wu
  - [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3442381.3449786)

- **Contrastive Self-supervised Learning for Graph Classification (AAAI)**
  - Authors: Jiaqi Zeng, Pengtao Xie
  - [[paper]](https://arxiv.org/abs/2009.05923)

### 2020
- **Deep Graph Contrastive Representation Learning (ICML Workshop on GRL)**
  - Authors: Yanqiao Zhu, Yichen Xu, Feng Yu, Qiang Liu, Shu Wu, Liang Wang
  - [[paper]](https://arxiv.org/pdf/2006.04131.pdf)
  - [[code]](https://github.com/CRIPAC-DIG/GRACE)

- **Sub-graph Contrast for Scalable Self-Supervised Graph Representaion Learning (ICDM)**
  - Authors: Yizhu Jiao, Yun Xiong, Jiawei Zhang, Yao Zhang, Tianqi Zhang, Yangyong Zhu
  - [[paper]](https://arxiv.org/pdf/2009.10273.pdf)
  - [[code]](https://github.com/yzjiao/Subg-Con)
