# test.ipynb
  - 主要是词向量，同作者的文本相似度
# 开源方案1（https://github.com/yunsuxiaozi/AI-and-competition/blob/main/2024kddWhoiswhotop37solution/2024kdd-data.ipynb）
  - 提供了一个文本可读性指数，用于衡量文本的可读性也就是i质量的特征，
  - 对特征右偏取log1p进行处理（这里其实对左偏特征也有对应的处理方法，例如：反向对数变换， 平方变换，平方根变换等）
  - 数据处理思路，如果一个特征的value_counts的含量很少，直接定为缺失值（不一定可行！）
  
