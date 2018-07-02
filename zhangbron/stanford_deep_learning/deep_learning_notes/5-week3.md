## Various sequence to sequence architecture

### Basic Models

<img src="image/rnn1.png">



<img src="image/rnnb2.png">



### Picking the most likely sentence

 机器翻译模型与语言模型非常相似

- Beam search
- greedy search - 一般结果不好

<img src="image/rnnb3.png">

<img src="image/rnnb4.png">

<img src="image/rnnb5.png">

### Beam Search





<img src="image/rnnb6.png">

<img src="image/rnnb7.png">



### Refinements to Beam Search

- 对目标函数进行改写和规范化
- 选择B（B越大，考虑的可能性越多，会得到更好的结果但是计算速度会变慢）

<img src="image/rnnb8.png">

<img src="image/rnnb8.png">



### Error analysis in beam search







<img src="image/rnnb10.png">

<img src="image/rnnb11.png">

<img src="image/rnnb12.png">



### Bleu Score (optional)

评价机器翻译的好坏





<img src="image/rnnb13.png">

<img src="image/rnnb14.png">

<img src="image/rnnb15.png">

<img src="image/rnnb16.png">



### Attention Model Intuition

**动机**：之前讲的都是encode-decode的结构，这种结构在机器翻译当中需要记住一整个句子然后再翻译

尤其是当一个句子中单词量很多的情况下，Bleu会比较低

Attention Model Intuition 注意力模型的实现过程与人的行为更为接近，在某个时间点只看句子的一部分

<img src="image/rnnb17.png">



<img src="image/rnnb18.png">

<img src="image/rnnb16.png">

<img src="image/rnnb19.png">

<img src="image/rnnb20.png">

<img src="image/rnnb16.png">

<img src="image/rnnb16.png">

<img src="image/rnnb17.png">

<img src="image/rnnb19.png">