# 导论
统计学习方法是机器学习的前置知识

其中学习方式有两种，一种是监督学习，一种是非监督学习
## 监督学习
基本步骤
- 得到一个有限训练集
- 确定假设空间，也就是备选模型
- 确定模型的准则，也就是学习策略
- 实现求解最优模型算法
- 通过学习方法选择最优模型
- 利用学习的最优模型对新数据预测或者分析


![_XUN HU}F}N2T3_Q 6YB3JR](https://user-images.githubusercontent.com/59946363/168828542-6d1dd897-78f7-47df-a83c-3b9f47edfeda.png)


也就是说明了整个事情需要有label进行人工标注


### 统计学习三要素
1. 模型(假设空间)
   1. 决策函数F = {f|Y=f_sitar(X),sitar属于R^n}
   2.  条件概率分布 F = {P|P_sitar(Y|X),itar属于R^n} 
2. 策略
   1. 0-1损失
    2. 平方损失
    3. 绝对值损失
    4. 对数损失 
