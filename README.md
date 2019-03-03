<<<<<<<
# ctr-avazu
CTR预估项目

=======
# ctr-avazu
CTR预估项目

2019.03.03

目前，代码主要包括GBDT +LR 和 FFM模型的。使用的数据是前1000000行。数据量比较小，会过拟合。

其中，GBDT +LR中运用到了，dummyPy.py中的OneHotEncoder，可以有效解决高维数据的问题，参考：https://yashuseth.blog/2017/12/14/how-to-one-hot-encode-categorical-variables-of-a-large-dataset-in-python/

而，FFM中使用了Xlearn 的库，比libffm块13倍，参考：https://blog.csdn.net/linxid/article/details/80382569
>>>>>>>