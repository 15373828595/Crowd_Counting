# Crowd_Counting
密集计数的方法统计

这个仓库包含了密集计数相关的各类论文和代码

统计是按照 *基础-模型-损失函数* 顺序进行排布，每个板块里面会按照 *时间顺序* 进行排布

如果你想帮助更新我们的仓库或者有什么问题或建议，请关注 [Contributing & Contact](#contributing--contact)

# Contents
- [Crowd_Counting](#crowd_counting)
- [Contents](#contents)
- [Papers](#papers)
- [Ideas](#ideas)
- [Contributing \& Contact](#contributing--contact)

# Papers
> 本仓库按照不同的模块和时间的顺序来整理论文和相应的代码

### 基础
- **BERT：Pre-training of Deep Bidirectional Transformers for Language Understanding** [[arXiv 2019](https://arxiv.org/pdf/1810.04805.pdf)] [[Code]()]
- **End-to-End Object Detection with Transformers** [[ECCV 2020](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_13)] [[Code](https://github.com/facebookresearch/detr)]
- **An Image Is Worth 16x16 Words：Transformers For Image Recognition At Scale** [[ICLR 2021](https://arxiv.org/abs/2010.11929)] [[Code](https://github.com/lucidrains/vit-pytorch)]
- **Masked Autoencoders Are Scalable Vision Learners** [[CVPR 2022](https://arxiv.org/abs/2111.06377)] [[Code]()]
- **A ConvNet for the 2020s** [[CVPR 2022](https://arxiv.org/abs/2201.03545)] [[Code]()]
- **BiFormer：Vision Transformer with Bi-Level Routing Attention** [[CVPR 2023](https://arxiv.org/abs/2303.08810)] [[Code]()]

### 模型
- **Multi-Scale Attention Network for Crowd Counting** [[arXiv 2019](https://arxiv.org/abs/1901.06026)] [[Code]()]
- **Transformer in Convolutional Neural Networks（Vision Transformers with Hierarchical Attention）** [[arXiv 2021](https://homes.esat.kuleuven.be/~konijn/publications/2021/Liu2.pdf)] [[Code](https://github.com/yun-liu/TransCNN)]
- **CrossViT：Cross-Attention Multi-Scale Vision Transformer for Image Classification** [[ICCV 2021](https://arxiv.org/abs/2103.14899)] [[Code](https://github.com/IBM/CrossViT)]
- **Multiscale Vision Transformers** [[ICCV 2021](https://arxiv.org/abs/2104.11227)] [[Code](https://github.com/facebookresearch/SlowFast)]
- **ConViT：Improving Vision Transformers with Soft Convolutional Inductive Biases** [[PMLR 2021](http://proceedings.mlr.press/v139/d-ascoli21a/d-ascoli21a.pdf)] [[Code](https://github.com/facebookresearch/convit)]
- **CvT：Introducing Convolutions to Vision Transformers** [[ICCV 2021](https://arxiv.org/abs/2103.15808)] [[Code](https://github.com/leoxiaobin/CvT)]

### 改进模型
- **Swin Transformer：Hierarchical Vision Transformer using Shifted Windows** [[ICCV 2021](https://arxiv.org/abs/2103.14030)] [[Code](https://github.com/microsoft/Swin-Transformer)]
- **Pyramid Vision Transformer：A Versatile Backbone for Dense Prediction without Convolutions** [[ICCV 2021](https://arxiv.org/abs/2102.12122)] [[Code](https://github.com/whai362/PVT)]
- **Twins：Revisiting the Design of Spatial Attention in Vision Transformers** [[NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2021/file/4e0928de075538c593fbdabb0c5ef2c3-Paper.pdf)] [[Code](https://git.io/Twins)]
- **CONDITIONAL POSITIONAL ENCODINGS FOR VISION TRANSFORMERS** [[ICLR 2023](https://arxiv.org/abs/2102.10882)] [[Code](https://git.io/CPVT)]

### 高斯平滑损失
- **MCNN：Single-Image Crowd Counting via Multi-Column Convolutional Neural Network** [[CVPR 2016](https://openaccess.thecvf.com/content_cvpr_2016/papers/Zhang_Single-Image_Crowd_Counting_CVPR_2016_paper.pdf)] [[Code]()]
- **DENSE POINT PREDICTION：A SIMPLE BASELINE FOR CROWD COUNTING AND LOCALIZATION** [[IEEE 2021](https://ieeexplore.ieee.org/abstract/document/9455954)] [[Code]()]

### 反焦点距离损失
- **Focal Inverse Distance Transform Maps for Crowd Localization** [[IEEE 2022](https://ieeexplore.ieee.org/abstract/document/9875106)] [[Code]()]

### 贝叶斯损失
- **Bayesian Loss for Crowd Count Estimation with Point Supervision** [[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Bayesian_Loss_for_Crowd_Count_Estimation_With_Point_Supervision_ICCV_2019_paper.pdf)] [[Code](https://github.com/ZhihengCV/Baysian-Crowd-Counting)]

### 最优传输损失
- **Sinkhorn Distances：Lightspeed Computation of Optimal Transportation Distances** [[NeurIPS 2013](https://proceedings.neurips.cc/paper_files/paper/2013/file/af21d0c97db2e27e13572cbf59eb343d-Paper.pdf)] [[Code]()]
- **Computational Optimal Transport** [[RePEc 2017](https://ideas.repec.org/p/crs/wpaper/2017-86.html)] [[Code]()]
- **Distribution Matching for Crowd Counting** [[NeurIPS 2020](https://proceedings.neurips.cc/paper_files/paper/2020/file/118bd558033a1016fcc82560c65cca5f-Paper.pdf)] [[Code](https://github.com/cvlab-stonybrook/DM-Count)]
- **Learning to Count via Unbalanced Optimal Transport** [[AAAI 2021](https://ojs.aaai.org/index.php/AAAI/article/view/16332)] [[Code]()]
- **Direct Measure Matching for Crowd Counting** [[arXiv 2021](https://arxiv.org/pdf/2107.01558.pdf)] [[Code]()]
- **A Generalized Loss Function for Crowd Counting and Localization** [[CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Wan_A_Generalized_Loss_Function_for_Crowd_Counting_and_Localization_CVPR_2021_paper.pdf)] [[Code]()]

### 综合项目
- **Learning To Count Everything** [[CVPR 2021](https://arxiv.org/pdf/2104.08391.pdf)] [[Code](https://github.com/cvlab-stonybrook/LearningToCountEverything)]
- **Boosting Crowd Counting with Transformers** [[arXiv 2021](https://arxiv.org/pdf/2105.10926.pdf)] [[Code]()]
- **CCTrans：Simplifying and Improving Crowd Counting with Transformer** [[arXiv 2021](https://arxiv.org/pdf/2109.14483.pdf)] [[Code]()]
- **Boosting Crowd Counting via Multifaceted Attention** [[CVPR 2022](https://arxiv.org/pdf/2203.02636.pdf)] [[Code](https://github.com/LoraLinH/Boosting-Crowd-Counting-via-Multifaceted-Attention)]
- **TransCrowd：weakly-supervised crowd counting with transformers** [[Science China-Information Sciences（2区） 2022](https://link.springer.com/article/10.1007/s11432-021-3445-y)] [[Code]()]
- **Joint CNN and Transformer Network via weakly supervised Learning for efficient crowd counting** [[arXiv 2022](https://arxiv.org/pdf/2203.06388.pdf)] [[Code]()]
- **An End-to-End Transformer Model for Crowd Localization** [[ECCV 2022](https://arxiv.org/pdf/2202.13065.pdf)] [[Code](https://github.com/dk-liang/CLTR)]
- **Congested Crowd Instance Localization with Dilated Convolutional Swin Transformer** [[Neurocomputing（2区） 2022](https://www.sciencedirect.com/science/article/abs/pii/S0925231222012061)] [[Code]()]

# Ideas
当前的想法是，以CCTrans的模型为基础，毕竟这个是那一年的第一名，模型的修改可能会借鉴decoder的想法，引入金字塔模型，分层的去处理encoder的输出，处理的方式会使用空洞卷积；

损失函数会替换成非平衡的最优传输损失，另外我想试一下视觉定位任务的损失，能不能提升模型预测准确度。

# Contributing & Contact
您可以随时为我们的仓库贡献您的改进策略。

- 如果您想 *修改错误* ，请直接进行修改；
- 如果您想 *增加/更新* ，请遵循现有格式；
- 如果您有 *任何问题或建议* ，请通过电子邮件与我们联系（2257611653@qq.com）。

感谢您的支持！
