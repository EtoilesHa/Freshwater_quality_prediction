![image](https://github.com/EtoilesHa/Freshwater_quality_prediction/assets/100062637/c38ee1d7-b0e9-4147-83c0-6788be59b3d2)# Freshwater_quality_prediction

### 内容简介： 
- 通过机器学习对输入数据进行选取，建立模型对数据进行分析，最终对淡水是否可使用做出判断；
- 在数据预处理部分：通过特征间相关性计算并合并特征， KNN插值对缺失数据处理，独热编码(one-hot)对数据进行转换，箱图处理有明显偏差的数据，XGBoost和随机森林算法筛选出与结果强相关的影响因素，用基于调整算法分 SMOTE 算法进行数据平衡处理，并将输入数据转化为可使用的形式；
- 在模型与训练部分：采用随机森林方法，对数据进行建模分析；
- 模型评估：AUC值0.92，ROC曲线光滑：
![image](https://github.com/EtoilesHa/Freshwater_quality_prediction/assets/100062637/ee708911-aece-42cf-81d6-b089c352d2e1)
 
