- **Author：** 马肖
- **E-Mail：** maxiaoscut@aliyun.com
- **GitHub：**  https://github.com/Albertsr

- ==**备注：由于Github无法正常显示公式，部分链接为个人整理的有道云笔记链接，若无法正常显示，请尝试刷新**==

---

## 第一部分：基础知识

### 1. 最优化
- [泰勒展开式与梯度下降法](http://note.youdao.com/noteshare?id=04b615c3ed519b08b2fadc1b31584b51&sub=BB9C8E31B8E041CAB48EBFFB86F81237)

- [牛顿法与拟牛顿法](http://note.youdao.com/noteshare?id=a833fad696ba110d0bfb3472ef9e3fb9&sub=E8D135E215314FA0B9C21103EC1AA2DB)

- [梯度下降法 vs 牛顿法](http://note.youdao.com/noteshare?id=879c45854ec2dc9bb1de214181ce4a67&sub=E09CCD8D6C154B5390F052B3CD159EC7)

### 2. 损失函数
- [六大损失函数](http://note.youdao.com/noteshare?id=b269151a475b95393019b80584e4a521&sub=4434BC48320E4A0AB2AAF95B6718B318)

- [熵、KL散度、交叉熵](http://note.youdao.com/noteshare?id=7824f4e49e0a73f0734864cc10a9b25f&sub=B0D769D4E7DE4A88BABD0C0372E6B26A)

- [Huber Loss & Fair Loss](http://note.youdao.com/noteshare?id=e724e03dd48476579e6718feedb42bb7&sub=1293076C8DEF41EE934C9DD4A15F3BBA)

- [经验风险、期望风险、结构风险](http://note.youdao.com/noteshare?id=17dda31b4a34b821ae4b3014a2af13cc&sub=73C8E3F08CB4414E8D393E4FE9461ED0)

### 3. 其他
- [Bias-Variance Tradeoff](http://note.youdao.com/noteshare?id=49c9bbe574f4d3c982c82cdde9bb0805&sub=B557C999E1FE42E6BD5BC3C8536A52C7)


- [生成模型与判别模型](http://note.youdao.com/noteshare?id=ed50912f4b1a95100513667015f3fa01&sub=DE4495BD714B4BFD8FC33585D3204A2C)


---

## 第二部分：机器学习流程


### 1. 经典非集成监督算法

#### 1.1 【逻辑回归】理论详解：[Logistic Regression](http://note.youdao.com/noteshare?id=a0d1a51a06b27665adb25196b9302a3a&sub=EF059197C6EA477E976ADD9494033C47)

#### 1.2 【决策树】理论详解：[Decision Tree](http://note.youdao.com/noteshare?id=1df47deec7d30a99b436f3c0e801db24&sub=1BCABBDFFA50404582372B2BCE9159F1)

#### 1.3 【朴素贝叶斯】理论详解： [Naive Bayesian](http://note.youdao.com/noteshare?id=7c88fb8f65d118d5c820555f865c45a7&sub=5494C55210934C17ADF503B73317851C)

#### 1.4 【支持向量机】理论详解
- **[1）凸二次规划、拉格朗日对偶性与KKT条件](http://note.youdao.com/noteshare?id=8ed93129261f6f0805be1fd7d3acbc24&sub=6945BC170DD54C559B0F689FEB8AFDE9)**

- **[2）硬间隔最大化](http://note.youdao.com/noteshare?id=2b792aa786a8d30b1a4e7108cbadf4f1&sub=410912446FD9468ABD77F581020AC8D1)**

- **[3）软间隔最大化](http://note.youdao.com/noteshare?id=ba08bc2004bde1a8e7a534d942448462&sub=B08F68399D674A44A5B4A09CB19CDEDF)**

- **[4）Kernel Trick](http://note.youdao.com/noteshare?id=fc70222f0ed0be3e41a93cdd1835bd14&sub=FDE74AB1C280401A831083001581655F)**



---

### 2. 集成算法
#### 2.1 Boosting
- **1）GBDT：[GBDT理论详解](http://note.youdao.com/noteshare?id=68a1bb88a57b867b54196f18e7ebdfcd&sub=E097CC28CB2747DCBF60FA967D93239A)**

- **2）GBDT+LR：[GBDT与LR的融合理论详解](http://note.youdao.com/noteshare?id=7a3116acb15caae65a3856e6078aa2f0&sub=46BE3B40DB1A4079AC223991FAC88BD0)**
    - [代码：lightgbm_lr.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/GBDT-LR/lightgbm_lr.py)
    - [代码：xgboost_lr.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/GBDT-LR/xgboost_lr.py)
    - [代码：gbdt_lr.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/GBDT-LR/gbdt_lr.py)
    - [GBDT系列算法与LR融合与性能对比](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/GBDT-LR/GBDT%E7%B3%BB%E5%88%97%E4%B8%8ELR%E7%9A%84%E8%9E%8D%E5%90%88%26%E6%80%A7%E8%83%BD%E5%AF%B9%E6%AF%94.ipynb)
    
    ![gbdt_lr_contrast](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/gbdt_lr_contrast.jpg)


- **3）XGBoost：[XGBoost理论详解](http://note.youdao.com/noteshare?id=8ec0afbb4b92a3ccfde94decd3bb2432&sub=2A73304730AF4BC0B0F8C53ECCA22917)**

   - **自定义损失函数：**
     - [jupyter：XGB自定义损失.ipynb](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/XGB%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8D%9F%E5%A4%B1%26%E5%8F%AF%E8%A7%86%E5%8C%96.ipynb)
     - [代码：xgb_custom_lossfunc.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/xgb_custom_lossfunc.py)
     
     ![xgb_loss](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/xgb_loss.jpg)
   
   - **通过early_stopping确定合理的基学习器个数：**
     - [jupyter：early_stopping_rounds](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/early_stopping_rounds.ipynb)
     - [代码：xgb_early_stopping.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/xgb_early_stopping.py) 
    
    ![xgb_early_stopping](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Boosting/xgb_early_stopping.jpg)

- **4）AdaBoost：[AdaBoost详解](http://note.youdao.com/noteshare?id=d0c70dcd9b716b70ecf08fb962279955&sub=27C7D5F6889241868216754956E07E5D)**

- **5) LightGBM：[LightGBM详解](http://note.youdao.com/noteshare?id=be2a01188207b095ac37af107e0ec614&sub=CA3B40E0068A495EA0019421494423A4)**

---

#### 2.2 Bagging
- [Bagging减少variance，Boosting减少bias](http://note.youdao.com/noteshare?id=5a75ad193efd2341a2b9a6c7dbf5ba9a&sub=45E8EAAE1075459695FA53B451DB7F1B)


#### 2.3 Stacking
- **1）Stacking：** [Stacking详解](http://note.youdao.com/noteshare?id=c7891b8ad0e3013e176cb73536bdfad8&sub=943369E1A3B446FC932951A45BE7986B)

- **2）二级Stacking的个人实现：** [stacking_models.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Stacking/stacking_models.py)

- **3）个人实现与Mlxtend对比：** [StackingModels_vs_Mlxtend.py](https://github.com/Albertsr/Machine-Learning/blob/master/5.%20Ensemble%20Learning/Stacking/StackingModels_vs_Mlxtend.py)

---

### 3. 聚类
#### 3.1 谱聚类：[谱聚类Spectral Clustering](http://note.youdao.com/noteshare?id=319bd869104b6674bef01dd0a3024597&sub=7740B67581D04E69A6DF492CD8E5E685)
- **1）瑞利商：[瑞利商的性质及其证明](http://note.youdao.com/noteshare?id=9f0062a660ded11f2d9434a8b9c3988a&sub=9884B7629E2E417F82666903DA60A873)**
- **2）拉普拉斯矩阵的最小特征值：[The Smallest Eigenvalues of a Graph Laplacian](http://blog.shriphani.com/2015/04/06/the-smallest-eigenvalues-of-a-graph-laplacian/)**

#### 3.2 DBSCAN：[密度聚类DBSCAN](http://note.youdao.com/noteshare?id=2f9664802a90dfd9ecb2d421014a9696&sub=0FFCFBB5E9C14B1FA1DCE510700FB23A)

#### 3.3 KMeans：[K均值聚类KMeans](http://note.youdao.com/noteshare?id=393875faf212f47a718fb5bbfce657ce&sub=03362B91CB454DFD985E4EDBA9A06596)


#### 3.4 BIRCH：[层次聚类BIRCH](http://note.youdao.com/noteshare?id=a93a6fc70108222262cc93ee3faef0a0&sub=A8848EAC58F04E08AE11D2BC424273B4)

---


### 1. 数据探索
#### [1.1 数据探索综述](https://github.com/Albertsr/Machine-Learning/tree/master/1.%20Data%20Exploration)

#### [1.2 对Titanic数据集进行探索](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/1.%20Data%20Exploration/%E4%B8%93%E9%A2%981%EF%BC%9A%E5%88%86%E7%B1%BB%E9%97%AE%E9%A2%98%E7%9A%84%E6%95%B0%E6%8D%AE%E6%8E%A2%E7%B4%A2%28%E4%BB%A5Titanic%E6%95%B0%E6%8D%AE%E9%9B%86%E4%B8%BA%E4%BE%8B%29.ipynb)

#### [1.3 回归问题中的相关系数矩阵与热力图(以Boston数据集为例)](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/1.%20Data%20Exploration/%E4%B8%93%E9%A2%982%EF%BC%9A%E5%9B%9E%E5%BD%92%E9%97%AE%E9%A2%98%E4%B8%AD%E7%9A%84%E7%9B%B8%E5%85%B3%E7%B3%BB%E6%95%B0%E7%9F%A9%E9%98%B5%E4%B8%8E%E7%83%AD%E5%8A%9B%E5%9B%BE%28%E4%BB%A5Boston%E6%95%B0%E6%8D%AE%E9%9B%86%E4%B8%BA%E4%BE%8B%29.ipynb)

#### [1.4 对iris数据集进行数据探索](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/1.%20Data%20Exploration/%E4%B8%93%E9%A2%983%EF%BC%9A%E5%AF%B9iris%E6%95%B0%E6%8D%AE%E9%9B%86%E8%BF%9B%E8%A1%8C%E6%95%B0%E6%8D%AE%E6%8E%A2%E7%B4%A2.ipynb)

### 2. 数据预处理

#### [2.1 数据预处理综述](https://github.com/Albertsr/Machine-Learning/tree/master/2.%20Data%20Preprocessing)

#### [2.2 数据的标准化、归一化与正则化](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/2.%20Data%20Preprocessing/%E4%B8%93%E9%A2%981%EF%BC%9A%E6%95%B0%E6%8D%AE%E7%9A%84%E6%A0%87%E5%87%86%E5%8C%96%E3%80%81%E5%BD%92%E4%B8%80%E5%8C%96%E4%B8%8E%E6%AD%A3%E5%88%99%E5%8C%96.ipynb)

#### [2.3 One-Hot 编码](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/2.%20Data%20Preprocessing/%E4%B8%93%E9%A2%982%EF%BC%9AOne-Hot%E7%BC%96%E7%A0%81.ipynb)

#### [2.4 特征共线性问题](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/2.%20Data%20Preprocessing/%E4%B8%93%E9%A2%984%EF%BC%9A%E5%85%B1%E7%BA%BF%E6%80%A7%E9%97%AE%E9%A2%98.ipynb)

#### [2.5 非正态分布数据的处理](https://nbviewer.jupyter.org/github/Albertsr/Machine-Learning/blob/master/2.%20Data%20Preprocessing/%E4%B8%93%E9%A2%985%EF%BC%9A%E9%9D%9E%E6%AD%A3%E6%80%81%E5%88%86%E5%B8%83%E6%95%B0%E6%8D%AE%E7%9A%84%E5%A4%84%E7%90%86.ipynb)

---

### 3. 特征工程
#### 3.1 特征选择
- **特征选择理论综述：** [特征选择详解](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.1%20Feature%20Selection/ReadMe.md)

- **代码实例**
  - **Filter：** [filter.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.1%20Feature%20Selection/filter.py)
  - **Wrapper：** [wrapper.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.1%20Feature%20Selection/wrapper.py)
  - **Embedded：** [embedded.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.1%20Feature%20Selection/embedded.py)

#### 3.2 特征抽取
- **PCA：** [PCA详解](http://note.youdao.com/noteshare?id=596c5a7394109f8da87be7ce74ee5e56&sub=AAB5BEA8761C4C40B0B60E697ED749E9)
   - 通过原矩阵的SVD实现PCA：[pca_svd.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.2%20Feature%20Extraction/pca_svd.py)
   - 通过协方差矩阵的EVD实现PCA：[pca_evd.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.2%20Feature%20Extraction/pca_evd.py)
   
- **KernelPCA：** [KernelPCA详解](http://note.youdao.com/noteshare?id=6841be74d0fcf6f6a121869d6956aad0&sub=4107BFC5B47A49DD86524504B46EA639)

- **SVD：** [SVD详解](http://note.youdao.com/noteshare?id=5ebc61d03c25c9164bc461f8fa66827d&sub=56B3F62C7C1445E6B715777AA5F15BDC)

#### 3.3 特征构建
- 高基数离散型特征的处理：[high_categorical.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.3%20Feature%20Construction/high_categorical.py)
- 时间型特征的处理：[create_time_feature.py](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.3%20Feature%20Construction/create_time_feature.py)
- 连续型特征的处理：[连续型特征的处理.ipynb](https://github.com/Albertsr/Machine-Learning/blob/master/3.%20Feature%20Engineering/3.3%20Feature%20Construction/%E8%BF%9E%E7%BB%AD%E5%9E%8B%E7%89%B9%E5%BE%81%E7%9A%84%E5%A4%84%E7%90%86.ipynb)

---



### 7. 模型评估

- **交叉验证与常见评估指标：** [交叉验证与常见评估指标](http://note.youdao.com/noteshare?id=417577308d6de13a1e21168d96cb9a76&sub=0F36C3976E3A420182A5A84782656470)

- **G-Mean与Coverage：** [G-Mean与Coverage](https://github.com/Albertsr/Anomaly-Detection#22-模型评估指标)
  - **G-Mean：** [gmean.py](https://github.com/Albertsr/Class-Imbalance/blob/master/5.%20Appropriate%20Metrics/gmean.py)

  - **Coverage：** [coverage.py](https://github.com/Albertsr/Class-Imbalance/blob/master/5.%20Appropriate%20Metrics/coverage.py)

- **KS值** 
  - [ks_value.py](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/ks_value.py) 
  - [绘制KS曲线](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/ks_curve.py)
  
  ![ks curve](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/Pics/ks%20curve.jpg)

- **ROC曲线与PRC曲线的绘制**
  - **绘制ROC代码：** [roc.py](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/roc.py)
  
  ![roc](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/Pics/roc.jpg)

  - **绘制PRC代码：** [prc.py](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/prc.py)
  
  ![prc](https://github.com/Albertsr/Machine-Learning/blob/master/7.%20Model%20Evaluation/Pics/prc.jpg)  

---

### 8. 模型持久化
- **运用joblib序列化各反序列化机器学习模型：** [joblib.py](https://github.com/Albertsr/Machine-Learning/blob/master/8.%20Model%20Persistence/joblib.py)

- **运用pickle序列化/反序列化机器学习模型：** [pickle.py](https://github.com/Albertsr/Machine-Learning/blob/master/8.%20Model%20Persistence/pickle.py)
