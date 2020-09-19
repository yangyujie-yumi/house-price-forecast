### house-price-forecast
#### 核心：数据管道流程化处理数据、交叉验证超参数选择、网格搜索与随即搜索
##### 1.get the data:下载数据、迅速的简单观察数据结构、划分训练集测试集
##### 2.discover and visualize the data to gain insights:可视化数据、观察相关关系、实验不同属性的组合与目标变量的相关度，这一步完成特征选取吧
##### 3.prepare the data for machine learning algorithms:数据清洗、文本数据与类别数据处理（先是文本类别应用labelencoder，之后对labelencoder结果进行独热编码，因为labelencoder会认为类别13比类别12之间的距离更大，但实际上只是一个标识，而onehot只能将整数分类值转换为热编码，所以二者结合使用）、custom transformers（自定义转换）、特征缩放、数据管道
##### 4.选择并且评估模型
##### 5.修改超参数，特征工程迭代，最好使用交叉验证，网格搜索与随即搜索，特征重要性排序与筛选

