# 决策树

### 简介：

**决策树**是一种描述对*实例*分类的树状结构，由结点（node）和有向边（directed edge）组成。在进行分类时，对每个实例，从**根节点**（root）开始，根据*该实例*是否满足结点的调节，选择不同的分支进入下个结点，最终到达**叶节点**（leaf）得到分类结果。



### 特征选择：

一般样本实例有多维数据，而我们每次需要选择某一维来划分样本，这就是特征选择。



#### 信息增益：

**熵（entropy）**表示随机变量**不确定性**的度量，设$X$是一个取有限个值的离散随机变量，其概率分布

