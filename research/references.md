# 研究参考资料

本索引按研究问题提供原始资料入口。建议先阅读量子核与搜索方法，再结合风险预测、组合优化和实验设计补齐背景。年份按所列论文或版本记录；预印本链接可能早于正式发表年份。

## 核心方法与阅读顺序

1. **[Neural Auto-designer for Enhanced Quantum Kernels](https://arxiv.org/abs/2401.11098)**（2024）。Cong Lei, Yuxuan Du, Peng Mi, Jun Yu, Tongliang Liu。
   阅读重点：量子核特征映射搜索、候选预测与排序；本项目核自设计方法的主要起点。

2. **[A Quantum Approximate Optimization Algorithm](https://arxiv.org/abs/1411.4028)**（2014）。Edward Farhi, Jeffrey Goldstone, Sam Gutmann。
   阅读重点：QAOA原始算法；用于组合目标采样启发式。

3. **[From the Quantum Approximate Optimization Algorithm to a Quantum Alternating Operator Ansatz](https://arxiv.org/abs/1709.03489)**（2019）。Stuart Hadfield, Zhihui Wang, Bryan O’Gorman, Eleanor G. Rieffel, Davide Venturelli, Rupak Biswas。
   阅读重点：受约束mixer与可行解空间。

4. **[Variational quantum algorithms](https://arxiv.org/abs/2012.09265)**（2021）。M. Cerezo, Andrew Arrasmith, Ryan Babbush, Simon C. Benjamin, Suguru Endo, Keisuke Fujii, Jarrod R. McClean, Kosuke Mitarai, Xiao Yuan, Lukasz Cincio, Patrick J. Coles。
   阅读重点：变分线路、梯度、训练与噪声背景。

5. **[Melding the Data-Decisions Pipeline: Decision-Focused Learning for Combinatorial Optimization](https://arxiv.org/abs/1809.05504)**（2019）。Bryan Wilder, Bistra Dilkina, Milind Tambe。
   阅读重点：决策聚焦学习与预测—优化接口。

6. **[Supervised quantum machine learning models are kernel methods](https://arxiv.org/abs/2101.11020)**（2021）。Maria Schuld。
   阅读重点：量子监督学习的核方法解释。

7. **[Differentiable Quantum Architecture Search](https://arxiv.org/abs/2010.08561)**（2022）。Shi-Xin Zhang, Chang-Yu Hsieh, Shengyu Zhang, Hong Yao。
   阅读重点：可微量子架构搜索。

8. **[Neural Predictor based Quantum Architecture Search](https://arxiv.org/abs/2103.06524)**（2021）。Shi-Xin Zhang, Chang-Yu Hsieh, Shengyu Zhang, Hong Yao。
   阅读重点：神经代理预测器与线路候选筛选。

9. **[On the Network Topology of Variance Decompositions: Measuring the Connectedness of Financial Firms](https://www.nber.org/papers/w17490)**（2011）。Francis X. Diebold, Kamil Yilmaz。
   阅读重点：FEVD 金融风险关联；此处引用 2011 年工作论文版本。

10. **[Portfolio Selection](https://doi.org/10.1111/j.1540-6261.1952.tb01525.x)**（1952）。Harry Markowitz。
   阅读重点：均值—方差组合选择基础。

11. **[Smart “Predict, then Optimize”](https://arxiv.org/abs/1710.08005)**（2022）。Adam N. Elmachtoub, Paul Grigas。
   阅读重点：SPO决策损失与预测优化结合。

## 雷聪署名研究：特征选择与图学习

以下相关作品用于了解特征选择、低秩表示与图学习的研究脉络。题名和作者归属已按所持论文核对；QuKerNet 见前面的核心方法。

| 年份 | 论文 | 作者 |
| --- | --- | --- |
| 2017 | [Supervised Feature Selection Algorithm Based on Low-Rank and Manifold Learning](https://doi.org/10.1007/978-3-319-69179-4_19) | Yue Fang, Jilian Zhang, Shichao Zhang, Cong Lei, Xiaoyi Hu |
| 2017 | [Unsupervised Feature Selection via Local Structure Learning and Self-Representation](https://doi.org/10.1109/ICBK.2017.22) | Shichao Zhang, Cong Lei, Yue Fang, Yangding Li, Rongyao Hu, Xiaoyi Hu |
| 2017 | [Unsupervised Spectral Feature Selection with Local Structure Learning](https://doi.org/10.1109/ICBK.2017.23) | Shichao Zhang, Yue Fang, Cong Lei, Yangding Li, Rongyao Hu, Yonggang Li |
| 2017 | [基于超图和样本自表征的谱聚类算法](https://doi.org/10.3969/j.issn.1001-3695.2017.06.005) | 李永钢, 苏毅娟, 何威, 雷聪 |
| 2018 | [Dynamic graph learning for spectral feature selection](https://doi.org/10.1007/s11042-017-5272-y) | Wei Zheng, Xiaofeng Zhu, Yonghua Zhu, Rongyao Hu, Cong Lei |
| 2018 | [Hypergraph expressing low-rank feature selection algorithm](https://doi.org/10.1007/s11042-017-5235-3) | Yue Fang, Yangding Li, Cong Lei, Yonggang Li, Xuelian Deng |
| 2018 | [Robust Graph Dimensionality Reduction](https://doi.org/10.24963/ijcai.2018/452) | Xiaofeng Zhu, Cong Lei, Hao Yu, Yonggang Li, Jiangzhang Gan, Shichao Zhang |
| 2018 | [Unsupervised feature selection by combining subspace learning with feature self-representation](https://doi.org/10.1016/j.patrec.2017.09.022) | Yangding Li, Cong Lei, Yue Fang, Rongyao Hu, Yonggang Li, Shichao Zhang |
| 2018 | [Unsupervised feature selection via local structure learning and sparse learning](https://doi.org/10.1007/s11042-017-5381-7) | Cong Lei, Xiaofeng Zhu |
| 2018 | [基于PCA的哈希图像检索算法](https://doi.org/10.3969/j.issn.1001-3695.2018.10.062) | 苏毅娟, 余浩, 雷聪, 郑威, 李永钢 |
| 2018 | [基于超图的稀疏属性选择算法](https://doi.org/10.3969/j.issn.1001-3695.2018.11.003) | 雷聪, 钟智, 胡晓依, 方月, 余浩, 郑威 |
| 2019 | [Low-rank hypergraph feature selection for multi-output regression](https://doi.org/10.1007/s11280-017-0514-5) | Xiaofeng Zhu, Rongyao Hu, Cong Lei, Kim-Han Thung, Wei Zheng, Can Wang |
| 2019 | [One-Step Multi-View Spectral Clustering](https://doi.org/10.1109/TKDE.2018.2873378) | Xiaofeng Zhu, Shichao Zhang, Wei He, Rongyao Hu, Cong Lei, Pengfei Zhu |
| 2019 | [基于核函数的低秩非线性属性选择算法](https://doi.org/10.16208/j.issn1000-7024.2019.09.025) | 李佳烨, 张乐园, 雷聪 |
| 2020 | [Self-paced Learning for K-means Clustering Algorithm](https://doi.org/10.1016/j.patrec.2018.08.028) | Hao Yu, Guoqiu Wen, Jiangzhang Gan, Wei Zheng, Cong Lei |
| 2020 | [Supervised feature selection by self-paced learning regression](https://doi.org/10.1016/j.patrec.2018.08.029) | Jiangzhang Gan, Guoqiu Wen, Hao Yu, Wei Zheng, Cong Lei |
| 2020 | [Unsupervised nonlinear feature selection algorithm via kernel function](https://doi.org/10.1007/s00521-018-3853-y) | Jiaye Li, Shichao Zhang, Leyuan Zhang, Cong Lei, Jilian Zhang |
| 2020 | [基于局部结构学习的非线性属性选择算法](https://doi.org/10.19734/j.issn.1001-3695.2018.07.0524) | 李佳烨, 张乐园, 雷聪, 甘江璋, 吕治政 |
| 2020 | [基于核稀疏表示的属性选择算法](https://doi.org/10.3969/j.issn.1007-130X.2020.01.022) | 吕治政, 李扬定, 雷聪 |
| 2021 | [Adaptive reverse graph learning for robust subspace learning](https://doi.org/10.1016/j.ipm.2021.102733) | Chang-An Yuan, Zhi Zhong, Cong Lei, Xiaofeng Zhu, Rongyao Hu |

## 补充题录

- **[Anonymizing approach to resist label-neighborhood attacks in dynamic releases of social networks](https://doi.org/10.1109/HealthCom.2017.8210763)**（2017）。Xiaoyi Hu, Li-e Wang, Jiaqi Tang, Cong Lei, Peng Liu, Xianxian Li。动态社交网络匿名化方向；目前仅核对作者题录，全文分析待补充。

## 使用方法

- 研究记录说明实际阅读的章节、使用的方法及对应实验，引用具体版本。
- 文献中的结果归属于原作者；本项目的实验记录另行给出实现、数据、预算和复核结果。
- 论文与数据的使用遵循来源许可；复用内容保留必要署名。
