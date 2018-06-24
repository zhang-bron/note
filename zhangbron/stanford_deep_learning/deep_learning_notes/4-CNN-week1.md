## CNN

- 参数共享
- 连接的稀疏性

<img src="image/CNN20.png">



### Edge detection

#### 1. 垂直边缘检测

通过滤波器来对图片进行卷积计算，尺寸一般是基数

<img src="image/CNN1.png">

<img src="image/CNN2.png">

#### 2. Padding

- 在每一层卷积的时候，输出的图片尺寸不断变小，尤其是当网络很deep时
- 丢失边界上的信息

<img src="image/CNN3.png">

<img src="image/CNN4.png">

### Stride 步幅

<img src="image/CNN4.png">

<img src="image/CNN5.png">

### Cross-correlation(深度学习所用的卷积) vs convolution

在深度学习中，通常忽略掉翻转操作

<img src="image/CNN7.png">

### 三维卷积

<img src="image/CNN8.png">

<img src="image/CNN9.png">

<img src="image/CNN10.png">

<img src="image/CNN11.png">

### One layer of CNN

<img src="image/CNN12.png">

<img src="image/CNN13.png">



### Simple Convolutional Network Example

<img src="image/CNN14.png">

<img src="image/CNN15.png">

### Pooling

- Max pooling-效果好
- 均值pooling
- 有趣的是max pooling有一套超参但是不需要学习参数

<img src="image/CNN17.png">

<img src="image/CNN18.png">

<img src="image/CNN19.png">