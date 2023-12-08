# ALBERT模型
## Way：
1、减少BERT的Embeeding维度来提高速率

2、共享和不共享参数对结果影响比较小

3、Layer越多越好

4、隐藏特征维度越大越好



# RoBERTa
## 改进： 将静态mask 改为动态mask
1、Bert在训练中随机15%词汇被mask掉，在每次epoch训练时，mask是固定的。

2、添加了全词mask：
`
Example： 我爱吃XXX ， 今天你跟XXX干啥了？`
