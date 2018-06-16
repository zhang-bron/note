### 异常检测 Anomaly detection

<img src="image/anomaly.png">

### Gaussian Distribution

<img src="image/gauss.png">



<img src="image/gauss1.png">



### Algorithm

#### density estimation

<img src="image/gauss2.png">

<img src="image/gauss3.png">

<img src="image/gauss4.png">



### evaluate anomaly detection algorithm

<img src="image/gauss5.png">

<img src="image/gauss6.png">

<img src="image/gauss7.png">



### 为什么要用异常检测算法

- 什么时候应该用异常检测算法？

  <img src="image/gauss8.png">

  <img src="image/gauss9.png">

  ​

### 异常检测的特征选择

- 非高斯的情况下怎么办？
  - 通过log函数转化特征

<img src="image/gauss10.png">

<img src="image/gauss11.png">



<img src="image/gauss12.png">



### 多元高斯分布

<img src="image/gauss13.png">

<img src="image/gauss14.png">

<img src="image/gauss15.png">

<img src="image/gauss16.png">

### 异常检测之多元高斯

<img src="image/gauss17.png">

<img src="image/gauss18.png">

<img src="image/gauss19.png">

### 什么时候用原始的gauss模型，什么时候用多远高斯模型

- 当运用多元高斯模型的时候发现协方差矩阵是奇异的，那么说明
  - m < n
  - 或者 协方差中存在两个线性相关的特征（重复特征）- 此时需要检查冗余特征

<img src="image/gauss20.png">

### 推荐系统

####1. 基于内容推荐的推荐系统

- ***其实是线性回归的变形***

<img src="image/rec1.png">*

<img src="image/rec2.png">

<img src="image/rec3.png">

<img src="image/rec4.png">

### Collaborative Filtering - 协同过滤

<img src="image/rec5.png">

<img src="image/rec6.png">

<img src="image/rec7.png">

<img src="image/rec8.png">

This serves as symmetry breaking (similar to the random initialization of a neural network’s parameters) and ensures the algorithm learns features $x^{(1)}, \dots, x^{(n_m)}$ that are different from each other。

<img src="image/rec9.png">

#### 如何推荐相关联的电影

<img src="image/rec10.png">



### 均值归一化

<img src="image/rec11.png">

<img src="image/rec12.png">

<img src="image/rec10.png">









.