# Boston_house_predict
波士顿房价预测

# 1、数据加载

# 2、数据探索

# 3、数据处理
将原数据根据以下三种方式进行处理并按照0.3比例切分数据集。
- 3-1 无标准化
- 3-2 Zscore标准化
- 3-3 MinMax标准化

# 4、准备模型

分别创建AdaBoostRegressor、DecisionTreeRegressor、KNeighborsRegressor、SVR模型对数据进行训练，且使用网格搜索GridSearchCV探索每个模型的最佳参数。

将每种数据处理方式和每个模型的最佳参数及最后的均方误差储存在Dataframe里面。

最后按照均方误差进行排序展示。
