1. 构建二元线性回归模型，其中模型中的参数使用tf.Variable()构建，模型的样本输入使用tf.placeholder代替。写出模型结构。
2. 使用tf.placeholder代替上述样本中的标记，写出对于一个样本的代价。

在Tensorflow中主要使用类tf.Variable()来实例化一个变量对象.
引入“未知数”来参与构建图，在TensorFlow中，我们称之为占位符（placehoders）。在TensorFlow中使用tf.placeholder构建占位符。占位符也是一个节点。
