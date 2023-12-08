# ALBERT模型
## Way：
减少BERT的Embeeding维度来提高速率

共享和不共享参数对结果影响比较小

Layer越多越好

隐藏特征维度越大越好



# RoBERTa
## 改进： 将静态mask 改为动态mask
` Bert在训练中随机15%词汇被mask掉，在每次epoch训练时，mask是固定的。` 
