# 2020-2021-Seminar-Materials
##2020年-2021年讨论班ppt与论文
| Date | Title | Detail | Author | link |
| ------------- |:-------------:| -----|-----:|-----:|
| 2021.1.8 |FewRel 2.0: Towards More Challenging Few-Shot Relation Classification | 要将小样本学习模型应用到生产环境中，应具备从资源丰富领域迁移到资源匮乏领域的能力；小样本学习模型应当具备检测句子是否真的在表达某种预定义关系或者没有表达任何关系的能力。 |Gao Yifei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20210108) |
| 2020.12.4 |Hybrid Attention-Based Prototypical Networks for Noisy Few-Shot Relation Classification | 本文基于混合注意力机制的原型网络来解决小样本关系分类中的噪声问题，提出了instance-level attention和feature-level attention。 |Gao Yifei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201204) |
| 2020.11.27 |SSD: Single Shot MultiBox Detector | 这篇论文提出了单阶段目标检测算法SSD（Single Shot MultiBox Detector），基于将detection转化为regression的思路，可以一次完成目标定位与分类。该算法修改了传统的VGG16网络：将VGG16的FC6和FC7层转化为卷积层；去掉所有的Dropout层和FC8层；添加了Atrous算法，将Pool5从2x2-S2变换到3x3-S1，同时加入基于特征金字塔的检测方式，即在不同感受野的feature map上预测目标。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
| 2020.11.20 |CNN-RNN: A Unified Framework for Multi-label Image Classification | 这篇论文提出了首个多标签分类的端到端的模型CNN-RNN，全过程由深度学习模型直接学习从原始数据到期望输出的映射(无需人工干预)，基本思路是先用CNN获取图像的空间信息，然后再借助LSTM去构建图像-标签关系以及标签之间的依赖关系。 |Zhu HuiJing | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201120) |
| 2020.11.6 |Classifying Relations via Long Short Term Memory Networks along Shortest Dependency Paths | 提出了SDP-LSTM模型来对一句语句中的两个实体进行关系分类，其中该模型利用了两个实体间的最短依赖路径（shortest dependency path，SDP），而LSTM能够从SDP中选出异构信息。 |Gao Yifei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201106) |
| 2020.10.29 |Attention On Attention for  Image Captioning | 这篇论文提出了一个"Attention on Attention"(AoA)模块，该模块扩展了常规的注意力机制，以确定注意力结果和查询结果的相关性。作者将AoA应用于图像标注模型的编码器和解码器中，所得AoANet模型的性能优于以前发布的所有方法。 |Zhu HuiJing | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201029) |
| 2020.10.23 |Mask Scoring R-CNN | 这篇论文是在Mask R-CNN的基础上提出了一种给算法的“实例分割假设”打分的方法，来提高实例分割模型的性能。而通过实验证明在COCO数据集上的表现结果超越了Mask R-CNN。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201023) |
| 2020.10.13 |Mask R-CNN | 这篇论文提出了Mask RCNN算法，这是一个通用实例分割算法，可以用于做“目标检测”、“目标实例分割”、“目标关键点检测”等多种任务，相比于之前的算法，Mask RCNN都取得了不错的成绩。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201013) |
| 2020.8.23 |A Simple Neural Attentive Meta-Learner | 这篇论文提出了一类简单通用的元学习者架构，应用时序卷积更直接、更高带宽地汇总过去经验中的信息，结合软注意力查明具体的信息，缓解时序卷积只能粗略地访问很久之前信息的劣势。 |Zhu Huijing | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200823) |
| 2020.7.25 |How to Keep a Knowledge Base Synchronized with Its Encyclopedia Source |文中提出构建一个以知识库的更新频率预测器为核心组件的知识库更新系统，主要包括四个部分：Seed finding（发现种子实体）、Seed synchronizing（种子实体同步）、Entity expanding（扩展实体）、Expanded entities synchronizing（同步扩展实体）。 |Gao Yifei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200725) |
| 2020.7.18 |ImageNet: A Large-Scale Hierarchical Image Database | 这篇论文从构建过程、特征介绍和应用实例等角度介绍了计算机视觉领域常用的大型图像数据集ImageNet。 |Zhu Huijing | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200718) |
| 2020.7.13 |Modeling Relational Data with Graph Convolutional Networks | 这篇论文引入了图卷积网络(GCN)，并在此基础上提出了关系图卷积网络(R-GCNs)。然后将R-GCN应用于两个基于标准知识库完成的任务：链接预测（用于预测新事实，即挖掘知识库中已存在的实体间未有的关系）和实体分类（对知识库中实体进行分类，即恢复实体的属性），并通过实验验证了R-GCN模型的优越性。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200713) |
| 2020.6.12 |Faster AutoAugment: Learning Augmentation Strategies using Backpropagation | 这篇论文在autoaugment算法(见20200508)的基础上，扩大和连续化搜索空间，并通过引入密度匹配算法和贝叶斯优化改进搜索算法，提高了小规模训练条件下的效率。 |Zhu Huijing | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200612) |
| 2020.6.6 |Reasoning With Neural Tensor Networks for Knowledge Base Completion | 这篇论文提出了一个新的神经网络neural tensor network（NTN），它综合了几个以前的神经网络模型并提出一个强于标准神经网络层的更有力去模型化信息之间的关系的方法；提供了一个全新的方式去展现知识库里的实体，之前的论文中只是把实体表现成一个变量，然而如果实体的名称有相同的子串则不能分享统计上的相似属性。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200606) |
| 2020.5.15 |Neural Network-based Question Answering over Knowledge Graphs on Word and Character Level|知识库上的问答系统可以将自然语言问题转化为一个结构化查询语句（如SPARQL），从而快速检索知识库中知识并返回正确的答案。如何处理词汇缺项、一词多义等问题是构建基于知识库的问答系统的难点。本文提出一种用于回答简单问题的端到端的方法，利用字符和单词级别的词向量表示来解决知识库问答问题。 |Gao Yifei| [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200515) |
| 2020.5.8 |AutoAugment:Learning Augmentation Strategies from Data|这篇论文针对特定数据集适用特定数据增强方法的低可迁移性问题，将寻找最佳增强策略的问题形式化为离散搜索方法，创建搜索空间再利用搜索算法来自动搜索合适的数据增强策略。 |Zhu Huijing| [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200508) |
| 2020.4.24 |知识图谱研究进展/知识图谱构建技术综述 | 这两篇论文主要是介绍了知识图谱领域相关发展方向和相关技术的进展。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200424) |

