聚类的概念：

无监督问题

聚类：相似的问题聚在一起

难点：如何评估，如何调参？

基本概念：

要得到簇的个数，需要指定K值

质心：均值，向量各维取平均即可。

距离的度量：欧氏距离和余弦相似度（先标准化）

优化目标：$min \sum_{i=1}^{K} \sum_{x \epsilon C_{i}} dist(c_{i},x)^{2}$

# 优点

简单，快速，适合常规数据集

缺点：

K值难确定

复杂度与样本成线性关系

很难发现任意形状的簇

初始值非常重要，最好多次选择初始值，选择平均值。