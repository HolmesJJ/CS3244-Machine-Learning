## 详解
### 基本介绍
* [【五分钟机器学习】环境会影响你的决策：K近邻算法（KNN)](https://www.bilibili.com/video/BV13K411H7Zs)
* [什么是KNN（K近邻算法）？【知多少】](https://www.bilibili.com/video/BV1Ma411F7Y4)
* [【菊安酱的机器学习】第1期 k-近邻算法 |数据分析|机器学习|算法|](https://www.bilibili.com/video/BV11b411F7sT)
* [【帅器学习/林木】K最近邻算法（KNN）](https://www.bilibili.com/video/BV1L4411c7XF)
* [第02课：KNN 算法——不学习我也能预测](https://gitbook.cn/gitchat/column/5ac2f0509e924a1dc029dd84/topic/5ac9be49dbd50e7493d34f96)
* [K NEAREST NEIGHBOR 算法](https://coolshell.cn/articles/8052.html)
* [用人话讲明白近邻算法KNN](https://zhuanlan.zhihu.com/p/79531731)


### 时间复杂度


### 分类
* [图解机器学习_k临近---1. k临近分类 kNN](https://www.bilibili.com/video/BV1By4y137Ps)
* [机器学习入门（二）：KNN分类算法和决策边界(Decision Boundary)绘制](https://blog.csdn.net/OldDriver1995/article/details/105145051)

### 回归
* [图解机器学习_k临近---7. kNN回归---scikit learn代码讲解](https://www.bilibili.com/video/BV1kb4y1C7WU?share_source=copy_web)
* [KNN算法多用于分类，但是能不能用于预测数据的值？](https://www.zhihu.com/question/277140284/answer/391612055)

### 归一化Normalization
* [Why do you need to scale data in KNN](https://stats.stackexchange.com/questions/287425/why-do-you-need-to-scale-data-in-knn)
* [KNN算法学习 -- 数据归一化处理解决量纲不同的问题](https://blog.csdn.net/qq_34734683/article/details/79521351)
* 关键点：归一化会影响分类结果

### 要点
* 通常先使用欧几里得距离
* 但任何距离度量（非负、对称、服从三角不等式）都是可能的
* 定义距离度量以适应数据的语义意义可能很重要
* KNN决策边界形成泰森多边形图
* KNN通过最近的K个训练来预测目标输入的类别，距离度量和K是超参数
    * 设置超参数：
        * 对数据的经验
        * 训练数据的保留部分：验证集
* KNN在几乎从不用于图像处理，像素上的距离度量没有信息量

## 应用
* [机器学习 KNN算法--道路数据/推荐系统（完结）](https://www.bilibili.com/video/BV1W4411m7Av)
* [协同过滤和基于内容推荐有什么区别？](https://www.zhihu.com/question/19971859)
* [推荐系统：协同过滤及其利弊](https://zhuanlan.zhihu.com/p/77983059)
* [协同过滤算法：基于用户和基于物品的优缺点比较](https://blog.csdn.net/sunkun2013/article/details/71196884)
* [推荐算法概述（基于用户的协同过滤算法、基于物品的协同过滤算法、基于内容的推荐算法）](https://blog.csdn.net/u011630575/article/details/80171597)
* [Build Your own Recommendation Engine](https://towardsai.net/p/machine-learning/build-your-own-recommendation-engine-netflix-demystified-demo-code-550401d4885e)